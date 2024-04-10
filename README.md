# The Chimera and Gaggle Algorithms
The Chimera Algorithm is a novel Neural Architecture Search method able to generate and evolve the architecture of feedforward Convolutional Neural Networks based on the adaptation of the Artificial Bee Colony Algorithm to work within an Evolutionary Computation framework. The Gaggle Algorithm is an extension of the Chimera Algorithm that combines the populations generated into ensembles.

There is an example of the Chimera and the Gaggle Algorithms tested on the CIFAR-10 dataset generating models from scratch, and an example of the Gaggle Algorithm generating the models by mutating VGG11. We also provide some code to check the performance of randomly initialized or pretrained VGG11 in said dataset. Lastly, we provide the code to use the Chimera and Gaggle Algorithms on a problem of biomedical interest: the characterization of the misalignments in a CT system infered from the artifacts in the reconstructed volumes. We provide the required dataset, which can be accessed through Kaggle. 

**The instructions to replicate all experiments are laid out in each notebook's header. The seeds employed to replicate the experiments are given within.**
