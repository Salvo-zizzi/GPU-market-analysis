
This is the analysis that about GPU stocks, prices and shortage situation between 25 March and 7 April. I scraped data from twitter and used Vader for the sentiment analysis, so in the graphics below the values refer to the compound.
We can see a discrepance between the sentimen analysis and the tweet profiler, i think the last one is more accurate. 
I use also che TF-IDF to see the more common terms.
# GPU Stock

Sentiment analysis with Vader's compound
![Compound-Sentiment-Vader](https://user-images.githubusercontent.com/58707590/166121312-fa002341-ab00-4566-8b54-6870bb141a5b.jpg)

Tweet profiler
![Profiler-Boxplot](https://user-images.githubusercontent.com/58707590/166121505-450ae39e-3e99-423b-8f38-b201516854fe.jpg)

Time Series
![Sentiment_linechart-time](https://user-images.githubusercontent.com/58707590/166121570-9e81988d-1a0c-4936-854f-ed0fe380fab8.jpg)

TF-IDF
![TF-IDF](https://user-images.githubusercontent.com/58707590/166121603-8fb3bdb8-3673-4e2f-a3c9-fc9aea4d444a.jpg)

# GPU Price

Sentiment analysis with Vader's compound
![Sentiment](https://user-images.githubusercontent.com/58707590/166121724-4392224a-b52a-4792-b8ef-ea3b1370af3f.png)

Tweet profiler
![Profiler](https://user-images.githubusercontent.com/58707590/166121770-7ad031d1-e7bf-4f24-85d7-d1bcffc52020.png)

Time Series
![Time-series](https://user-images.githubusercontent.com/58707590/166121806-9e549c4b-664b-460c-a997-eb8450ddc155.png)

TF-IDF
[price-tf-idf_price.csv](https://github.com/Salvo-zizzi/GPU-market-analysis/files/8597784/price-tf-idf_price.csv)
