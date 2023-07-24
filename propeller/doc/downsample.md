# Downsampling the Training Data

Downsampling is a very simple way to improve the efficiency of your evolutionary runs. It might allow for deeper evolutionary searches and a greater success rate.

Using Downsampled-Lexicase selection with propeller is easy:


Set the :parent-selection argument to :ds-lexicase as follows
```clojure
lein run -m propeller.problems.simple-regression :parent-selection :ds-lexicase <ARGS>
```

Arguments:

- Case Downsampling function: ```:ds-function``` What method to select cases for the down-sample
    - Random sampling (default)
        ```clojure 
        :ds-function :case-rand 
        ```
    - Farthest First Traversal Down-sampling
         ```clojure 
        :ds-function :case-maxmin 
        ```
- Downsample Rate: `r`
What proportion of the entire training set should be in the down-sample
```clojure 
:downsample-rate 0.1
```
- Parent Sample Rate: `ρ`
What proportion of parents used to evaluate case distances.
 ```clojure 
 :ds-parent-rate 0.01
  ```
- Generation Evaluation Interval: `k`
The number of generations between successive parent evaluations. (controls how out-dated the distance info is).
 ```clojure 
 :ds-parent-gens 100
  ```
- Max Generations: `G`
The number of generations to run for before cutting off
``` clojure
:max-generations 3000
```

Example:

For example, to run the fizz buzz problem with random 5% down-sampling, keeping the computational costs equivalent, you would run the following command:
```clojure
lein run -m propeller.problems.PSB2.fizz-buzz :parent-selection :ds-lexicase :max-generations 6000 :downsample-rate 0.05 :ds-parent-rate 0 :ds-parent-gens 1 :ds-function :case-rand :case-t-size 200 :population-size 1000 :dont-end false
```

To run informed down-sampling with 10% down-sampling, 1% parent sample and k=100, you would run the following command:
```clojure
lein run -m propeller.problems.PSB2.fizz-buzz :parent-selection :ds-lexicase :max-generations 2997 :downsample-rate 0.05 :ds-parent-rate 0.1 :ds-parent-gens 100 :ds-function :case-maxmin :case-t-size 200 :population-size 1000 :dont-end false
```
