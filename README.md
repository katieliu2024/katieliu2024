## Midterm Project: Analysis of Building Value 
#### Course: INF 1340 Programming for Data Science
#### Instructor: Dr. Maher Elshakankiri
#### Name: Xiaojing Liu (1004263888)

#### Table of Content
- Requirements
- Program Explanation
- Guideline to run the program 
- Sample Input and Sample Output


#### Part 1 Requirement
Users can access the colabortory or install Python.3x on the computer. 


#### Part 2 Program Explanation
The program is to create a Python file to do the numerical analysis of the data. I selected the building.txt as the input file. The input file has 7 columns and 15 rows. The columns include the legal_type, current_land_value, current_improvement_value, previous_land_value, previous_improvement_value. I created 9 different tasks to analyze the building data including its analysis of current value, analysis of improvement rate, analysis of growth rate, and analysis of legal types. After analyzing the data, the result will be saved in the output file. Also, the results will be displayed in the Python program. Users can set the input file name and output file name to do the numerical analysis. 


#### Part 3  Guideline to run the program 
1. Set the working directory and have an input file on your system
2. Enter the input file when the program prompted
3. Enter the output file when the program prompted
4. Run the program by clicking the top right button 'run'.
5. Review the analysis result of the Python program
6. Review the output file that has been created


#### Part 4 Sample Input and Sample Output
*****Sample Input (Building.txt)*****: 
```
Legal_type, CurrentValue, CurrentValue_Improve, PreviousValue_land, PreviousValue_improve
land, 7200000, 43600, 5760000, 42300
land, 3779000, 989000, 3569000, 787000
Strata, 196000, 154000, 178000, 149000
```

****Sample Output*****: 
```
Enter input file name: building.txt
Enter output file name: Output.txt
Average Current Value: 1434714.29
Maximum Current Value: 7200000
Minimum Current Value: 182000
The number of legal types: 2
Average Current Value by Type:
land: 3045666.67
Strata: 226500.00
Legal Type Frequency:
land: 6
Strata: 8
The maximum growth rate: 34.97 %
The maximum growth rate: 151.09 %
The proportion of building that has a negative growth rate: 14.29 %
```




















