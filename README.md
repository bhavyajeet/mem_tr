# mem_tr

This repository contains the code for the memtr paper

There are two directories, xcai and upma. xcai contains the utility scrips necessary for evaluation and data construction. 

Upma contains the scripts for training and evaluation. 

Each python script in `upma/upma` contains one of the ablations or experiments described in the paper/ 

The bash scripts to train the linker module can be found in `upma/scripts/03-beir_linker.sh`

The script to run any specific version of the memory augmented transformer can be found in `upma/scripts/04-beir_upma.sh`