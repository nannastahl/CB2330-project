# CB2330 Project – Amyloid-Beta Membrane Binding

## About the project
We used a Monte Carlo simulation to model amyloid-beta binding to a lipid membrane, using one parameter, ε, representing the energy required to leave the membrane.

## Results and limitations
The forward simulation showed that higher ε values caused the peptide to remain bound, due to the low escape probability given by the Boltzmann factor.

However, our model was too simplified, with ε effectively accounting for several physical factors. This made the forward model insufficiently robust for backward inference.

We therefore used an analytical expression for ΔG with ABC-MCMC to practise the inference workflow. This allowed us to retain simulated ΔG values close to the experimental target, but a more detailed model with additional parameters would be needed for reliable inference.

## How to run
Open `project.ipynb` in Jupyter and run the cells in order. The data and its source are described in the `data/` folder.# CB2330-project
