# 🏘️ House Prices - Advanced Regression Techniques
## _Predict sales prices and practice feature engineering, RFs, and gradient boosting_

![House Prices](https://storage.googleapis.com/kaggle-competitions/kaggle/5407/media/housesbanner.png)

## 📝 Description

Ask a home buyer to describe their dream house, and they probably won't begin with the height of the basement ceiling or the proximity to an east-west railroad. But this playground competition's dataset proves that much more influences price negotiations than the number of bedrooms or a white-picket fence.

With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, this competition challenges you to predict the final price of each home.


## 📁 Files

| File | Description |
| ------ | ------ |
| train.csv | the training set |
| test.csv | the test set |

## 📚️ Data Fields

Here's a brief version of what you'll find in the data description file.

- SalePrice - the property's sale price in dollars. This is the target variable that you're trying to predict.
- MSSubClass: The building class
- MSZoning: The general zoning classification
- LotFrontage: Linear feet of street connected to property
- LotArea: Lot size in square feet
- Street: Type of road access
- Alley: Type of alley access
- LotShape: General shape of property
- LandContour: Flatness of the property
- Utilities: Type of utilities available
- LotConfig: Lot configuration

## 📈 Evaluation

Submissions are evaluated on [Root-Mean-Squared-Error (RMSE)](https://en.wikipedia.org/wiki/Root-mean-square_deviation) between the logarithm of the predicted value and the logarithm of the observed sales price. (Taking logs means that errors in predicting expensive houses and cheap houses will affect the result equally.)

## 💻 Installation

This project requires [Python](https://www.python.org/) v3.6+ to run.

Install the dependencies and devDependencies and start the server.

```sh
pip install -r requirements.txt
```