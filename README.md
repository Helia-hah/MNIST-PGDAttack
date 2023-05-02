# PGD-Attack
In this project,the both targeted and non-targeted PGD attack algorithms were developed and a CNN model for the MNIST dataset was trained based on perturbed data.

* Classifier1: non-targeted 20-step PGD attack (perturbation radius ϵ = 0.3, step size α = 0.02)
* Classifier2: non-targeted 1-step PGD attack (perturbation radius ϵ = 0.3,step size α = 0.5)
* Classifier3: targeted 20-step PGD attack (perturbation radius ϵ = 0.3, step size α = 0.02)

At the end, the built classifiers on the testing set using both the targeted and non-targeted 40-step PGD
attack were evaluated based on different perturbation radius ϵ ∈ {0, 0.1, 0.2, 0.3, 0.45}.
