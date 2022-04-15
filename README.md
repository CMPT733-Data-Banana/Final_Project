# Final_Project

Dish Out web tool link: https://dishout.000webhostapp.com/

Competitor Analysis

To run these files, ensure that you change path according to input files location in your system. 

/Data Extraction
This includes the steps to extract data from from yelp api 
This is extraction for 50 records 



/Data Cleaning
This includes the steps to clean the extracted data 



/Input 
This contains all the input files


/PopCityWise
This creates maps for all popular restaurants city wise


/restuarantslocationwise_analyis
This includes analysis done on locations of business listings


/restwise_comp_analysis
This includes analysis on all competitors that serve same cuisine as that of host business listing


/restwise_radius_map
This includes analysis on all competitors of host restaurant with radius constraints. ( 5KM, 3KM, 2KM, 1KM)

Instruction for UI folder:

Webpages:

1. index.html: The main homepage for the Dish Out tool.

2. new.html: For Aspiring Restaurant owners, consists of Popular Restaurants page, Competition Aorund page and Reviews Analysis (click Aspiring Restaurateurs owners for this page)

 3.existing.html: For Existing Restaurant owners, consists of Success Potential page and Attribute Analysis page (click Existing Restaurateurs owners for this page)

4. reviews.html: Reviews Analysis page, accesible through Existing Restaurateurs page. (click on Reviews Analysis)

5. attributes.html: Attributes Analysis page, accesible through Aspiring Restaurateurs page. (click on Attribute Analysis)

6. competition.html: Competitor Around page, accesible through Existing Restaurateurs page. (click on Competition Aorund)

7. base.html: is the base for Competitor Analysis page

Folder:

1. The /assets folder contains the css, javascript, sass and webfonts for the web tool

2. The /competitior folder contains the maps for restaurants around who can be a competition

3. The /popularrestaurants folder contains the maps showing the popular restaurants in different cities.

4. The /pictures folder contains the images of Review Analysis

5. The /images folder contains the webimages such as background

Success Prediction Folder:

1.First Run EDA Business 
  - Input: bc_rest_open.csv, cat_list.csv 
  - Output: business_list.csv

2.Model Selection
  - Input:business_list.csv, attributes.csv
  - Output:business_df_merged.csv, rf_model.sav

3.Test Prediction
  - Input:business_df_merged.csv
  - Ouput: rf_df.csv
  

 rf_df.csv is then visualized using Tableau

Attritube Analysis:
  -Input:Business.csv(From Google Drive)
  -Output:attributes.csv

Reviews Analysis

1.The /Data Contains the folders(or links to files) required to run the program
2.The /Data_Preprocessing Contains the scrripts to convert the files in a useable manner
3.The /Monthly_Sentiment_Analysis contains scripts to return the monthly sentiment across time for different types of restaurants
4.The /Lexicon_sentiment Contains the positive and negative txt files for sentiment
5.The /EDA files consist of the initial EDA files and visualizations
6.The /Polarity files consist the script to run polarity 
7.The /WordCloud consist of scripts to develop wordcloud files
8.The /Visualizations folder consists of all the visualizations created


