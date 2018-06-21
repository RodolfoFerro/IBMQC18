# IBM Quantum Computing Workshop 2018

***Description:** To be added.*

<center>
  <img src="https://image.flaticon.com/icons/svg/189/189810.svg" width="5%">
</center>

## Structure

You'll find several folders in this repo, which contain all the content created during this workshop. The main structure is as follows:

- 📁 **[docs](https://github.com/RodolfoFerro/IBMQC18/tree/master/docs):** Contains all documentation (slides, papers, etc.) reviewed or recommended during the workshop.

<center>
  <img src="https://image.flaticon.com/icons/svg/189/189810.svg" width="5%">
</center>

## Requirements

<img src="https://upload.wikimedia.org/wikipedia/commons/c/c3/Python-logo-notext.svg" width="5%"> <img src="https://image.flaticon.com/icons/svg/109/109526.svg" width="1.5%"> <img src="https://gitlab.eurecom.fr/zoe-apps/pytorch/avatar" width="5.5%">

For this workshop [Python 3](https://www.python.org/) will be needed, and [Jupyter Notebooks](http://jupyter.org/) will be very useful.

<img src="https://raw.githubusercontent.com/QISKit/qiskit-tutorial/master/images/qiskit-heading.gif" width="18%">

Install the ***"[Open Source Quantum Information Science Kit](https://qiskit.org/)"*** (*[QISKit](https://qiskit.org/)*) directly with `pip` as follows:

```bash
[python3] $ pip install qiskit
```

We'll run some `qiskit` examples (found in the offial repo [QISKit/qiskit-tutorial](https://github.com/QISKit/qiskit-tutorial)) inside an IBM quantum computer, so we'll need extra installations. To do so, please follow the instructions from **[HERE](https://github.com/QISKit/qiskit-tutorial/blob/master/INSTALL.md)**.

#### TL;DR:

To install locally:

1. Clone the [QISKit/qiskit-tutorial](https://github.com/QISKit/qiskit-tutorial):
```bash
git clone https://github.com/QISKit/qiskit-tutorial.git
```

2. If you use [Conda/Anaconda](https://conda.io/docs/index.html) I highly recommend you to create a virtual environment as follows (after clonning `qiskit-tutorial`):
```bash
cd qiskit-tutorial
conda env create -f QISKitenv.yml
```

If you're willing to run in the cloud using Azure Notebooks:

1. Create an account in [Azure Notebooks](https://notebooks.azure.com/), then create a new library from GitHub by pasting the link to this repo: `https://github.com/RodolfoFerro/IBMQC18`.
2. Now please see the [Azure Notebook instructions](https://github.com/RodolfoFerro/IBMQC18/blob/master/Azure_Notebooks_Installation.md) to install the [qiskit-tutorial](https://github.com/QISKit/qiskit-tutorial) requirements inside a Jupyter Notebook.

<center>
  <img src="https://image.flaticon.com/icons/svg/189/189810.svg" width="5%">
</center>
