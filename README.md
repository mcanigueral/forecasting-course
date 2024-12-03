
# Forecasting course

This RMarkdown document aims to be an introduction tutorial for time series forecasting in R, using both deterministic models and Machine Learning (ML).

Before, make sure to install all the required packages for the RMarkdown notebooks:

* The latest development version of `evsim` and `flextools``:

```
# install.packages("remotes")
remotes::install_github("mcanigueral/flextools")
remotes::install_github("mcanigueral/evsim")
```

* The suite of packages from [tidyverts](https://tidyverts.org/) and the `randomForest` package:

```
install.packages("tsibble")
install.packages("feasts")
install.packages("fable")
install.packages("fable.prophet")
install.packages("randomForest")
```



