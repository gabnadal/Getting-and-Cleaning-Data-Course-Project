# getting_cleaning_data_project
This repo holds the run_analysis.R, codebook and README for the final project related to the getting and cleaning data Coursera course

The run_analysis script is a self contained file that can be opened with R studio and run from your current working directory.
Although the instructions say the file should be run from the Samsung tab directory, this file makes no assumptions about the current working directory or the contents on your computer.

In order use the file you will need a program like R or R studio, download the file to your computer and then open it in R or R studio. Once you open the file, run the file and it will retrieve the necessary zip file from the UCI archive.
After it has downloaded the file it will unzip the contents and create the UCI HAR sub folder along with the sub folders containing the data from the mobile device tracking each participants activities. The result of running the code will be a tidyData table in your R workspace.

The run_analysis.R file is liberally commented with a summary of what the subsequent lines of code do. 
To summarize here is how the run_analysis.R file works.

1. Download it to your computer
2. Open it in a working version of R or R studio
3. Run the entire code
4. The code produces a tidyData table in your R workspace environment
(A commented line at the very bottom exports the tidyData table to a file called rtbrown77_tidyData.txt in your current workspace)

