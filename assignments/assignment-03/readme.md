# Python for Policy
# Assignment 3

Due next Monday night by 23:59pm via Canvas submission.

In this assignment, you will need to follow the instructions in this Jupyter notebook to work with a data set from ACS containing population data for all US counties.

1. Create a new, clean Jupyter notebook to contain your submission. The first cell in your notebook should be a markdown cell containing a plain-English narrative of the a) logic you will need to code and b) how your development process corresponds to *Think Python* sections 4.8 and 6.2. Use this narrative to think through how you will tackle each piece of the assignment in straightforward language.
2. Download the acs_data_county_US.csv from Canvas, and save it to your working directory.
3. Using the acs_data_county_US.csv file and the pandas techniques we've learned, do the following:
   1. Load the data file, inspect and clean the data: replace all missing value with 0, and make all population variables float types
   2. Divide the "geodisplaylabel" column into two seperate column named "countyname" and "statename". The "countyname" column should contain only county name (e.g. Autauga County), and the "statename" column should contain only state name (e.g. Alabama)
   3. Create new columns and calculate the percentage of white, black, nativeindian, asian and hispanic population for each county (with intuitive field names of your choice).
   4. Create a subset dataframe with counties containing population between 500,000 and 1 million, and answer the question: How many counties are within the state of Massachusetts?

You must complete the above tasks only using Python in the notebook, don't introduce other outside programs.  Make sure your entire notebook runs properly and without any errors. Click Kernel > Restart > Clear all outputs and restart. This clears your memory and re-initializes your notebook. Then click Cell > Run all and make sure everything behaves properly. Give it meaningful filenames like `your-lastname-assignment3.ipynb`.
