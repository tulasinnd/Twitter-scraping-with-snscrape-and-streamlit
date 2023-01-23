# Twitter-scraping-with-snscrape-and-streamlit
Interative GUI using streamlit for twitter scraping 

REQUIRED SKILLS:
1.	Python scripting
2.	MongoDB
3.	Streamlit
4.	Snscrape

OVER VIEW:

I have Created a GUI using streamlit that contains the follwing  features
1. Can enter any keyword or Hashtag to be searched, 
2. select the starting date 
3. select the ending date  
4. Number of tweets needs to be scrapped.
After scraping is done, it has the following options
1.	Download data as CSV
2.	Download data as JSON
3.	Upload data to DATABASE
4.	Display All the Tweets scraped
5.	All the Uploaded Collections in Database are Displayed in the left side

WORKING:
Step1:
Initially I collected the Keyword, Start date, End date, and Number of tweets from the user using streamlit

Step 2:
The above details are fed to TwitterSearchScraper and TwitterHashtagScraper.
A dataframe is created to store the entire scraped data
Now we can download this scraped data in the form of CSV or JSON format 

Step3:
The database connection is established using pymongo
A new collection will be created and data is uploaded into that collection  if the user wish to upload 

Step4:
A separate sidebar is created to display all the collections that are uploaded to the database, On clicking any collection, we can see the documents in that collection

TWITTER SCRAPER STREAMLIT APP WORKING DEMO VIDEO:
https://www.linkedin.com/posts/tulasi-n-49b6111b0_snscrape-python-streamlit-activity-7023389364365783040-1DUv?utm_source=share&utm_medium=member_desktop

Screenshots:
![image](https://user-images.githubusercontent.com/116662776/214135502-ee88fb03-f683-44d2-8e08-010ac4bd6866.png)
![image](https://user-images.githubusercontent.com/116662776/214135783-3464a7f5-3faa-4c2d-837a-30c4db3c754c.png)


