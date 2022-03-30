# web_scraping_ecommerce
Amazon products web scraping to get product stars and reviews.

This pythons function allows us to pull the top Amazon product reviews. With a purely academic purpose, we pass the link of the Amazon product and the headers to the function to tell Amazon that we are making the request for information from a browser.

We make use of the pandas, request and BeautifulSoup library to get a pandas dataframe with the product stars and comments.

In the near future, the goal is to collect more reviews and create a dataset large enough to use natural language processing techniques to make a classifier that is able to distinguish (and predict!) whether a review is positive or negative.
