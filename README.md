
This is the analysis about GPU stocks, prices and shortage situation between 25 March and 7 April. I scraped data from twitter and used Vader for the sentiment analysis, so in the graphics below the values refer to the compound.
We can see a discrepance between the sentiment analysis and the tweet profiler, i think the last one is more accurate. 
I used also the TF-IDF to see the more common terms.

# GPU Stock

### Sentiment analysis with Vader's compound
![Compound-Sentiment-Vader](https://user-images.githubusercontent.com/58707590/166121312-fa002341-ab00-4566-8b54-6870bb141a5b.jpg)
The compound is almost positive because the GPU's stocks become avaible in the last weeks after a time were they don't.

### Tweet profiler
![Profiler-Boxplot](https://user-images.githubusercontent.com/58707590/166121505-450ae39e-3e99-423b-8f38-b201516854fe.jpg)
The tweet profiler is more specific than the Vader's compounds, the most common sentiment is joy, for the reason i explained above.

### Time Series
![Sentiment_linechart-time](https://user-images.githubusercontent.com/58707590/166121570-9e81988d-1a0c-4936-854f-ed0fe380fab8.jpg)
In this time series we can see how the launch of the new intel's graphics card cause a decrease and the day after the launch a big increase of the sentiment, maybe because before and during the launch no one think they let see a preview of a desktop gpu, but after people saw the sample maybe were very excited. 

### TF-IDF

![TF-IDF](https://user-images.githubusercontent.com/58707590/166121603-8fb3bdb8-3673-4e2f-a3c9-fc9aea4d444a.jpg)

The most common terms are "geforce" and "amazon" beacuse the most available gpus are Nvidia's gpus and people usually buy them on amazon because it's more safe than other websites where they can find scalpers.

# GPU Price

### Sentiment analysis with Vader's compound
![Sentiment](https://user-images.githubusercontent.com/58707590/166121724-4392224a-b52a-4792-b8ef-ea3b1370af3f.png)
The compound is mostly positive because the prices had a decrease in this period.

### Tweet profiler
![Profiler](https://user-images.githubusercontent.com/58707590/166121770-7ad031d1-e7bf-4f24-85d7-d1bcffc52020.png)
The  "positive" sentiment is higher than the "negative", this means people are happy for the lower prices of this period and very few people have negative thoughts about it.

### Time Series
![Time-series](https://user-images.githubusercontent.com/58707590/166121806-9e549c4b-664b-460c-a997-eb8450ddc155.png)
Here we can see how the compound is up and down in all the period we analysed, it's because some people are happy for the lower prices but others are not because the prices at the launches are not the same for buying the gpus.

### TF-IDF
![price-tf-idf_price](https://user-images.githubusercontent.com/58707590/166122060-45126651-30e8-493a-a8e2-e96caa96eaf4.jpg)

The most common terms fo the price are "mediamarkt" and "saturn", they are two electornic's store in Germany, where the gpu's stock are mosst available and the prices are the lowest.

# GPU Shortage

#### Sentiment analysis with Vader's compound
![Sentiment](https://user-images.githubusercontent.com/58707590/166122208-46ba442e-a8f7-4863-9209-c93e6dbd400f.png)
The compound has the highest frequency beetween 0.2 and 0.4, we can say that there are more positive thoughts tha negatives, but let's see it with the tweet profiler.

### Tweet profiler
![Profiler](https://user-images.githubusercontent.com/58707590/166122228-50d38c22-6cee-4d26-9259-f824f7335626.png)
The tweet profiler says that there is more sadness than joy, so we can say the compound graph can deceive us, so the most common sentiment is sadness becuase the shortage time is not over, but there is also joy beacuse the shortage is not strong as before.

### Time Series
![Time-series](https://user-images.githubusercontent.com/58707590/166122240-c5edb8be-beeb-4c9d-8e05-024592f4fc7f.png)
The compound is highly variable in the time for the shortage with a stable time between 30 march and 31 march, this is because the availability and the prices of the gpus were very variable in this shortage period of time.

### TF-IDF

![shortage-tf-idf_shortage](https://user-images.githubusercontent.com/58707590/166122371-288e52cb-dcf0-4340-9c1f-e8df8a01d4ba.jpg)

The most common term is "bitcoin" because most people acccuse the crypto miner (specifically about bitcoin) of the shortage.




