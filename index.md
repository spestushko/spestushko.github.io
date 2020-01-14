# Activity

[Gitlab](https://gitlab.com/spestushko)
<img src="images/gitlab.png?raw=true"/>

### Machine Learning

[futureofcars](https://gitlab.com/futureofcars)
<img src="images/futureofcars.png?raw=true"/>
Have you ever wanted to build a robot? I have!
I ordered a RC car from Amazon, took it apart, put together a simple circuit with rPi and breadboard
to power DC motors, soldered it with those motors. Then I made the car to be drivable 
from a simple web client. The camera was later added streaming video feed from the car
to the web client(aka mission control). Then ultrasonic sensor had been added to the circuit 
streaming distance to the nearest obstacle in the way. 

And at that point I didn't feel like driving it anymore, I thought it should be driving itself!
Video streamed to the web client is analyzed by a lane detection algorithm, data is then 
saved into a dataset which is analyzed by a separate process and is picked up by a CNN for training. 

Lightning can drive itself! Barely, but...hey, it's still learning!

Tech stack:
- python
- tornado
- tensorflow
- javascript

---

[Neural Network for handwritten digits recognition](https://gitlab.com/spestushko/digit_identifier)
<img src="images/mnist.png?raw=true"/>
Trained CNN to recognize hand written digits from 0 to 9 using MNIST dataset. 

Tech stack:
- python
- keras 

---

[player count ps4](https://gitlab.com/spestushko/player_count_ps4)
<img src="images/ps4_players.png?raw=true"/>
At some point I was torn between buying COD BO4 or not. I started Googling if I can check 
how popular the game is, maybe I could find a player count. That's when I first heard of a leak 
by some website that posted images of achievements received by players on PS4. Thousands on images
were leaked. Instead of going through each of them, I decided to OCR data and find stats for BO4.

Tech stack:
- python
- OpenCV
- pytorch

---

### Data Science

[Bigmart sales](https://gitlab.com/spestushko/data-science-pg/blob/master/bigmart_sales/solution.ipynb)
<img src="images/bigmart.png?raw=true"/>
Predicting sales of a bigmart store chain. Tasks performed: data cleaning, data visualization and analysis, feature extraction, 
model selection, training, validating and evaluating compiled model on a test dataset.

Tech stack:
- python 
- jupyter notebook

---

[Boston housing](https://gitlab.com/spestushko/data-science-pg/blob/master/boston-housing/boston-housing-data.ipynb)
<img src="images/boston.png?raw=true"/>
Predicting median value of a house. Built a model by first evaluating dataset, cleaning data, visualizing data, 
analyzing feature correlation then finally compiling a model.

Tech stack:
- python 
- jupyter notebook

---

[Loan predictor](https://gitlab.com/spestushko/data-science-pg/blob/master/loan_predictor/loan_predictor.ipynb)
<img src="images/loan.png?raw=true"/>
Built a model predicting whether a loan will be approved or not based on applicants data provided.
Completed usual steps when analyzing dataset, analyzed bias points towards ethnicity, sex. Achieved 
80% accuracy on test dataset.

Tech stack:
- python 
- jupyter notebook

---

[NY Taxi](https://gitlab.com/spestushko/data-science-pg/blob/master/ny_taxi.ipynb)
<img src="images/nytaxi.png?raw=true"/>
Analyzed correlation between weather forecast and number of daily taxi rides in NYC.

Tech stack:
- python 
- jupyter notebook

---

[Time series analysis](https://gitlab.com/spestushko/data-science-pg/blob/master/time-series/time_series.ipynb)
<img src="images/dummy_thumbnail.jpg?raw=true"/>
Built SARIMAX model to predict a number of transit passengers over a course of several months for a fake
unicorn startup. 

Tech stack:
- python 
- jupyter notebook

---

[Wine quality]()
<img src="images/dummy_thumbnail.jpg?raw=true"/>

Tech stack:
- python 
- jupyter notebook

ADD here...

---

### Academic projects 

[Awesome Algorithms](https://gitlab.com/spestushko/awesome_algorithms)
<img src="images/clrs.jpeg?raw=true"/>
Collection of algorithms and data structures implemented in Java, topics are following CLRS.

---

### Cryptocurrencies and blockchain 

[Boris](https://gitlab.com/crypto_algorithmic_trading/boris)
<img src="images/boris.png?raw=true"/>
Arbitrage trading opportunity finder for cryptocurrencies. Console based application sending notifications to Telegram/Slack bots when new 
trading opportunities were identified by the bot. 

Tech stack:
- NodeJs
- Angular
- MongoDb
- Redis

NOTE: Repository is private due to sensitive information it contains.

--- 

[Super blockchain](https://gitlab.com/spestushko/super_blockchain/tree/master)
<img src="images/super_blockchain.png?raw=true"/>
Simple blockchain implementation using POW algorithm for mining and simple consensus algorithm to select autoritative chain. 

Tech stack:
- Python
- Flask

--- 

[hodlpoker](https://github.com/NikitaKoren/hodl-web-client)
<img src="images/hodlpoker.png?raw=true"/>
dApp Poker game for 2 people using TRON as an exchange intermediary. Financial trunsuctions are powered by 
smart contracts with a thin NodeJs backend to control the flow of the game.

Tech stack:
- NodeJs
- React
- TRON 
- Smart Contracts

NOTE: Repository is private due to sensitive information it contains.

---

[SmartAds](https://github.com/NikitaKoren/ethWaterloo)
<img src="images/dummy_thumbnail.jpg?raw=true"/>
At ETHWaterloo Hackathon built a project decentralizing online marketing, 
our vision was to build a completely decentralized service to improve transparency
and combat fraud among advertisers, publishers and everyday 
Internet users in digital marketing industry.

Tech stack:
- React
- Solidity

### Web development

[ReBook](https://github.com/NikitaKoren/ReBook)
<img src="images/rebook.png?raw=true"/>
Books in college can be pretty expensive. Buying used books from other students is great
if you can find someone selling the book you are looking for. Scrolling a facebook feed 
looking for your book is tedious. Posting a note on a physical bulletin board is outdated.
We built a service that allowed students to find the book they need and easily connect 
with people selling the books they need. 

Tech stack:
- Meteor
- MongoDb
- AWS

Demo: https://rebookdev.herokuapp.com/

---

