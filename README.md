
# Multi-Camera Cross Mapping and Annotation

This project performs multi-camera object tracking on football match footage. The primary goal is to detect players, track them within each video feed, and then create a consistent mapping of player IDs between two different camera views using homography.

![hippo](https://drive.google.com/file/d/1mHkfg7uMtfYaxyP3l5c6Or1MGDqXeMvk/view?usp=sharing)
-----

## Project Structure

This repository contains two  Jupyter notebooks:

1.  `INTERACITVE`

      * A detailed, step-by-step notebook that walks through each stage of the pipeline: detection, tracking, and homography calculation.
      * **Best for**: Understanding the methodology and visualizing intermediate steps.

2.  `OOPS`
      * A clean and scalable implementation using Object-Oriented Programming (OOP) principles. The entire pipeline is encapsulated in classes and methods.
      * **Best for**: Quickly generating the final results. This notebook only has two cells to run\!

-----

## Setup

Follow these steps to set up your local environment. Python 3.9 is preferred.

**1. Create and Activate a Virtual Environment**

Create a virtual environment to manage project dependencies.

```bash
# Create the virtual environment
python3 -m venv venv
```

Activate the environment.

```bash
# For Linux / macOS
source venv/bin/activate

# For Windows (Command Prompt)
.\venv\Scripts\activate
```

**2. Configure Jupyter Kernel**

If you're using VS Code or Jupyter Lab, make sure to select the kernel from your virtual environment (`venv`) after installing ipykernel. 

```bash
pip install ipykernel
```

**3. Download the Model**

  * **Automatic:** Simply run the notebook, and it will automatically download the required model to the directory from the link provided in the code.
  * **Manual:** Download the model and place it in the folder.

-----

## Run

  For the most straightforward experience, open and run the OOPS notebook.
  Execute the two cells.
  All processed outputs, including the final annotated videos, will be automatically saved in the **`results/`** folder.

-----
