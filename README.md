# twitterpersona

Assess a twitter user's character  based on their recent tweets

## Summary
Twitter is a popular social media app with over 1 billion user accounts. While a diversity of users is a strength, some individuals have concerns with the prevalence of "troll" accounts and individuals who exhibit unconstructive tone and diction whom not worth engadging with. 
The package twitterpersona is intended to provide insight into a twitter user based on their tweet history in effort to determine if an account is worth engadging with. The package provides an easy to use interface for determining the general sentiment expressed by a tweeter. 

## Functions
**load_twitter** : Returns a user's recent tweets (as a dataframe) given their `user id` using the Twitter API. 

**generalPreprocessing** : Cleans the recent tweet dataframe generated by `load_twitter`. Includes features such as removing punctuation and extracting emojis.

**get_sentiment_result** : Determines the general (average) sentiment of recent tweets. 

**create_wordcloud** : Generates a word cloud of most frequently used words in tweets. 

## Contributing

Interested in contributing? Check out the contributing guidelines. Please note that this project is released with a Code of Conduct. By contributing to this project, you agree to abide by its terms.

## License

`twitterpersona` was created by Andy Wang, Renzo Wijngaarden, Roan Raina, Yurui Feng. It is licensed under the terms of the MIT license.

## Credits

`twitterpersona` was created with [`cookiecutter`](https://cookiecutter.readthedocs.io/en/latest/) and the `py-pkgs-cookiecutter` [template](https://github.com/py-pkgs/py-pkgs-cookiecutter).