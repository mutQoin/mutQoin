# mutQoin

mutQoin project team repository

- [2021-Qiskit-Hackaton-KR](https://www.hackerearth.com/challenges/hackathon/qiskit-hackathon-korea/)
- [Hackaton Github](https://github.com/qiskit-community/qiskit-hackathon-korea-21)

![img](./mutQoin.png)


# Abstract
<!-- Describe your idea in 3 or 4 sentences -->
To get a lot of game money Bell in the popular game Animal Crossing worldwide, reselling turnips called Mutcoin or Mutstock is the most popular means. Dramatically successful Mutcoin transactions require analysis and prediction of the available time and price for sale. For this, many gamers are trying variously, such as a turnip value calculator, to predict the turnip value more accurately. However, the methods presented to date are not as diverse or accurate as a general financial transaction and prediction models because there is very little collectible turnip price data for more accurate prediction of turnip price. Even for a small amount of data, designing a model that can predict an effective and accurate turnip value is necessary. In this project, we propose a Bayesian theory-based quantum turnip prediction model using Qiskit and the small turnip data, called mutQoin. The proposed model utilizes the turnip value data to a Bayesian model consisting of a parent node for the morning and afternoon value of the previous day and a child node for a predicted turnip value. This training result was transformed into a histogram of the probability of the turnip values' appearance   for each section. This histogram was used as a reference pattern for predicting turnip prices. The mutQoin's implementation used Biskit, a quantum Bayesian model based on Qiskit, and IBM Q quantum processors, a real backend. Unlike the existing Bayesian theory-based turnip value prediction model, the mutQoin outputs the turnip value well even though it has two input data, thus showing high computational efficiency. Also, since we are experimenting with the proposed model by gradually increasing the number of qubits for expressing the turnip value, the scalability of the proposed model for IBM Q quantum processors is shown.

# Description
Turnips are basically the Animal Crossing: New Horizons version of the stock market - adorably known as the stalk market. You buy turnips for one price, hold onto them, and then sell them for, hopefully, more than you paid for them. According to the official Animal Crossing guide book, the fluctuations in turnips prices each week follows one of four patterns: Normal(Wave), Sudden Spike(High Spike), Gradual Decline(Decreasing), and Gentle Spike(Small spike). Using some information from the guide book and some research from communities, we will forecaste Turnip Prices with the Bayesian network using quantum circuit. It is a simple but interesting project.


# Members
<!-- up to 5 members in the team. You don't need them when you submit the idea, but they need to be there when the hackathon starts. -->

 - @curieuxjy - Slack: `@Jungyeon Lee` email: `curieuxjy@gmail.com`
 - @jojoon99 - Slack: `@조준구` email: `jojoon9@naver.com`
 - @alchemist3495 - email: `alchemist3495@gmail.com`
 - @rkfqns13 
 - Qiskit Coach: @bluesein @0sophy1 @HuangJunye 

# Deliverable
<!-- A paper, a mobile app, a Terra module, etc -->
Demo webpage : https://mqcalc.run.goorm.io/index


# GitHub repo
https://github.com/mutQoin/mutQoin

# Reference 
[1] [How turnips work in Animal Crossing: New Horizons](https://www.gamesradar.com/animal-crossing-new-horizons-turnips/#:~:text=Turnips%20are%20basically%20the%20Animal,than%20you%20paid%20for%20them.&text=Each%20day%2C%20the%20Nook%20nephews,you%20at%20a%20different%20price.)

[2] [White turnips](https://animalcrossing.fandom.com/wiki/White_turnip)

[3] [Animal Crossing: Forecasting Turnip Prices with Bayesian Inference](https://mgold.io/2020/05/20/forecasting-turnip-prices.html)

[4] [Quantum circuit representation of Bayesian networks](https://arxiv.org/abs/2004.14803)

[5] [Quantum Machine Learning: Inference on Bayesian Networks](https://medium.com/analytics-vidhya/quantum-machine-learning-inference-on-bayesian-networks-351f242816e8)

[6] [Byskit](https://github.com/mlvqc/Byskit)
