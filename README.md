# min-nfa

This respository contains the test samples S = (S_+, S_-) used for the minimal NFA inference. 
The samples are defined over the alphabets of size 2, 5, and 10. 

The files are named according to the following convention:
1. For the files over the alphabets of size 2 and 5, the naming pattern is st-N-M-plus.txt and st-N-M-minus.txt, respectively for the sets of positive (S_+) and negative (S_-) examples. The parameter N = {2, 5} stands for the alphabet size, while the parameter M = {10, 20, ..., 100} stands for the size of the given set, M = |S_+| = |S_-|.
2. For the files over the alphabet of size 10, the naming patern is ww-10-M-plus.txt and ww-10-M-minus.txt, where the meaning of the plus and minus suffix, and the parameter M is as specified above.
