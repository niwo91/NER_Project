# Named Entity Recognition Project

**Nicholas Woody - CSPB3832 Spring 2026**

---

### Background
This repository holds the code for my Named Entity Recognition project for CSPB3832 for Spring 2026. The code and comments are contained in the attached Jupyter Notebook.

### Running the code

#### Suggested Method
The code itself runs succesfully in [Google's Colab servers](https://colab.research.google.com/). As noted in the notebook, you may need to configure your notebook with a user access token from huggingface. If needed, a link to huggingface's instructions can be found in the notebook.

#### Running the code in a virtual environment
If you choose to run this notebook on a virtual environment follow these instructions in a bash (or bash compatible) terminal. Be sure to have python3 installed on your machine and move the requirements.txt and NLP_Project.ipynb files in this repository to your virtual environment.

```bash
# Setup the virtual environment
python3 -m venv venv
# Activate venv
cd venv
. bin/activate
# Install requirements, be sure to move requirements.txt to this virtual environment folder prior to doing this
python3 -m pip install -r requirements.txt
# Create a Notebook kernel
ipython kernel install --user --name=venv
# run the notebook, be sure to move NLP_Project.ipynb to this virtual environment folder prior to doing this
jupyter notebook NLP_Project.ipynb
```

Once the notebook starts, go the "kernel" menu and choose "change kernel". Select the "venv" kernel you just created to run this notebook in the virtual environment.

#### Running the code locally without a virtual environment
If you choose to run the code locally, please install all the python modules listed in "requirements.txt". You should also have python3 and Jupyuter Notebook downloaded on your local environment.

##### A Note on pytorch
If you have an issue with pytorch, installation instructions can be found [here](https://pytorch.org/get-started/locally/). 
