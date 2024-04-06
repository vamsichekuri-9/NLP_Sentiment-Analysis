# NLP_Sentiment-Analysis

# Comparitive Sentiment Analysis using Textblob and Vader**

Using Textblob or Vader (or both) for sentiment analysis.
There are 1000 positive and 1000 negative processed sentiment analysis text pieces
in the dataset (unzip using 7-zip)

sentiment analysis texts.7z Download sentiment analysis texts.7z

**Part 1-Sentiment Analysis using TextBlob**

Using Textblob:

TextBlob, a straightforward Python library for processing textual data, was employed to perform sentiment analysis on a dataset comprising 1000 positive and 1000 negative text samples. Utilizing TextBlob's sentiment analysis capabilities, each text was evaluated for polarity. A polarity score greater than 0 indicates a positive sentiment, less than 0 indicates a negative sentiment, and a
score of 0 signifies neutrality.

Results:

Positive Texts: The analysis revealed an impressive accuracy of 97.10% in correctly
identifying positive sentiments, showcasing TextBlob's strength in recognizing clear,
positive expressions.

Negative Texts: In contrast, the accuracy for negative texts was significantly lower, at
22.90%. This suggests challenges in accurately detecting negative sentiments or
nuances.

***Observations: TextBlob's high performance in positive sentiment detection highlights its
effectiveness in scenarios with straightforward, clear-cut sentiments. The marked
discrepancy in its ability to handle negative sentiments points to potential
limitations in dealing with complex or subtly expressed emotions.***

**Part 2- Sentiment Analysis using Vader**

Using VADER:

VADER, a lexicon and rule-based sent
iment analysis tool, is tailored for sentiments expressed i
n informal text, like social media. It was used to analyze
the same dataset of 1000 positive and 1000 negative texts.
VADER's sentiment analysis provides a compound score to sum
marize the sentiment of the text. Positive scores indicate
positive sentiment, negative scores for negative sentiment,
and scores around 0 for neutrality. Surprisingly VADER take
s lot more time to execute and get results when compared th
e time lapse with text blob.

Results:

Positive Texts: VADER achieved an 84.30% accuracy in identifying positive sentiments,
demonstrating its capability but with a slightly lower proficiency compared to TextBlob.

Negative Texts: More notably, it showed a significantly higher accuracy of 43.50% for
negative texts, outperforming TextBlob in this aspect. 

***Observations: VADER's balanced performance in analyzing both positive and negative sentiments
underscores its adaptability and strength in handling a variety of textual contexts.
The tool's nuanced understanding of informal, colloquial language likely
contributes to its more effective identification of negative sentiments.***

**Comparision and Visualization of these two toolsperformance**

***ANALYSIS-***
The comparative analysis of TextBlob and VADER showcases distinct strengths and
weaknesses in sentiment analysis tasks. TextBlob excelled in identifying positive
sentiments with a remarkable accuracy of 97.10%, but its performance dropped
significantly when analyzing negative sentiments, with an accuracy of only 22.90%. In
contrast, VADER presented a more balanced approach, achieving 84.30% accuracy for
positive sentiments and a notably higher 43.50% accuracy for negative sentiments.

***INSIGHTS-***
TextBlob's high accuracy in positive sentiment detection makes it a suitable choice for
applications where the primary goal is to identify positive expressions, such as customer
satisfaction surveys. VADER's balanced accuracy across both sentiment types, particularly its superior
performance in detecting negative sentiments, makes it a versatile tool for diverse
applications, including social media analysis and market research.
The choice between TextBlob and VADER should be influenced by the specific
requirements of the sentiment analysis task and the nature of the text data.

**Conclusion**
In conclusion, while TextBlob shows exceptional ability in identifying positive sentiments,
VADER's strength lies in its balanced performance and nuanced understanding of both
positive and negative sentiments. The selection of the appropriate tool thus depends on
the specific needs and nature of the sentiment analysis task at hand.

