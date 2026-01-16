# SENTIMENT-ANALYSIS

"COMPANY": CODTECH IT SOLUTIONS

"NAME": Ramisetty Meghana

"INTERN ID": CTIS0393

"DOMAIN": DATA ANALYTICS

"DURATION": 8 WEEKS

"MENTOR": NEELA SANTHOSH

"DESCRIPTION":

The Sentiment Analysis task was successfully completed using Microsoft Excel with the help of Google and online video tutorials. The main objective of this task was to analyze textual data such as reviews or tweets and determine the sentiment behind them, whether positive, negative, or neutral. Although sentiment analysis is usually performed using programming languages like Python and advanced NLP libraries, Excel can also be used effectively for basic sentiment analysis by applying logical rules, text functions, and predefined sentiment dictionaries.

First, the textual dataset was collected from online sources using Google. The dataset contained customer reviews and opinions expressed in text form. It was downloaded in CSV or Excel format and imported into Microsoft Excel. Google and video tutorials were very helpful in understanding how sentiment analysis can be implemented in Excel using formulas and structured approaches. After importing the dataset, the structure of the data was studied to identify important columns such as review text, date, user information, and ratings if available.

The first step in sentiment analysis was data preprocessing. Preprocessing is important because raw textual data usually contains unnecessary elements that affect accuracy. In Excel, preprocessing involved converting all text into lowercase to maintain uniformity, removing extra spaces, and eliminating punctuation marks or special characters. Functions like LOWER(), TRIM(), SUBSTITUTE(), and CLEAN() were used for this purpose. Any blank or irrelevant rows were removed to ensure data quality. This step made the text cleaner and more suitable for analysis.

After preprocessing, a sentiment dictionary was created. A sentiment dictionary is a list of words labeled as positive or negative. For example, words like “good,” “excellent,” “happy,” and “amazing” were categorized as positive, while words like “bad,” “poor,” “disappointed,” and “worst” were labeled as negative. This dictionary was prepared using guidance from Google and tutorials. It was stored in a separate Excel sheet and used as a reference for matching words from the reviews.

The next step was tokenization and sentiment scoring. Tokenization means breaking each review into individual words. In Excel, this was done using formulas and helper columns. Each review was checked against the sentiment dictionary to count how many positive and negative words it contained. Functions like COUNTIF() and SEARCH() were used to identify matches. For each review, a sentiment score was calculated by subtracting the number of negative words from the number of positive words.

Based on the sentiment score, the final sentiment label was assigned. If the score was greater than zero, the sentiment was classified as Positive. If the score was less than zero, it was classified as Negative. If the score was zero, it was considered Neutral. This classification was done using the IF() function. This step represented the model implementation part of the task, where a simple rule-based NLP model was applied.

Once the sentiments were classified, insights were generated from the data. The total number of positive, negative, and neutral reviews was calculated using COUNTIF() functions. These results helped in understanding overall public opinion. For example, a higher number of positive reviews indicated customer satisfaction, while a large number of negative reviews highlighted areas needing improvement. Charts such as pie charts and bar charts were created to visualize sentiment distribution clearly.

Visualization played an important role in making the results understandable. A pie chart was used to show the percentage of positive, negative, and neutral sentiments, and a bar chart was used to compare sentiment counts. These visuals made the analysis more meaningful and easy to interpret.

In conclusion, the Sentiment Analysis task was successfully completed using Excel with guidance from Google and video tutorials. The project demonstrated all essential steps: data preprocessing, model implementation using a rule-based approach, and insight generation. Even though Excel is not a traditional NLP tool, it proved effective for understanding sentiment analysis concepts and fulfilling the internship requirements in a practical and systematic way.

"OUT PUT OF TASK":

<img width="739" height="715" alt="Image" src="https://github.com/user-attachments/assets/7ddbb300-bce3-482c-b222-1ce9d5b4f6cd" />
