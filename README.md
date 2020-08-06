# Trophic-Information-Extraction-Pipeline

**Description**

The uploaded files in concert work to create a trophic information pipeline run in a Jupyter notebook to create a result file that has the final classifications for scientific names found within research articles.

**Getting Started**

To run the pipeline, download all the data files into the same folder, and run the Jupyter notebook following the instructions inside the notebook. The Ollie tool must be downloaded from  http://knowitall.cs.washington.edu/ollie/ollie-app-latest.jar as well as the English MaltParser model (engmalt.linear-1.7.mco) http://www.maltparser.org/mco/english_parser/engmalt.html based on the instructions from https://github.com/knowitall/ollie. The two downloads should be in the same folder as the jupyter notebook file.  The scientific names file (zipped), the common names file, the abbreviated scientific names file (zipped), the english words file, the Random Forest training file and the trophic keywords file must be downloaded from this github repository and all kept in the same folder as the previous downloaded files mentioned. Unzip the two compressed files using the gunzip command. Once that is complete fill in the necessary names in the Part 1 cell which are the names of the files to be analyzed (PDFs), and the name of the result file. All other variables are left as the defaults based on the downloaded file names. If you change a file or a file name, the default must be changed. Then run all the cells in the notebook.
