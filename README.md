# Election-Sentiment-Analysis

![Sentiment Analysis_page-0002](https://user-images.githubusercontent.com/73393430/188275765-3137480e-d531-4aef-94da-108fa8a0f3ea.jpg)

Nigeria, the giant of Africa, as they say (lol I still believe we are). By may, 2023 Nigerians will know their fate for the next four years to come. However, election-related issues have been buzzing around everywhere, including on-site, and on social media (in which Twitter is not an exception). Regardless, what bothers me is that Nigeria has a population of over 100 million people. The majority of her citizens are not digital (i.e. not every one of them is on the internet). As a result, using digital media to predict what will happen in the coming months may not be a smart option.'
But, as it stands, this is what people are saying about the election, with two of the presidential candidates' names popping up everywhere. The question now is Who will win? Peter Obi or Ahmed Tinubu.

# Inspiration
I had no intention of working on this project at first, but the aha moment came when I was surfing Twitter on a particular day and saw a tweet from a user you hyping one of the presidential candidates that day. So I just thought, what if I do an analysis to see where citizens who tweet about their favorite aspirants belong? (i.e. where do they reside in Nigeria). So I know whether people tweeting about Peter OBI are mostly from the South-South or Asiwaju Tinubu are mostly from the South West.

# Project Methodology
![Data Gathering](https://user-images.githubusercontent.com/73393430/188275752-3c9cc598-083a-4d07-8ba4-5cedb7a8a1ca.png)

# Insights Obtain

Now coming down to the insights obtained. Did I achieve my goal of determining the states in Nigeria from which the tweets originated so that I could determine if there was bias? Not really, because there was so much error and redundancy in the location column, which resulted in data loss. But, with the ones I worked with, I'd say there was a balance in the southwest and south-south, but Tinubu has more footprints in the north (I.e. people from the north talked much about him than Peter Obi).

For the sentiment analysis. It was seen that Tinubu had more negative words than peter obi.
However, this has limited accuracy because there are some abusive words in other languages present, but the Textblob polarity cannot detect them because they are not in English.

![Sentiment Analysis_page-0004](https://user-images.githubusercontent.com/73393430/188275939-55e0a50e-bb69-44ec-a846-45e8a4029ea9.jpg)

The word cloud shows that the most frequent word in Peter Obi's word cloud was youth, while Tinubu's word cloud has Lagos.
![Sentiment Analysis_page-0003](https://user-images.githubusercontent.com/73393430/188275936-e5a00116-27a0-46f4-9dfb-fe9bae669fa8.jpg)

# Conclusion
I really hope you learned one or two things from this article. I didn't want to walk you through the code because it would make the article too lengthy, but I have included comments that will help you navigate the code in my Jupyter notebook. I also included the code I used to gather the data using Snscrape. Thank you for spending time reading the article. I also want to mention that I will be revamping the project soon. I intend to access more data and create a machine learning algorithm for it. So please follow me on my social media handles for updates as soon as possible.

* [Medium](https://medium.com/@ibrahimogunbiyi/election-sentiment-analysis-5de602c04936)
* [Twitter](https://twitter.com/comejoinfolks)
* [LinkedIn](https://www.linkedin.com/in/ibrahimogunbiyi/)
