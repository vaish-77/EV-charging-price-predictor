# EV-charging-price-predictor
Datasets :  
Weather Data - Dataset1  
   Conatins the weather conditions and solar radiations available at that instant.  
Radiation_pattern - Dataset2  
   Contains price corresponding to different amount of radiations per unit area based on inverse relation  
Grid_Price - Dataset3  
   Contains price corresponding to power consumed from grid based on direct relation and different per unit price for  different power unit ranges.  
Separate_Power - Dataset4  
   Divides user's demand into solar power and grid power based on available solar radiations.  


Models :  
Dataset_1 - Contains all the four models for dataset 1   
Dataset_2 - Contains all the four models for dataset 2   
Dataset_3 - Contains all the four models for dataset 3   
Dataset_4 - Contains all the four models for dataset 4  
Linear_Final - Contains the integrated model to find the final price using linear regression model on all four datasets.  
Best_Case - Contains the integrated model to find the final price using the best model in terms of least error for all four datasets.  


Before running the code, we should following libraries and softwares installed :
1) Jupyter Notebook
2) Pandas
3) Numpy
4) Matpolib
4) Sklearn
5) Tensorflow


Steps to run the codes: 
1) Download all the codes and datasets in the same folder.
2) The dataset should be in .csv format.
3)Launch Juptyer notebook in system.
4)Open the folder conatining the codes. 
5) Execute the codes one by one for each dataset and can compare them using the graphs and error obtained.
6) Run the last two models (from above sequence) to find the final price for EV charging based on demand and weather conditions as input.


--------------------------------------------------------------------------------------------------------------------------------------
 
