# Sentiment Analysis on Amazon Product Reviews
## 📌 Project Overview
This project performs sentiment analysis on Amazon product reviews using Natural Language Processing (NLP) and Machine Learning techniques. By scraping customer reviews, the system classifies them as positive, negative, or neutral, providing insights for consumers and sellers.

## 🔍 Key Features
Web Scraping: Extracts Amazon product reviews using ScraperAPI and BeautifulSoup.
Sentiment Analysis: Uses VADER SentimentIntensityAnalyzer to classify reviews.
Automation & Processing: Handles multiple pages of reviews efficiently.
Statistical Summary: Provides the percentage of positive, negative, and neutral reviews.
## 🛠️ Technologies Used
Python
BeautifulSoup (HTML parsing)
VADER Sentiment Analysis
Requests (for HTTP requests)
ScraperAPI (for web scraping)
## 🚀 How It Works
User inputs the Amazon product review page URL and the number of pages to scrape.
The script extracts review texts using BeautifulSoup.
VADER Sentiment Analyzer evaluates the sentiment score for each review.
Final output includes:
Sentiment classification (Positive, Negative, Neutral)
Total number of reviews
Percentage of each sentiment type
## 📌 Results & Applications
![Screenshot 2025-03-02 193538](https://github.com/user-attachments/assets/0881edcc-c25c-40ff-8209-32ea9c435f48)

 Sample Output

Review 1

Review: The Xiaomi Redmi Note 11T 5G impresses with its stellar performance and 5G capabilities at an affordable price point. The vibrant and large display makes for immersive viewing, whether for multimedia or gaming. The device's battery life is commendable, easily lasting through a day of heavy usage. Its camera system captures decent photos in various conditions, although low-light performance could be better. The inclusion of 5G connectivity future-proofs the device for faster data speeds. While the plastic build may feel less premium, it aids in keeping the device lightweight. Overall, the Redmi Note 11T 5G offers great value for its features, making it an excellent choice for budget-conscious users seeking a blend of performance and connectivity.

Sentiment Analysis:

Negative: 0.00%

Neutral: 83.50%

Positive: 16.50%

Overall Sentiment: Positive

Review 2

Review: Phone is good but functions are not. Fingerprint is not there. Voice is not good.

Sentiment Analysis:

Negative: 14.80%

Neutral: 76.00%

Positive: 9.30%

Overall Sentiment: Negative

Review 3

Review: The Redmi Note 11T is an absolute gem of a smartphone, and it deserves every one of its five stars. Here's why:

Impressive Performance: Handles multitasking, gaming, and resource-intensive apps smoothly.

Vibrant Display: Sharp Full HD+ resolution for an immersive experience.

Outstanding Camera: Great quality, even in low-light conditions.

Long Battery Life: Lasts a full day, with fast charging.

5G Connectivity: Future-proofed for next-gen mobile networks.

Affordable Price: Flagship-level features at a mid-range price.

Solid Build Quality: Sturdy and modern design.

Sentiment Analysis:

Negative: 0.60%

Neutral: 79.80%

Positive: 19.60%

Overall Sentiment: Positive

Additional Reviews

"Call recording is difficult and photos by camera are not clear." (Negative Sentiment: 34.20%)

"Just OK." (Neutral Sentiment: 100.00%)

"Best mobiles are available at a cheaper price for these features." (Positive Sentiment: 28.50%)

"Good product." (Positive Sentiment: 74.40%)

Features

Extracts and processes Amazon product reviews.

Performs sentiment analysis on each review.

Classifies reviews as Positive, Neutral, or Negative.

Provides percentage breakdown for each sentiment category.

How It Works

Enter the Amazon product review URL.

Specify the number of pages to scrape.

The script extracts and analyzes the reviews.

Outputs sentiment scores for each review.

Requirements

Python

BeautifulSoup

VaderSentiment

Requests

Number of reviews: 20 
Number of Positive Reviews: 12 
Number of Negative Reviews: 4 
Number of Neutral Reviews: 4 
Average Rated As Positive 
Most buyers like this product. 

![image](https://github.com/user-attachments/assets/dd39391d-edf1-4043-b46b-92516a33565c)

A License

This project is licensed under the MIT License.
