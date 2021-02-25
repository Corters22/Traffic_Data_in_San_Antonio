![Pic of minor accident](https://github.com/Corters22/Traffic_Data_in_Texas_Project1/blob/main/fender-bender-costarica.jpg)

# What is the best environment in San Antonio to reduce the chances of getting in an accident?

1) Where in San Antonio is the lowest and highest amount of accidents? 
2) What is the best weather condition to drive in San Antonio? 
3) What time of day do more accidents occur in San Antonio?

### Dataset
You can find the original data file through Kaggle.com. Here is the link to the exact dataset. [US Accidents (4.2 million records)] (https://www.kaggle.com/sobhanmoosavi/us-accidents). In order to use Kaggle, you do need to create a free account. Due to the size of the original dataset, we were unable to load it to the repository so if you choose to run the notebook code to 'clean' and narrow down the dataset (cleaning_csv.ipynb), you will first need to download it from Kaggle.

### Table of Contents
**I. Presentation**  
**A. Texas Traffic Accident Patterns in 2018.pptx** - PowerPoint presentation for data analysis.  

**II. Question_1 - Where in San Antonio?**  
**A. Images**  
    1. acc_large_bar.png - Bar Chart showing number of accidents in zip codes with larger populations
    2. acc_medium_bar.png - Bar Chart showing number of accidents in zip codes with medium sized populations.
    3. acc_per_zip_bar.png - Bar Chart showing number of accidents in all zip codes.
    4. acc_side_bar.png - Bar Chart showing number of accidents in different sides of town.
    5. acc_small_bar.png - Bar Chart showing number of accidents in zip codes with smaller populations.
    6. acc_zipsize_bar.png - Bar Chart showing number of total accidents in each size of zip codes.  
**B. sa_zipcode_analysis.ipynb**  
    1.Jupyter notebook with Python code to analyze data based on location. Charts above come from this notebook. It starts with the cleaned csv extrapolated from the orginal dataset. (**hint** You will need a GoogleMaps API and Census API)  

**III. Question_2 - Weather Condition in San Antonio**  
**A. Images**  
    1. accident_per_precip_bar.png - Bar Chart showing number of accidents in different precipitation levels.
    2. accident_per_temp_bar.png - Bar Chart showing number of accidents in different temperatures.
    3. accident_per_visibility_line.png - Line Chart showing number of accidents in different visibility distances.
    4. accident_per_weather_bar.png - Bar Chart showing number of accidents in each type of weather condition.   
**B. SA_weather_conditions.ipnyb**
    1. Jupyter notebook with Python code to analyze data based on weather. Charts above come from this notebook. It starts with the cleaned csv extrapolated from the orginal dataset.   

**IV. Question_3 - Date, time of accidents in San Antonio**  
**A. Images**  
    1. month.png - Bar Chart showing total number of accidents in each month.  
    2. number of accidents.png - Bar Chart showing total number of accidents based on the week of the month.
    3. times of day.png - Bar Chart showing total number of accidents based on time of day.  
**B. SA_time_traffic.ipynb**
    1. Jupyter notebook with Python code to analyze data based on date and time. Charts above come from this notebook. It starts with the cleaned csv extrapolated from the orginal dataset.   

**V. Data Clean up**  
**A. cleaning_csv.ipynb**  
    1. Jupyter notebook with Python code to extrapolate accidents that occurred in Texas in 2018.  
**B. cleaned_2018_texas_accidents.csv**  
    1. CSV file with cleaned data - all other notebooks are run from this CSV

### Conclusion

## To reduce your chances of getting in an accident in San Antonio, you should drive in the Southeast side of town, specifically in zip code 78203, between 6 pm and 12 am in week four in August, while it is clear or partly cloudy.

### Further Analysis
####    Feel free to further the research by testing the correlation between location and weather, location and time, or weather and time. You'll find a more precise answer to our question. 

### Sources

Per the original dataset, we are to give credit to the following papers: 1) Moosavi, Sobhan, Mohammad Hossein Samavatian, Srinivasan Parthasarathy, and Rajiv Ramnath. “A Countrywide Traffic Accident Dataset.”, arXiv preprint arXiv:1906.05409 (2019).2) Moosavi, Sobhan, Mohammad Hossein Samavatian, Srinivasan Parthasarathy, Radu Teodorescu, and Rajiv Ramnath. “Accident Risk Prediction based on Heterogeneous Sparse Data: New Dataset and Insights.” In proceedings of the 27th ACM SIGSPATIAL International Conference on Advances in Geographic Information Systems, ACM, 2019.
