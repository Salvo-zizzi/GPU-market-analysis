# GPU Market Analysis: Stock, Price, and Shortage (March 25 - April 7)

This analysis examines GPU stock availability, pricing trends, and shortage conditions between March 25th and April 7th. Data was scraped from Twitter, and sentiment analysis was performed using VADER. Additionally, TF-IDF was employed to identify the most frequent terms.

**Note:** Sentiment analysis was performed using VADER, and a custom "Tweet profiler" was used to provide a more detailed analysis of the sentiment of the tweets. The "Tweet profiler" is a custom tool that allows a more granular look at the sentiment of the tweets, allowing to see the different types of emotions, like joy, sadness, etc. The "compound" value given by VADER, is a single value that represents the overall sentiment of the text.

## GPU Stock

### Sentiment Analysis with VADER's Compound

![Compound-Sentiment-Vader](https://user-images.githubusercontent.com/58707590/166121312-fa002341-ab00-4566-8b54-6870bb141a5b.jpg)

The compound sentiment is generally positive, reflecting the increased availability of GPUs in recent weeks after a period of scarcity.

### Tweet Profiler

![Profiler-Boxplot](https://user-images.githubusercontent.com/58707590/166121505-450ae39e-3e99-423b-8f38-b201516854fe.jpg)

The tweet profiler provides a more nuanced view than the VADER compound. The dominant sentiment is joy, aligning with the improved stock availability.

### Time Series

![Sentiment_linechart-time](https://user-images.githubusercontent.com/58707590/166121570-9e81988d-1a0c-4936-854f-ed0fe380fab8.jpg)

The time series reveals a sentiment dip around the Intel graphics card launch, followed by a significant increase. This suggests initial skepticism, turning to excitement upon seeing the desktop GPU preview.

### TF-IDF

![TF-IDF](https://user-images.githubusercontent.com/58707590/166121603-8fb3bdb8-3673-4e2f-a3c9-fc9aea4d444a.jpg)

The most frequent terms are "geforce" and "amazon," indicating the prevalence of Nvidia GPUs and Amazon as a common purchase platform, perceived as safer than other sources prone to scalping.

## GPU Price

### Sentiment Analysis with VADER's Compound

![Sentiment](https://user-images.githubusercontent.com/58707590/166121724-4392224a-b52a-4792-b8ef-ea3b1370af3f.png)

The compound sentiment is predominantly positive, reflecting the price decrease observed during this period.

### Tweet Profiler

![Profiler](https://user-images.githubusercontent.com/58707590/166121770-7ad031d1-e7bf-4f24-85d7-d1bcffc52020.png)

Positive sentiment outweighs negative, indicating general satisfaction with lower prices.

### Time Series

![Time-series](https://user-images.githubusercontent.com/58707590/166121806-9e549c4b-664b-460c-a997-eb8450ddc155.png)

The compound sentiment fluctuates, reflecting mixed reactions to price variations. While some are pleased with lower prices, others express dissatisfaction with prices still inflated compared to launch prices.

### TF-IDF

![price-tf-idf_price](https://user-images.githubusercontent.com/58707590/166122060-45126651-30e8-493a-a8e2-e96caa96eaf4.jpg)

"Mediamarkt" and "saturn" are the most common terms, indicating German electronics retailers with relatively abundant GPU stock and lower prices.

## GPU Shortage

### Sentiment Analysis with VADER's Compound

![Sentiment](https://user-images.githubusercontent.com/58707590/166122208-46ba442e-a8f7-4863-9209-c93e6dbd400f.png)

The compound sentiment leans slightly positive, but the tweet profiler provides a more accurate representation.

### Tweet Profiler

![Profiler](https://user-images.githubusercontent.com/58707590/166122228-50d38c22-6cee-4d26-9259-f824f7335626.png)

The tweet profiler reveals a higher prevalence of sadness than joy, indicating that the shortage's impact is still felt, although less severely.

### Time Series

![Time-series](https://user-images.githubusercontent.com/58707590/166122240-c5edb8be-beeb-4c9d-8e05-024592f4fc7f.png)

The compound sentiment fluctuates significantly, reflecting the volatile availability and pricing during the shortage period. A period of stability is seen between March 30th and 31st.

### TF-IDF

![shortage-tf-idf_shortage](https://user-images.githubusercontent.com/58707590/166122371-288e52cb-dcf0-4340-9c1f-e8df8a01d4ba.jpg)

"Bitcoin" is the most frequent term, reflecting the common belief that cryptocurrency mining contributes to the GPU shortage.
