# Intro
Introduction to Python and Jupyter Notebook for PHYS3112.

# Installing the software we need using miniconda

These instructions are for a Windows computer. We are using miniconda rather than the full Anaconda distribution, since we can just download the software we need.

```
Go to https://www.anaconda.com/download

Click on "Skip registration"
Go down the page until you see "Miniconda Installers"
Select the 64-bit Graphical Installer.
Open the downloaded file, Next --> I agree --> Just me --> Next --> Install --> Next --> Finish
Use the Windows search box to open the app "Anaconda Prompt"
Type the following commands, not including the text after the hash on a line
conda create -n phys3112 python matplotlib numpy scipy pandas jupyter # this creates a "phys3112" environment for the software
y # a few hundred MB of software will now be downloaded
conda activate phys3112  # you need to do this every time you install new software
conda install conda-forge::vc14_runtime
pip install vpython # a 3D animation package
pip install ipympl # interactive plotting package; stands for "IPython matplotlib"

You should now be able to run the app "Jupyter Notebook (phys3112)" with all the software we use in the course.
```

# Quick instructions for downloading ipynb files to a lab computer

 * Login to a lab computer with your zid and zpass.
 * Relax for a minute or so while the computer starts up.
 * Start Anaconda Navigator (click on windows icon, type "Ana", select Anaconda Navigator).
 * From Anaconda Navigator, start Jupyter Notebook.
 * In your Windows browser, login to http://github.com/phys3112, navigate to the repository you want within the phys3112 project, click on Download, save as ZIP, open the ZIP file with a browser, extract the ipynb file you want, copy the file to the Windows Downloads folder.
 * From within Jupyter Notebook, upload, select the file from the Downloads folder, upload.
 * Click on the file to run it.
