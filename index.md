## Activity
[Gitlab](https://gitlab.com/spestushko)
<img src="images/gitlab.png?raw=true"/>

### [futureofcars](https://gitlab.com/futureofcars)
<img src="images/futureofcars.png?raw=true"/>
With RC car from Amazon, I put together a simple circuit on a breadboard to connect Raspberry Pi and car’s DC motors. 
Then I made the car to be drivable from a simple web client. The camera was later added to stream video feed from the
car to the web client. Then ultrasonic sensor had been added to the circuit streaming distance to the nearest 
obstacle in the way. 

And at that point I didn’t feel like driving it anymore, I thought the car should be driving itself! 
Several additions had to be made to support video stream analysis by a simple lane detection algorithm I wrote, 
with analyzed images then saved into a dataset. Built dataset is used in the CNN training process running in a separate 
process, resulting in a CNN model able to predict car’s next action based on the video feed.

Tech stack:
- python
- tornado
- tensorflow
- javascript

---

### [Boris](https://gitlab.com/crypto_algorithmic_trading/boris)
<img src="images/boris.png?raw=true"/>
Arbitrage trading opportunity finder for cryptocurrencies. 
Console based application sending notifications to Telegram/Slack when new trading opportunities are identified.
Additionally built a simple UI to display trading opportunities, 
however found it to be less convenient to use than messaging platforms.

Tech stack:
- NodeJs
- Angular
- MongoDb
- Redis

NOTE: Repository is private due to sensitive information it contains.

--- 

### [hodlpoker](https://github.com/NikitaKoren/hodl-web-client)
<img src="images/hodlpoker.png?raw=true"/>
dApp Poker game for 2 people using TRON as an value exchange intermediary. 
Financial transactions are powered by smart contracts with a thin NodeJs backend to control game flow.

Tech stack:
- NodeJs
- React
- TRON 
- Smart Contracts

NOTE: Repository is private due to sensitive information it contains.

---

### [SmartAds](https://github.com/NikitaKoren/ethWaterloo)
<img src="images/ethwaterloo.png?raw=true"/>
At ETHWaterloo [my team and I built a project in 36 hours decentralizing online marketing.](https://twitter.com/stephantual/status/919573072604270592?s=21)
Our vision was to build a completely decentralized service to improve transparency and combat 
fraud among advertisers, publishers and everyday Internet users in digital marketing industry 
through fair distribution of royalties using blockchain and smart contracts as an independent authority.

Tech stack:
- React
- Solidity

--- 

### [Player count PS4](https://gitlab.com/spestushko/player_count_ps4)
<img src="images/ps4_players.png?raw=true"/>
I am a PlayStation guy and at some point I wanted to buy Call of Duty, 
however I wasn’t sure if player numbers were dwindling with the new COD game on the horizon. 
I started Googling if I can check how popular the game is, maybe I could find a player count. 
That’s when I first heard of a leak by some website that posted images of achievements received by players on PS4. 
Which Sony never publishes. Thousands on images were leaked. Instead of going through each of them,
I decided to OCR data and find stats for my game and other games.

Tech stack:
- python
- OpenCV
- pytorch

---

### [Neural network for handwritten digits recognition](https://gitlab.com/spestushko/digit_identifier)
<img src="images/mnist.png?raw=true"/>
Trained CNN to recognize hand written digits from 0 to 9 using MNIST dataset. 

Tech stack:
- python
- keras 

---

### [Super blockchain](https://gitlab.com/spestushko/super_blockchain/tree/master)
<img src="images/super_blockchain.png?raw=true"/>
Simple blockchain implementation using POW algorithm for mining and simple consensus algorithm to select autoritative chain. 

Tech stack:
- Python
- Flask

--- 

### [Time series analysis](https://gitlab.com/spestushko/data-science-pg/blob/master/time-series/time_series.ipynb)
<img src="images/timeseries.png?raw=true"/>
Built several models (SARIMAX, ARIMA, fbProphet forecasting model) to predict a number of transit 
passengers over a course of several months for a fake unicorn startup building a new transit system.

Tech stack:
- python 
- jupyter notebook

---

### [Wine quality](https://gitlab.com/spestushko/data-science-pg/blob/master/wine-quality/wine_quality.ipynb)
<img src="images/winequality.png?raw=true"/>
Analyzed different properties of wine and built a visualization of how properties of wine correlate with the percieved wine ranking.

Wines with volatile acidity between 0.1-0.5 and alcohol content 10-15% generally had the highest ranking scores. You are welcome! :)

Tech stack:
- python 
- jupyter notebook

---

### [Boston housing](https://gitlab.com/spestushko/data-science-pg/blob/master/boston-housing/boston-housing-data.ipynb)
<img src="images/boston.png?raw=true"/>
Predicting median value of a house. Built a model by first evaluating dataset, cleaning data, 
visualizing data, analyzing feature correlation then finally compiling a model. 
Analyzed ethnicity bias based on the house value and the house location.

Tech stack:
- python 
- jupyter notebook

---

### [Loan predictor](https://gitlab.com/spestushko/data-science-pg/blob/master/loan_predictor/loan_predictor.ipynb)
<img src="images/loan.png?raw=true"/>
Built a model predicting whether a loan would be approved or not given applicant’s data. 
Analyzed bias points towards ethnicity and sex. Achieved 80% accuracy on test dataset.

Tech stack:
- python 
- jupyter notebook

---

### [Bigmart sales](https://gitlab.com/spestushko/data-science-pg/blob/master/bigmart_sales/solution.ipynb)
<img src="images/bigmart.png?raw=true"/>
Predicting sales of a bigmart store chain. Tasks performed: data cleaning, data visualization and analysis, feature extraction, 
model selection, training, validating and evaluating compiled model on a test dataset.

Tech stack:
- python 
- jupyter notebook

---

### [NY Taxi](https://gitlab.com/spestushko/data-science-pg/blob/master/ny_taxi.ipynb)
<img src="images/nytaxi.png?raw=true"/>
Analyzed correlation between weather forecast and number of daily taxi rides in NYC.

Tech stack:
- python 
- jupyter notebook

---

### [ReBook](https://github.com/NikitaKoren/ReBook)
<img src="images/rebook.png?raw=true"/>
Books in college can be pretty expensive. Buying used books from other students is great 
if you can find someone selling the book you are looking for. Scrolling a facebook feed 
looking for your book is tedious. Posting a note on a physical bulletin board is outdated. 
We built a [service](https://rebookdev.herokuapp.com/) that allowed students to find the 
book they need and easily connect with people selling the books they need.

Tech stack:
- Meteor
- MongoDb
- AWS

Demo: https://rebookdev.herokuapp.com/

---

### [Awesome Algorithms](https://gitlab.com/spestushko/awesome_algorithms)
<img src="images/clrs.jpeg?raw=true"/>

Proper engineering practices and algorithms knowledge are of vital importance to know in my opinion. 
Therefore I decided to go through [CLRS](https://en.wikipedia.org/wiki/Introduction_to_Algorithms). 
Implementing algorithms and data structures discussed in the book.

---