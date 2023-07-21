# Instructions used for PushGP Experiments

*Table of Contents*
1. [Count Odds](#count-odds)
2. [Find Pair](#find-pair)
3. [Fizz Buzz](#fizz-buzz)
4. [Fuel Cost](#fuel-cost)
5. [GCD](#gcd)
6. [Grade](#grade)
7. [Scrabble Score](#scrabble-score)
8. [Small Or Large](#small-or-large)

## Count Odds

| Type   | Instructions  |
|---|---|
| Boolean  | :boolean_and :boolean_deep_dup :boolean_dup :boolean_dup_items :boolean_dup_times :boolean_empty :boolean_eq :boolean_flush :boolean_from_integer :boolean_invert_first_then_and :boolean_invert_second_then_and :boolean_not :boolean_or :boolean_pop :boolean_print :boolean_rot :boolean_shove :boolean_stack_depth :boolean_swap :boolean_xor :boolean_yank :boolean_yank_dup  |
| Exec  | :exec_deep_dup :exec_do_count :exec_do_range :exec_do_times :exec_do_while :exec_dup :exec_dup_items :exec_dup_times :exec_empty :exec_eq :exec_flush :exec_if :exec_k :exec_pop :exec_print :exec_rot :exec_s :exec_shove :exec_stack_depth :exec_swap :exec_when :exec_while :exec_y :exec_yank :exec_yank_dup  |
| Integer | :integer_add :integer_dec :integer_deep_dup :integer_dup :integer_dup_items :integer_dup_times :integer_empty :integer_eq :integer_flush :integer_from_boolean :integer_gt :integer_gte :integer_inc :integer_lt :integer_lte :integer_max :integer_min :integer_mod :integer_mult :integer_pop :integer_print :integer_quot :integer_rot :integer_shove :integer_stack_depth :integer_subtract :integer_swap :integer_yank :integer_yank_dup   |
| Vector of Integer  | :vector_integer_butlast :vector_integer_concat :vector_integer_conj :vector_integer_contains :vector_integer_deep_dup :vector_integer_dup :vector_integer_dup_items :vector_integer_dup_times :vector_integer_empty :vector_integer_emptyvector :vector_integer_eq :vector_integer_first :vector_integer_flush :vector_integer_indexof :vector_integer_iterate :vector_integer_last :vector_integer_length :vector_integer_nth :vector_integer_occurrencesof :vector_integer_pop :vector_integer_print :vector_integer_pushall :vector_integer_remove :vector_integer_replace :vector_integer_replacefirst :vector_integer_rest :vector_integer_reverse :vector_integer_rot :vector_integer_set :vector_integer_shove :vector_integer_stack_depth :vector_integer_subvec :vector_integer_swap :vector_integer_take :vector_integer_yank :vector_integer_yank_dup  |
| Input  | :in1  |
| Special  | :print_newline close  |
| Constants  | 0 1 2 *random int*  |


## Find Pair
| Type   | Instructions  |
|---|---|
| Boolean  | :boolean_and :boolean_deep_dup :boolean_dup :boolean_dup_items :boolean_dup_times :boolean_empty :boolean_eq :boolean_flush :boolean_from_integer :boolean_invert_first_then_and :boolean_invert_second_then_and :boolean_not :boolean_or :boolean_pop :boolean_print :boolean_rot :boolean_shove :boolean_stack_depth :boolean_swap :boolean_xor :boolean_yank :boolean_yank_dup  |
| Exec  | :exec_deep_dup :exec_do_count :exec_do_range :exec_do_times :exec_do_while :exec_dup :exec_dup_items :exec_dup_times :exec_empty :exec_eq :exec_flush :exec_if :exec_k :exec_pop :exec_print :exec_rot :exec_s :exec_shove :exec_stack_depth :exec_swap :exec_when :exec_while :exec_y :exec_yank :exec_yank_dup  |
| Integer | :integer_add :integer_dec :integer_deep_dup :integer_dup :integer_dup_items :integer_dup_times :integer_empty :integer_eq :integer_flush :integer_from_boolean :integer_gt :integer_gte :integer_inc :integer_lt :integer_lte :integer_max :integer_min :integer_mod :integer_mult :integer_pop :integer_print :integer_quot :integer_rot :integer_shove :integer_stack_depth :integer_subtract :integer_swap :integer_yank :integer_yank_dup   |
| Vector of Integer  | :vector_integer_butlast :vector_integer_concat :vector_integer_conj :vector_integer_contains :vector_integer_deep_dup :vector_integer_dup :vector_integer_dup_items :vector_integer_dup_times :vector_integer_empty :vector_integer_emptyvector :vector_integer_eq :vector_integer_first :vector_integer_flush :vector_integer_indexof :vector_integer_iterate :vector_integer_last :vector_integer_length :vector_integer_nth :vector_integer_occurrencesof :vector_integer_pop :vector_integer_print :vector_integer_pushall :vector_integer_remove :vector_integer_replace :vector_integer_replacefirst :vector_integer_rest :vector_integer_reverse :vector_integer_rot :vector_integer_set :vector_integer_shove :vector_integer_stack_depth :vector_integer_subvec :vector_integer_swap :vector_integer_take :vector_integer_yank :vector_integer_yank_dup  |
| Input  | :in1  :in2 |
| Output | :output-one :output-two |
| Special  | :print_newline close  |
| Constants  | -1 0 1 2 *random int*  |


## Fizz Buzz

| Type   | Instructions  |
|---|---|
| Boolean | :boolean_and :boolean_deep_dup :boolean_dup :boolean_dup_items :boolean_dup_times :boolean_empty :boolean_eq :boolean_flush :boolean_from_integer :boolean_invert_first_then_and :boolean_invert_second_then_and :boolean_not :boolean_or :boolean_pop :boolean_print :boolean_rot :boolean_shove :boolean_stack_depth :boolean_swap :boolean_xor :boolean_yank :boolean_yank_dup  |
| Exec  |  :exec_deep_dup :exec_do_count :exec_do_range :exec_do_times :exec_do_while :exec_dup :exec_dup_items :exec_dup_times :exec_empty :exec_eq :exec_flush :exec_if :exec_k :exec_pop :exec_print :exec_rot :exec_s :exec_shove :exec_stack_depth :exec_swap :exec_when :exec_while :exec_y :exec_yank :exec_yank_dup   |
| Integer | :integer_add :integer_dec :integer_deep_dup :integer_dup :integer_dup_items :integer_dup_times :integer_empty :integer_eq :integer_flush :integer_from_boolean :integer_from_string :integer_gt :integer_gte :integer_inc :integer_lt :integer_lte :integer_max :integer_min :integer_mod :integer_mult :integer_pop :integer_print :integer_quot :integer_rot :integer_shove :integer_stack_depth :integer_subtract :integer_swap :integer_yank :integer_yank_dup  |
| String | :string_butlast :string_concat :string_contains :string_deep_dup :string_drop :string_dup :string_dup_items :string_dup_times :string_empty :string_empty_string :string_eq :string_flush :string_from_boolean :string_from_integer :string_length :string_parse_to_chars :string_pop :string_print :string_replace :string_replace_first :string_rest :string_reverse :string_rot :string_shove :string_split :string_stack_depth :string_substr :string_swap :string_take :string_yank :string_yank_dup | 
| Input  | :in1 |
| Special  | :print_newline close  |
| Constants  | "Fizz" "Buzz" "FizzBuzz" 0 3 5|

## Fuel Cost
| Type   | Instructions  |
|---|---|
| Boolean  | :boolean_and :boolean_deep_dup :boolean_dup :boolean_dup_items :boolean_dup_times :boolean_empty :boolean_eq :boolean_flush :boolean_from_integer :boolean_invert_first_then_and :boolean_invert_second_then_and :boolean_not :boolean_or :boolean_pop :boolean_print :boolean_rot :boolean_shove :boolean_stack_depth :boolean_swap :boolean_xor :boolean_yank :boolean_yank_dup  |
| Exec  | :exec_deep_dup :exec_do_count :exec_do_range :exec_do_times :exec_do_while :exec_dup :exec_dup_items :exec_dup_times :exec_empty :exec_eq :exec_flush :exec_if :exec_k :exec_pop :exec_print :exec_rot :exec_s :exec_shove :exec_stack_depth :exec_swap :exec_when :exec_while :exec_y :exec_yank :exec_yank_dup  |
| Integer | :integer_add :integer_dec :integer_deep_dup :integer_dup :integer_dup_items :integer_dup_times :integer_empty :integer_eq :integer_flush :integer_from_boolean :integer_gt :integer_gte :integer_inc :integer_lt :integer_lte :integer_max :integer_min :integer_mod :integer_mult :integer_pop :integer_print :integer_quot :integer_rot :integer_shove :integer_stack_depth :integer_subtract :integer_swap :integer_yank :integer_yank_dup   |
| Vector of Integer  | :vector_integer_butlast :vector_integer_concat :vector_integer_conj :vector_integer_contains :vector_integer_deep_dup :vector_integer_dup :vector_integer_dup_items :vector_integer_dup_times :vector_integer_empty :vector_integer_emptyvector :vector_integer_eq :vector_integer_first :vector_integer_flush :vector_integer_indexof :vector_integer_iterate :vector_integer_last :vector_integer_length :vector_integer_nth :vector_integer_occurrencesof :vector_integer_pop :vector_integer_print :vector_integer_pushall :vector_integer_remove :vector_integer_replace :vector_integer_replacefirst :vector_integer_rest :vector_integer_reverse :vector_integer_rot :vector_integer_set :vector_integer_shove :vector_integer_stack_depth :vector_integer_subvec :vector_integer_swap :vector_integer_take :vector_integer_yank :vector_integer_yank_dup  |
| Input  | :in1  |
| Special  | :print_newline close  |
| Constants  | 0 1 2 3 *random int*  |


## GCD

| Type   | Instructions  |
|---|---|
| Boolean |:boolean_and :boolean_deep_dup :boolean_dup :boolean_dup_items :boolean_dup_times :boolean_empty :boolean_eq :boolean_flush :boolean_from_integer :boolean_invert_first_then_and :boolean_invert_second_then_and :boolean_not :boolean_or :boolean_pop :boolean_print :boolean_rot :boolean_shove :boolean_stack_depth :boolean_swap :boolean_xor :boolean_yank :boolean_yank_dup |
| Exec  |  :exec_deep_dup :exec_do_count :exec_do_range :exec_do_times :exec_do_while :exec_dup :exec_dup_items :exec_dup_times :exec_empty :exec_eq :exec_flush :exec_if :exec_k :exec_pop :exec_print :exec_rot :exec_s :exec_shove :exec_stack_depth :exec_swap :exec_when :exec_while :exec_y :exec_yank :exec_yank_dup    |
| Integer | :integer_add :integer_dec :integer_deep_dup :integer_dup :integer_dup_items :integer_dup_times :integer_empty :integer_eq :integer_flush :integer_from_boolean :integer_gt :integer_gte :integer_inc :integer_lt :integer_lte :integer_max :integer_min :integer_mod :integer_mult :integer_pop :integer_print :integer_quot :integer_rot :integer_shove :integer_stack_depth :integer_subtract :integer_swap :integer_yank :integer_yank_dup  |
| Input  | :in1 :in2 |
| Special  | :print_newline close  |
| Constants  | *random int*|


## Grade

| Type   | Instructions  |
|---|---|
| Boolean | :boolean_and :boolean_deep_dup :boolean_dup :boolean_dup_items :boolean_dup_times :boolean_empty :boolean_eq :boolean_flush :boolean_from_integer :boolean_invert_first_then_and :boolean_invert_second_then_and :boolean_not :boolean_or :boolean_pop :boolean_print :boolean_rot :boolean_shove :boolean_stack_depth :boolean_swap :boolean_xor :boolean_yank :boolean_yank_dup  |
| Exec  |  :exec_deep_dup :exec_do_count :exec_do_range :exec_do_times :exec_do_while :exec_dup :exec_dup_items :exec_dup_times :exec_empty :exec_eq :exec_flush :exec_if :exec_k :exec_pop :exec_print :exec_rot :exec_s :exec_shove :exec_stack_depth :exec_swap :exec_when :exec_while :exec_y :exec_yank :exec_yank_dup   |
| Integer | :integer_add :integer_dec :integer_deep_dup :integer_dup :integer_dup_items :integer_dup_times :integer_empty :integer_eq :integer_flush :integer_from_boolean :integer_from_string :integer_gt :integer_gte :integer_inc :integer_lt :integer_lte :integer_max :integer_min :integer_mod :integer_mult :integer_pop :integer_print :integer_quot :integer_rot :integer_shove :integer_stack_depth :integer_subtract :integer_swap :integer_yank :integer_yank_dup  |
| String | :string_butlast :string_concat :string_contains :string_deep_dup :string_drop :string_dup :string_dup_items :string_dup_times :string_empty :string_empty_string :string_eq :string_flush :string_from_boolean :string_from_integer :string_length :string_parse_to_chars :string_pop :string_print :string_replace :string_replace_first :string_rest :string_reverse :string_rot :string_shove :string_split :string_stack_depth :string_substr :string_swap :string_take :string_yank :string_yank_dup | 
| Input  | :in1  :in2 :in3 :in4 :in5|
| Special  | :print_newline close  |
| Constants  | "A" "B" "C" "D" "F" *random int*|

##  Scrabble Score

| Type   | Instructions  |
|---|---|
| Boolean |:boolean_and :boolean_deep_dup :boolean_dup :boolean_dup_items :boolean_dup_times :boolean_empty :boolean_eq :boolean_flush :boolean_from_integer :boolean_invert_first_then_and :boolean_invert_second_then_and :boolean_not :boolean_or :boolean_pop :boolean_rot :boolean_shove :boolean_stack_depth :boolean_swap :boolean_xor :boolean_yank :boolean_yank_dup  |
| Char |  :char_all_from_string :char_deep_dup :char_dup :char_dup_items :char_dup_times :char_empty :char_eq :char_flush :char_from_integer :char_is_digit :char_is_letter :char_is_whitespace :char_pop :char_rot :char_shove :char_stack_depth :char_swap :char_yank :char_yank_dup |
| Exec  | :exec_deep_dup :exec_do_count :exec_do_range :exec_do_times :exec_do_while :exec_dup :exec_dup_items :exec_dup_times :exec_empty :exec_eq :exec_flush :exec_if :exec_k :exec_pop :exec_rot :exec_s :exec_shove :exec_stack_depth :exec_swap :exec_when :exec_while :exec_y :exec_yank :exec_yank_dup  |
| Integer |:integer_add :integer_dec :integer_deep_dup :integer_dup :integer_dup_items :integer_dup_times :integer_empty :integer_eq :integer_flush :integer_from_boolean :integer_from_char :integer_from_string :integer_gt :integer_gte :integer_inc :integer_lt :integer_lte :integer_max :integer_min :integer_mod :integer_mult :integer_pop :integer_quot :integer_rot :integer_shove :integer_stack_depth :integer_subtract :integer_swap :integer_yank :integer_yank_dup  |
| String | :string_butlast :string_concat :string_conj_char :string_contains :string_contains_char :string_deep_dup :string_drop :string_dup :string_dup_items :string_dup_times :string_empty :string_empty_string :string_eq :string_first :string_flush :string_from_boolean :string_from_char :string_from_integer :string_indexof_char :string_iterate :string_last :string_length :string_nth :string_occurencesof_char :string_parse_to_chars :string_pop :string_remove_char :string_replace :string_replace_char :string_replace_first :string_replace_first_char :string_rest :string_reverse :string_rot :string_set_char :string_shove :string_split :string_stack_depth :string_substr :string_swap :string_take :string_yank :string_yank_dup  | 
| Vector of Integer | :vector_integer_butlast :vector_integer_concat :vector_integer_conj :vector_integer_contains :vector_integer_deep_dup :vector_integer_dup :vector_integer_dup_items :vector_integer_dup_times :vector_integer_empty :vector_integer_emptyvector :vector_integer_eq :vector_integer_first :vector_integer_flush :vector_integer_indexof :vector_integer_iterate :vector_integer_last :vector_integer_length :vector_integer_nth :vector_integer_occurrencesof :vector_integer_pop :vector_integer_pushall :vector_integer_remove :vector_integer_replace :vector_integer_replacefirst :vector_integer_rest :vector_integer_reverse :vector_integer_rot :vector_integer_set :vector_integer_shove :vector_integer_stack_depth :vector_integer_subvec :vector_integer_swap :vector_integer_take :vector_integer_yank :vector_integer_yank_dup | 
| Input  | :in1 |
| Special  | :print_newline close  |
| Constants  | \[0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 1 3 3 2 1 4 2 4 1 8 5 1 3 1 1 3 10 1 1 1 1 4 4 8 4 10 0 0 0 0 0 0 1 3 3 2 1 4 2 4 1 8 5 1 3 1 1 3 10 1 1 1 1 4 4 8 4 10 0 0 0 0\]|

The vector of integers in the constants section is mapping from the letter to the scrabble score of that letter

## Small Or Large

| Type   | Instructions  |
|---|---|
| Boolean | :boolean_and :boolean_deep_dup :boolean_dup :boolean_dup_items :boolean_dup_times :boolean_empty :boolean_eq :boolean_flush :boolean_from_integer :boolean_invert_first_then_and :boolean_invert_second_then_and :boolean_not :boolean_or :boolean_pop :boolean_print :boolean_rot :boolean_shove :boolean_stack_depth :boolean_swap :boolean_xor :boolean_yank :boolean_yank_dup  |
| Exec  |  :exec_deep_dup :exec_do_count :exec_do_range :exec_do_times :exec_do_while :exec_dup :exec_dup_items :exec_dup_times :exec_empty :exec_eq :exec_flush :exec_if :exec_k :exec_pop :exec_print :exec_rot :exec_s :exec_shove :exec_stack_depth :exec_swap :exec_when :exec_while :exec_y :exec_yank :exec_yank_dup   |
| Integer | :integer_add :integer_dec :integer_deep_dup :integer_dup :integer_dup_items :integer_dup_times :integer_empty :integer_eq :integer_flush :integer_from_boolean :integer_from_string :integer_gt :integer_gte :integer_inc :integer_lt :integer_lte :integer_max :integer_min :integer_mod :integer_mult :integer_pop :integer_print :integer_quot :integer_rot :integer_shove :integer_stack_depth :integer_subtract :integer_swap :integer_yank :integer_yank_dup  |
| String | :string_butlast :string_concat :string_contains :string_deep_dup :string_drop :string_dup :string_dup_items :string_dup_times :string_empty :string_empty_string :string_eq :string_flush :string_from_boolean :string_from_integer :string_length :string_parse_to_chars :string_pop :string_print :string_replace :string_replace_first :string_rest :string_reverse :string_rot :string_shove :string_split :string_stack_depth :string_substr :string_swap :string_take :string_yank :string_yank_dup | 
| Input  | :in1 |
| Special  | :print_newline close  |
| Constants  | "" "small" "large" *random int*|