
Code for the paper "Informed Down-Sampled Lexicase Selection: Identifying productive training cases for efficient problem solving"

# Authors

[Ryan Boldi](https://ryanboldi.github.io/)\*, [Martin Briesch](https://en.wi.bwl.uni-mainz.de/martin-briesch/)\*, [Dominik Sobania](https://en.wi.bwl.uni-mainz.de/dominik-sobania/), [Alexander Lalejini](https://lalejini.com/), [Thomas Helmuth](https://cs.hamilton.edu/~thelmuth/index.html), [Franz Rothlauf](https://en.wi.bwl.uni-mainz.de/franz-rothlauf/), [Charles Ofria](https://ofria.com/), and [Lee Spector](https://lspector.github.io/)

\* = Equal Contribution First Authors

# Abstract

Genetic Programming (GP) often uses large training sets and requires all individuals to be evaluated on all training cases during selection. Random down-sampled lexicase selection evaluates individuals on only a random subset of the training cases allowing for more individuals to be explored with the same amount of program executions. However, creating a down-sample randomly might exclude important cases from the current down-sample for a number of generations, while cases that measure the same behavior (synonymous cases) may be overused despite their redundancy. In this work, we introduce Informed Down-Sampled Lexicase Selection. This method leverages population statistics to build down-samples that contain more distinct and therefore informative training cases. Through an empirical investigation across two different GP systems (PushGP and Grammar-Guided GP), we find that informed down-sampling significantly outperforms random down-sampling on a set of contemporary program synthesis benchmark problems. Through an analysis of the created down-samples, we find that important training cases are included in the down-sample consistently across independent evolutionary runs and systems. We hypothesize that this improvement can be attributed to the ability of Informed Down-Sampled Lexicase Selection to maintain more specialist individuals over the course of evolution, while also benefiting from reduced per-evaluation costs.

# Link

Preprint: [https://arxiv.org/abs/2301.01488](https://arxiv.org/abs/2301.01488)

# Citation

If you use this code, please cite the paper:

```
@misc{boldi2023informed,
  doi = {10.48550/ARXIV.2301.01488},
  url = {https://arxiv.org/abs/},
  author = {Boldi, Ryan and Briesch, Martin and Sobania, Dominik and Lalejini, Alexander and Helmuth, Thomas and Rothlauf, Franz and Ofria, Charles and Spector, Lee},
  keywords = {Neural and Evolutionary Computing (cs.NE), FOS: Computer and information sciences, FOS: Computer and information sciences},
  title = {Informed Down-Sampled Lexicase Selection: Identifying productive training cases for efficient problem solving},
  publisher = {arXiv},
  year = {2023},
  arxiv = {2301.01488},
  bibtex_show = {true},
  copyright = {arXiv.org perpetual, non-exclusive license}
}

```

# Code

The code for the PushGP portion of the experiments can be found in this repository [here]()

The code for the G3P portion of the experiements can be found [here](https://gitlab.rlp.net/mbriesc/informed-down-sampled-lexicase-selection)



# Supplement

You can find supplemental material hosted here:

### [PushGP Instruction Sets](/supplement/instructionsPushGP.md)
- This file details the exact list of instructions and constants available to PushGP for each of the problems studied.
### [G3P Grammars](/supplement/grammarsG3P.md)
- This file details the exact list of grammars used when doing grammar guided genetic programming for each of the problem studied.
- You can also find them in `.bnf` format [here](https://github.com/ryanboldi/Informed-Down-Sampled-Lexicase/tree/bbfa308ad8967d7662a7433ad4ed700cbf9ae346/supplement/awsupplementforids)

