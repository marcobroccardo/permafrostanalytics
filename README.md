
# PermafrostAnalytics: Repository for the Permafrost Hackathon

## Organisation

### Communication
For discussions during and after the hackathon please use the [chat room](https://matrix.to/#/!DncqFOaoXsgUnageDH:matrix.ee.ethz.ch?via=matrix.ee.ethz.ch)

### Data
During the hackathon the data will be available [here](). We will move the data to a permanent, public storage location after the hackathon.

### Code
The code you will need lives in this repository. If you want to dig deeper you can also have a look at the code for our data management package [stuett](linktostuett).

## Quickstart

* Python
* git

We recommend [Anaconda](https://www.anaconda.com/distribution/) or [Miniconda](https://docs.conda.io/en/latest/miniconda.html), the latter being a minimal (but sufficient) version of the Anaconda distribution. The following will be based on miniconda but you can use any other python environment.

### Create a new conda environment
```
conda create -n permafrost python==3.7 poetry
conda activate permafrost
```

### Download this repository and install the required packages
```
git clone [TODO:address]
git checkout hackathon
poetry install
```

### Try out an example
```
```

### Create your own idea
We encourage you to create your idea in this repository. Create a git branch and folder with the name of your idea.
At the end of the hackathon you are asked to illustrate your idea on two PDF slides which you will place in this folder. You can also share any code in this folder if you want to open source it.

```
git checkout -b youridea_name
mkdir ideas/youridea_name
```