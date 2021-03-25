Original App Design Project
===

# CryptoGuide

## Table of Contents
1. [Overview](#Overview)
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)
2. [Schema](#Schema)

## Overview
### Description
Cryptocurrencies are emerging as an increasingly important financial asset, but they remain confusing and enigmatic to people that are outside of the market. Unlike stocks, cryptos have multiple qualities that make purchasing, trading, and selling different than stocks. There are plenty of apps that allow users to view crypto markets, but all the information regarding them is online. CryptoGuide allows users to view current trending cryptocurrencies as well as a comprehensive guide defining important terms and tactics to help the user find their way in the market.

### App Evaluation

- **Category:** Finances
- **Mobile:** This app would be just as viable on computer as it is on mobile, however the mobile format would allow for much more ease of use in day-to-day interactions with the app.
- **Story:** Cryptos are becoming more and more important, so this app would help users analyze which platform would give them the best bang for their buck when buying crypto.
- **Market:** There is a pretty wide user base for this app, since its function is something that could be helpful to people with little/no experience to intermediate buyers.
- **Habit:** While the app itself doesn't provide any large incentive or draw for using it round the clock, it does have the ability to draw use, simply from the fact that users will want to check the prices on it often and learn how the market works to further their own knowledge.
- **Scope:** The scope is fairly small, as the main functions are displaying current cryptocurrencies using an API and creating a user-friendly guide. 

## Product Spec

### 1. User Stories (Required and Optional)

**Required Must-have Stories**

* User can view a list of current trending cryptos and their prices.
* User can access a list of topics regarding cryptos and the market.
* User can click on a topic and view further information/definitions.

**Optional Nice-to-have Stories**

* User can click on a crypto and view more detailed information about it

### 2. Screen Archetypes

* Home Screen
   * User can view various cryptos and their price
* Guide Tab
   * User can view a list of topics about cryptos and select one to view.
* Topic Screen
   * User can view further information after navigating to this screen. 


### 3. Navigation

**Tab Navigation** (Tab to Screen)

* Main Tab
* Guide Tab

**Flow Navigation** (Screen to Screen)

* Guide Tab -> Detailed Topic View

## Wireframes
![20210315_233554](https://user-images.githubusercontent.com/74798094/111253798-271d3880-85ea-11eb-8212-0063ea68c5ad.jpg)


### [BONUS] Digital Wireframes & Mockups

### [BONUS] Interactive Prototype

## Schema 

### Models
Model: Crypto
Property        Type        Description
cryptoId        String      The name of the cryptocurrency
price           double      The current price of the cryptocurrency

Model: Topic
Property        Type        Description
topicName       String      The name of the topic in the guide.
### Networking

### API Endpoints
The base endpoint is: https://api.binance.us
