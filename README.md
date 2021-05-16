# sentiment-analysis
Sentiment Analysis on Covid Vaccine


How to start contributing? 

1. Python -m pip install -r requirements.txt
2. Create a new file .env 
3. Enter the values with the keys mentioned below

    a. CONSUMER_KEY=

    b. CONSUMER_SECRET=

    c. BEARER_TOKEN=

    d. mongo=

    c. db=


4. Above values can be found at https://developer.twitter.com/en/portal/dashboard, you may have to apply for developer profile to fetch credentials 

5. To run with mongodb configuration, Run "python main_with_database.py"

### or

5. To run for without mongodb configuration, Run "python main.py"

6. Run jupyter notebook main.ipynb file for data visualization

### With CSV

Run "python main.py" which will generate csv files and store them in /data/csv folder 

Please note that "main.ipynb" file doesn't run the fetch_tweets() method to avoid downloading the same tweets again and again. That's why "main.python" script has fetch_tweets() method enabled. 

Once CSVs are downloaded, you can see all the reports in "main.ipynb" file.


