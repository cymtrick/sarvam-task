# sarvam-task

Working and tested on windows 11, rtx 4090 and 4070 ti super. Please set `cuda=False` during the `load_embeddings()` and `create_dico()` stage to avoid issue in case there is no GPU. It should work automatically when all cells are run in sequence.

requirements

torch
numpy
scipy
