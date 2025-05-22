This is the second component of the Ground Cover Change model, where you will find all the associated codes and tools.

Input
This step relies on metrics estimated to filter training data samples in the eco-zone of interest. The samples are collected using a standardized procedure and compiled in the “input_dataset.csv” file found here: https://data.mendeley.com/datasets/mzp3k6fmtz/5.

Output
Filter.py is written with a PYthon language command editor. Download and save the .py file and the .csv file  in a newly created local folder. Then, run the program to classify data into levels of reliability with stratified agricultural seasons.

These files will appear in your local folder:
1- Optimized Dataset: Integrated mean and 99th-percentile ICESat-2 canopy height measures for sample vetting.
2- Discrete land cover files: Classified samples arranged by land cover class. 
3- Output Dataset: Classified training data set.

The classified training data set is used to filter unwanted samples (Level 0 and Level 1 - with no agreements). Make sure to update the output file for GCC model input.
