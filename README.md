# FastCloneAssist_02
Fast cloning primer designing tool FastCloneAssist script and files.

What is Fast Cloning: Please see this paper: Li, C., Wen, A., Shen, B. et al. FastCloning: a highly simplified, purification-free, sequence- and ligation-independent PCR cloning method. BMC Biotechnol 11, 92 (2011). https://doi.org/10.1186/1472-6750-11-92

How to use FastCloneAssist to design primer for your Fast cloning Experiments.

To run in a python environment installed locally: 

To utilize the FastcloneAssist script, download it from the GitHub repository (GitHub link) and execute it using Python. The code is structured into three parts. Begin by running the 1st part to install the required libraries (Biopython & primer3). It is important to note that the 1st part only needs to be executed once for a system, as it installs the necessary libraries. Once this step is completed, proceed to run the 2nd part. The part 2 will import all required modules from the installed libraries. Note the tkinter, sys, and os modules will be imported from the default Python installation. 
Running the 3rd part (primer design part) the script will prompt you to enter 1 or 2 to choose either Class 1 or Class 2 style of primer designing (see above). Following your selection, the next required input will be the sequence. Ensure your sequence is pre-prepared with symbols as described for the specific class and need. The next prompts will ask you, if you want to choose any specific Tm or use the default range (55-65°C)? You may enter “no”, but if your input is yes, it will prompt you to enter your Tm range, such as 60-64. After this input, the script will generate a report as a text file. Please minimize your open windows to see the popup asking you to save the file.


To run on cloud using google Colab:

The script is compatible with Google Colab as well. No Python installation is required in your system. To use it in Google Colab, create a Colab account using Google acount. Download the Colab version of the script from the GitHub link (GitHub link) and save it in your Google Drive. In Colab, import the script from your Google Drive and run it. You can right click on file “FastCloneAssist_Colab” file in your google drive and choose run with Google Colaboratory. Note, in colab you need to run the 1st part each time you start a new session, as Google Cloud does not store the installed library once the session ends. The primer will be saved as a text file in your download folder.


Additionl detail for Google Colab: 
Advantage:
1-	Easy to use.
2-	No python environment required
3-	Report easily saved in download
4-	All installation will take place in cloud.




