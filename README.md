# Data analysis for stroke liklihood

This project will focus on an analysis of a data-set showing patient health data, and if the patient has suffered a stroke.  The analysis will perform initial data cleanup and validation, linear approaches, KNN approaches, and finally a random forest analysis and SVN.


## Installation

	- Download and Install Anaconda:
	- Go to Anaconda’s official website.
	- Download the appropriate version for your operating system.
	- Run the installer and follow the on-screen instructions.
	- Verify Installation:
	- Open your terminal or command prompt.
	- Run the command:
```
conda --version
```
If the version number is displayed, Anaconda is installed correctly.

Launching Jupyter Notebook

	1.	Activate the Anaconda Environment (Optional):
	•	If you want to use a specific environment, activate it by running:

conda activate <environment_name>


	2.	Start Jupyter Notebook:
	•	Open your terminal or Anaconda Prompt.
	•	Run:

jupyter notebook


	•	This will open Jupyter Notebook in your default web browser.

	3.	Accessing Notebooks:
	•	The interface displays the directory structure of your system.
	•	Navigate to the folder where you want to create or access a notebook.

Creating and Managing Notebooks

	1.	Creating a New Notebook:
	•	In the Jupyter Notebook interface, click the New button in the top-right corner.
	•	Select the desired kernel (e.g., Python 3).
	2.	Editing a Notebook:
	•	Each notebook consists of cells that can hold code, text (Markdown), or raw content.
	•	Use the toolbar to:
	•	Run cells (Shift + Enter)
	•	Add cells (Insert menu or toolbar button)
	•	Change cell type (Code/Markdown)
	3.	Saving and Exporting:
	•	Save your work using the Save button or by pressing Ctrl + S.
	•	Export notebooks as .html or .pdf through File > Download as.

Installing Additional Libraries

	1.	Using Conda:
	•	Install libraries using Conda with:

conda install <library_name>


	2.	Using Pip:
	•	For libraries not available in Conda, use Pip:

pip install <library_name>


	3.	Ensuring Compatibility:
	•	Always install libraries within the active environment to avoid conflicts.

Troubleshooting

	1.	Jupyter Notebook Not Launching:
	•	Ensure Jupyter is installed in your environment:

conda install jupyter


	•	Try launching Jupyter Notebook from the Anaconda Navigator.

	2.	Kernel Issues:
	•	If a notebook kernel doesn’t start, check the environment by running:

conda activate <environment_name>
python -m ipykernel install --user


	3.	Library Import Errors:
	•	Verify the library is installed in the correct environment:

conda list | grep <library_name>

Resources

	•	Jupyter Documentation
	•	Anaconda Documentation

This guide is intended to help you effectively set up and use Jupyter Notebook with Anaconda for your data science or development workflows.