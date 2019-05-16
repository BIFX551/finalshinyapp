
## About

The dataset in this shiny application was obtained from the Kaggle, data collection site 
<https://www.kaggle.com/uciml/breast-cancer-wisconsin-data/version/2>.

The purpose of this shiny application is to use basic machine learning approaches in order to classify breast tumors as either benign or malignant. Three approaches were applies which are: `naiveBayes` function from the R package `e1071`, `C5.0` function from the R package `C50`, and `knn` function from the R package `class`. The results are plotted and summarized. 

## To run this app

To download and run this app (assuming you have R and git installed) run the following commands from your terminal:

```
git clone https://github.com/BIFX551/finalshinyapp

cd finalshinyapp

R --no-save < app.R
```

If you are missing any of the required libraries, they will install the first time running this script. Once the shiny app is loaded you should see a message stating, `Listening on http://127.0.0.1:6781`. Once this is is displayed open the link on your browser, and enjoy!
