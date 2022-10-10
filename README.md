# This is the official repository for AML 2022/23 class at Sapienza University of Rome

The notebook provides an introduction to Transformer Network (TF).

The aim of this homework is to guide students through an implementation of the architecture studied in class. 

It is also interesting to see the versatility of the Transformer on a practical Computer Vision case as an alternative to the original NLP field.



## Deadline and Submission

The deadline for the homework is at 23:59 of 17/11/22  (GMT+2)

The students can organize and submit the work in group of ??-?? people.

Before the deadline you can submit the code at: ???

> :warning: Note: for each day of delay a penalization of 2 points on the grade will be applied


## Files structure

- `TF4AML_theory.ipynb` notebook contains exercises to guide the students through the implementation of TF fundamental blocks;

- `TF4AML_practice.ipynb` notebook contains exercises for a Computer Vision research application. See paper (Under the Hood of Transformer Networks for Trajectory Forecasting)[https://arxiv.org/abs/2203.11878];

- `dataset` folder has all the ETH/UCY data used as trajectory forecasting benchmark;

- `transformer` folder includes all the necessary file to build TF and experiment with the benchmark. 
The code is inspired by the original Hugging code of 2018.



## How to run

### Select hardware

We recommend to use GPU acceleration.

Then [Google colab](https://colab.research.google.com) is a good solution to use free one or alternatively use your own hardware.

In this case we suppose you already have Anaconda installed for the environment.


a. Run from `Google Colab`:

  1. Open a new [colab notebook](https://colab.research.google.com) (this will be needed only for the setup and then can be removed).
  
  2. Clone the repo running command in the first cell:
  > `!git clone https://github.com/FraLuca/TF4AML.git`
  
  3. Synchronize with google drive to save all the changes and model checkpoints/outputs (copy those 2 lines in the second cell):
  > `from google.colab import drive`
  > 
  > `drive.mount('/content/drive', force_remount=True)`
  
  4. Move folder to main drive folder (copy this line in the third cell):
  > `!mv /content/TF4AML /content/drive/MyDrive/` 
  
  5. Open [Google Drive](https://drive.google.com/drive/u/0/my-drive). 
  
  6. Now you should find the folder TF4AML in the drive and start opening the theory notebook with colab.
  
  7. After you open the notebook, activate the GPU (Runtime > Change runtime type > GPU > Save) and start following instructions!
  
  8. Once you are done with the theory part do the same with practice notebook.



b. Run from `Local`:

  1. Open terminal and run: 
  > `git clone https://github.com/FraLuca/TF4AML.git`
  
  2. Install the environment with 
  > `conda env create -f environment.yml`
  
  3. Open new terminal and activate new environment with:
  > `conda activate aml`
  
  4. From the same terminal (and environment) run jupyter notebook with:
  > `jupyter notebook`

  5. Start opening the theory notebook and complete it following the instruction.
  
  6. Once you are done with the theory part do the same with practice notebook.
