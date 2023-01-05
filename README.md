# Convolutive audio source separation using robust ICA and an intelligent evolving permutation ambiguity solution

## Abstract
Audio source separation is the task of isolating sound sources that are active simultaneously in a room captured by a set of microphones. Convolutive audio source separation of equal number of sources and microphones has a number of shortcomings including the complexity of frequency-domain ICA, the permutation ambiguity and the problem’s scalabity with increasing number of sensors. In this paper, the authors propose a multiple-microphone audio source separation algorithm based on a previous work of Mitianoudis and Davies [1]. Complex FastICA is substituted by Robust ICA increasing robustness and performance. Permutation ambiguity is solved using two methodologies. The first is using the Likelihood Ration Jump solution, which is now modified to decrease computational complexity in the case of multiple microphones. The application of the MuSIC algorithm, as a preprocessing step to the previous solution, forms a second methodology with promising results.

## Paper

The paper is available from [here](https://link.springer.com/article/10.1007/s12530-017-9199-3).

## Audio Samples

Audio samples can be found [here](https://tsgouros09.github.io/RLRJ). 

## Citation
Please cite the following paper, if you are using this code.

Mallis, D., Sgouros, T., & Mitianoudis, N. (2018). Convolutive audio source separation using robust ICA and an intelligent evolving permutation ambiguity solution. Evolving Systems, 9(4), 315-329.
