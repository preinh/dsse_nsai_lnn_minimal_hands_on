# NSAI: LNN minimal hands on for CAO-DSSE

The goal of this repo is to give you the chance to play with a piece of what we've been talking about.
If we had successfully engaged you so you decided to spend some time here, you may be able to earn a 'Badge'.

### Setting up the playground:

1. Let's create a fresh environment using `conda`:
```bash
export CONDA_ENV_NAME=dsse_lnn
conda create --name $CONDA_ENV_NAME python=3.9 pip ipykernel
conda activate $CONDA_ENV_NAME
```

2. And then add the LNN package (with tutorials) by cloning their repository and install it from the local source:

```bash
# i. clone
git clone git@github.ibm.com:IBM-Research-AI/LNN.git
# Or from the latest development branch:
# git clone git@github.ibm.com:IBM-Research-AI/LNN.git@develop

# ii. install
cd LNN
pip install .
cd ..
```