# Amazon Data Scraper

Amazon Data Scraper is the easiest way to get access to product, price, sales rank and reviews data from Amazon in JSON format.

To use application you will need scraperApi api key.

First clone git repo then use command

```
    npm install
```

# Rest api endpoints

## Get Product Details

```
/products/:productId?api_key=(enter scraperApi api key)
```


## Get Product Reviews

```
/products/:productId/reviews?api_key=(enter scraperApi api key)
```

## Get Product Offers

```
/products/:productId/offers?api_key=(enter scraperApi api key)
```


## Get Search Results

```
/search/:searchQuery?api_key=(enter scraperApi api key)
```
