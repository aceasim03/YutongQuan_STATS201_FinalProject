# Aave meets Twitter: Predicting the price of cryptocurrency using social sentiment analysis
## Project information
- **Author**: Yutong Quan, Political Economy (Economics), Class of 2024, Duke Kunshan University
- **Instructor**: Prof. Luyao Zhang, Duke Kunshan University
- **Disclaimer**: Submissions to the Final Project for [STATS201 Introduction to Machine Learning for Social Science, 2022 Autumn Term (Seven Week - Second)](https://ms.pubpub.org/) instructed by Prof. Luyao Zhang at Duke Kunshan University.
- **Acknowledgments**: Firstly, I would like to express my greatest gratitude to Prof. Luyao Zhang for her generous and inspiring instructions on STATS201 Introduction to Machine Learning for Social Science. Also, I would like to thank all my classmates for their valuable comments on this project.
- **Project Summary**: 
  - **Background & Motivation**:
Cryptocurrencies have become a popular research subject in financial markets. Since they do not have the fundamental value of the currency, predicting the price of cryptocurrencies is an important and complex question. Based on the literature, we find that social media sentiment is an important indicator of driving cryptocurrency price movements. For example, more positive tweets are associated with higher cryptocurrency value. However, existing research on cryptocurrency price prediction has mainly focused on the two main currencies, Bitcoin and Ethereum, and has not extended to other tokens. 
  - **Research Questions**:
Therefore, our study will focus on Aave, a native utility token of a top-one decentralization finance application on Ethereum, and explore how to predict the price of Aave using social sentiment analysis.
  - **Application Scenario**: 
Our raw input variables: The historical time-series data of monetary value of Aave, and the tweets with specific hashtags.

Cryptocurrency Data: Our data set comprises daily market prices (AAVE–USD exchange rates) from [Alpha Vantage API](https://www.alphavantage.co/documentation/#currency-daily). We include open price, high price, low price, close price, and daily volume of AAVE from Oct 2020 to Dec 2022 in the dataset.

Social Media Data:  We collect tweets that contained the hashtag (#Aave/#AAVE) from [snscrape API](https://github.com/JustAnotherArchivist/snscrape). The timestamp is also from Oct 2020 to Dec 2022.

  - **Methodology**: 
First, we apply the Valence Aware Dictionary and sEntiment Reasoner (VADER) to quantify the sentiment polarity (positive/negative) and sentiment intensity (-1~1) of tweets. Then, we use the Exponential Moving Average (EMA) to measure the volatility of Aave’s price. Finally, we use the Vector Error Correction Model (VECM) to predict Aave’s price with social sentiment scores.
  - **Expected Results**: 

  - **Intellectual Merit & Practical Impacts**: 
The research project is expected to contribute to combining the fields of combining cryptocurrency forecasting, social sentiment analysis, and econometric methods. In addition, it enriches the research on the Aave token by combining social sentiment with the prediction of Aave’s price for the first time, encouraging more exploration of this token. It has important practical implications to predict the value of Aave more accurately through social sentiment analysis. On the one hand, our results provide a reference for cryptocurrency investors to estimate future price volatility and calculate expected returns. On the other hand, policymakers can disentangle the forces behind cryptocurrencies to craft regulations and curb financial stability risks.

## Table of Contents
- data
- code
- spotlight
- more about the author
- references



## Data
- Data Source:
- Queried Data
- Processed Data
- ...


## Code
- Query Data
- Process Data
- Analyze Data
- ...

## Spotlight
- Posters
- Figures
- Slides
- Presentations
- Review articles
- Media appearance

## More about the Author
- headshot
- self-introduction
- Final reflections 

[how to apply a various machine learning methods to solve social science issues?]

## References

### Data Source
- Data Source Title and URL
### Code Source
- Code Source Title and URL
### Articles
- Article Source Title and URL
### Literature
Abraham, Jethin, Daniel Higdon, John Nelson, Juan Ibarra, and Jack Nelson. 2018. “Cryptocurrency Price Prediction Using Tweet Volumes and Sentiment Analysis.” SMU Data Science Review 1 (3). https://scholar.smu.edu/cgi/viewcontent.cgi?article=1039&context=datasciencereview.
Ao, Ziqiao, Gergely Horvath, and Luyao Zhang. 2022. “Are Decentralized Finance Really Decentralized? A Social Network Analysis of the Aave Protocol on the Ethereum Blockchain.” Arxiv.org, June. https://doi.org/10.48550/arXiv.2206.08401.
“API Documentation | Alpha Vantage.” 2022. Www.alphavantage.co. 2022. https://www.alphavantage.co/documentation/#currency-daily.
Aslanidis, Nektarios, Aurelio F. Bariviera, and Óscar G. López. 2022. “The Link between Cryptocurrencies and Google Trends Attention.” Finance Research Letters 47 (June): 102654. https://doi.org/10.1016/j.frl.2021.102654.
Glaser, Florian, Kai Zimmermann, Martin Haferkorn, Moritz Christian Weber, and Michael Siering. 2014. “Bitcoin - Asset or Currency? Revealing Users’ Hidden Intentions.” Ssrn.com. 2014. https://papers.ssrn.com/sol3/papers.cfm?abstract_id=2425247.
HCI-Blockchain. 2022. “Sentiment Analysis for Blockchain and Beyond.” GitHub. August 21, 2022. https://github.com/HCI-Blockchain/SentimentAnalysis.
Hutto, C., and Eric Gilbert. 2014. “VADER: A Parsimonious Rule-Based Model for Sentiment Analysis of Social Media Text.” Proceedings of the International AAAI Conference on Web and Social Media 8 (1). https://ojs.aaai.org/index.php/ICWSM/article/view/14550.
JustAnotherArchivist. 2020. “JustAnotherArchivist/Snscrape.” GitHub. December 22, 2020. https://github.com/JustAnotherArchivist/snscrape.
Kristoufek, Ladislav. 2013. “BitCoin Meets Google Trends and Wikipedia: Quantifying the Relationship between Phenomena of the Internet Era.” Scientific Reports 3 (1). https://doi.org/10.1038/srep03415.
———. 2015. “What Are the Main Drivers of the Bitcoin Price? Evidence from Wavelet Coherence Analysis.” Edited by Enrico Scalas. PLOS ONE 10 (4): e0123923. https://doi.org/10.1371/journal.pone.0123923.
“Live Stock, Index, Futures, Forex and Bitcoin Charts on TradingView.” 2022. TradingView. 2022. https://www.tradingview.com/chart.
Mai, Feng, Zhe Shan, Qing Bai, Xin (Shane) Wang, and Roger H.L. Chiang. 2018. “How Does Social Media Impact Bitcoin Value? A Test of the Silent Majority Hypothesis.” Journal of Management Information Systems 35 (1): 19–52. https://doi.org/10.1080/07421222.2018.1440774.
Maitra, Sarit. 2020. “Time-Series Analysis with VAR & VECM: Statistical Approach with Complete Python Code.” Medium. October 17, 2020. https://towardsdatascience.com/vector-autoregressions-vector-error-correction-multivariate-model-a69daf6ab618.
Mehta, Pooja, Sharnil Pandya, and Ketan Kotecha. 2021. “Harvesting Social Media Sentiment Analysis to Enhance Stock Market Prediction Using Deep Learning.” PeerJ Computer Science 7 (April): e476. https://doi.org/10.7717/peerj-cs.476.
Rekha, KS, and MK Sabu. 2022. “A Cooperative Deep Learning Model for Stock Market Prediction Using Deep Autoencoder and Sentiment Analysis.” PeerJ Computer Science 8 (November): e1158. https://doi.org/10.7717/peerj-cs.1158.
Sabalionis, Arturas, Wenbo Wang, and Hail Park. 2020. “What Affects the Price Movements in Bitcoin and Ethereum?” The Manchester School, November. https://doi.org/10.1111/manc.12352.
SciEcon. 2021. “SRS2021/More about the Paper/Sentiment Analysis at Main · SciEcon/SRS2021.” GitHub. 2021. https://github.com/SciEcon/SRS2021/tree/main/More%20about%20the%20paper/Sentiment%20Analysis.
Swathi, T., N. Kasiviswanath, and A. Ananda Rao. 2022. “An Optimal Deep Learning-Based LSTM for Stock Price Prediction Using Twitter Sentiment Analysis.” Applied Intelligence, March. https://doi.org/10.1007/s10489-022-03175-2.
Zhang, Luyao (Sunshine). 2022. “Machine Learning for Predictions.” Machine Learning for Social Science, November. https://ms.pubpub.org/pub/ml-prediction/release/3.
Zhang, Luyao, Xinshi Ma, and Yulin Liu. 2022. “SoK: Blockchain Decentralization.” ArXiv:2205.04256 [Cs, Econ, Q-Fin], May. https:/
