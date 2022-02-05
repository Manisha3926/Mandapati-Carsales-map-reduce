# map-reduce-Mandapati

# Data Details:
 This is the Car sales data set which include information about Manufacturer, Model,Sales_in_thousands,Vehicle_type,Price_in_thousands,Engine_size and more.

# Findings:
 By using the mapper and reducer I have sorted the car sales based on the maufacturer and its count. Once I have reduced the car sales excel sheet which has 145 rows into 15 rows I have inserted a pareto chart with the output generated.
 
 # Commands used:
 
 Once you clone the repo into your system, I have used the below commands to map reduce and pipe my dataset.
 
 To map I have used:
 
 ```cat Car_sales.csv | python mapper01.py > output-csv.txt```
 
 To reduce I have used:
 
 ```cat Car_sales.csv | python mapper01.py | sort | python reducer01.py > mandapati-output.txt```

# Chart:
<img width="366" alt="Capture" src="https://user-images.githubusercontent.com/77813935/152587611-a18d623b-6f60-4dec-bbd5-3fe14325ee55.PNG">




