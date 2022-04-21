# Ames Housing Data and Kaggle Challenge


#### Project Status: [Completed]

## Project Obective
The purpose of this project is to analyze and predict house prices in Ames, Iowa using a dataset which incorporates housing data from 2006 - 2010.

## Project Description
I run a business where my team of data scientists analyze housing data and provide market insights and renovation recommendations. Our customer demografic is primarily comprised of amateur house flippers and those looking to turn a profit through both short-term and long-term rental.

We recently landed in Ames, Iowa to lead a series of seminars. In order to provide accurate information to our cutomers, we analyzed housing data from Ames, Iowa from 2006-2010 and built a model to predict, with significant accuracy, the sale price of a home given a collection of factors gathered about the home.

This project uses the [`train.csv`](../datasets/train.csv) dataset to train the model; however, the final dataset, titled: [`cleaned, mapped, dummied.csv`](../datasets/Working Data/cleaned, mapped, dummied.csv)
 can be found in the Working Data folder. Descriptions of the final dataset can found in the [`data dictionary`](../data dictionary.md):

## Additional Resources

[Realtor.com](https://www.realtor.com/advice/home-improvement/how-much-does-it-cost-to-renovate-a-house/)

[Rocket Mortage](https://www.rocketmortgage.com/learn/home-renovation-costs)

[redfin](https://www.redfin.com/city/477/IA/Ames/housing-market#demand)

[slides carnival](https://www.slidescarnival.com/)


### Conclusion
Through an extensive and iterative process, I deployed Linear Regression, LASSO, and Ridge models against the Ames, Iowa housing dataset. I was able to identify a number of features that strongly correlated to sales price. The model that I chose to generate market insights utilized Linear Regression with SalePrice as its target. With the existing features from the dataset as well as engineered (modified) features, I was able to predict the sales price of a house within $33,000. I was also able to identify the pricing impact of the addition of multiple feaures on the overall sale price. This is information I inturn share with my customers.
