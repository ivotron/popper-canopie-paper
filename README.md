# CANOPIE paper artifacts

The repository is structued as follows:

* `workflows/`: Contains the Popper workflows for doing an MNIST training on a Local machine,  a Kubernetes cluster and a Slurm cluster and also instructions for executing them.

* `paper/`: Contains the paper and the static assets used in the paper along with a Popper workflow to plot the results and build the paper after running an experiment.

* `results/`: The location where result files get generated after running the experiment workflows. It also contains a Jupyter notebook to plot the results which is executed by the workflow here.