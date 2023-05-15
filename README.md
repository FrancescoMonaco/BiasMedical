# Debiasing of a ML model for managing the health of populations
The projects consists in taking the base model showed in "Obermeyer, Z., Powers, B., Vogeli, C., Mullainathan, S., *Dissecting racial bias in an algorithm used to manage the health of populations*, Science 366, https://escholarship.org/content/qt6h92v832/qt6h92v832.pdf, pp.447-453, 2019"
and applying some known methods for debiasing known in the literature.
A comparison is then carried out between the models, with a correlated discussion on tradeoffs and accuracy.
The models developed are:
* Decorrelated model (FairLearn Decorrelator)
* Augmented model (ADASYN)
* Model with a new label
* Adversarial neural network
