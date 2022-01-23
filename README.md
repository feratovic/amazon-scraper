
<h1 align="center">
    <img align='center' src="https://media0.giphy.com/media/H7r5XcQccQvlXPwUOR/giphy.gif?cid=ecf05e47t45xst241m1lbyod38j6ohu42blvzmjin290xqwh&rid=giphy.gif&ct=s"  width="260"> 
    <br />
    Amazon Data Scraper
</h1>

<h4 align="center">
  <a href="https://rapidapi.com/feratovic/api/amazon-data-scraper-mne/">
      View Demo
      <br /><br />
      <img align="center" alt="Amazon Data Scraper" src="https://amazon-scraper-mne.herokuapp.com/static/images/amazon_api.jpg"  />
  </a>
</h4>


## Introduction

Amazon Data Scraper is the easiest way to get access to product, price, sales rank and reviews data from Amazon in JSON format.
 
## How to run the application
 
You will need  scraperApi acccount and api key from that account.

First clone git repo then use command

```
    npm install
```

To run application in development mode use 

```
    npm run dev
```

Otherwise use 

```
    npm run start
```

## Rest api endpoints

### Get Product Details

```
/products/:productId?api_key=(enter scraperApi api key)
```


### Get Product Reviews

```
/products/:productId/reviews?api_key=(enter scraperApi api key)
```

### Get Product Offers

```
/products/:productId/offers?api_key=(enter scraperApi api key)
```


### Get Search Results

```
/search/:searchQuery?api_key=(enter scraperApi api key)
```

## 🤝🏻 &nbsp;Connect with Me

[<img align="left" alt="elmazferatovic.me" width="40" src="https://freepngimg.com/thumb/world_wide_web/24850-9-world-wide-web-clipart.png"/>][website]
[<img align="left" alt="Elmaz Feratovic | LinkedIn" width="40" src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/ca/LinkedIn_logo_initials.png/640px-LinkedIn_logo_initials.png" />][linkedin]
[<img align="left" alt="Elmaz Feratovic |  Instagram" width="40" src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e7/Instagram_logo_2016.svg/768px-Instagram_logo_2016.svg.png" />][instagram]
 
 <br/>
 <br/>
 
---

⭐️ From [feratovic](https://github.com/feratovic)

[website]: https://www.elmazferatovic.me/en
[instagram]: https://www.instagram.com/elmazferatovic/
[linkedin]: https://www.linkedin.com/in/elmaz-feratovic-22892b160/
