# repo-r

$ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
$ brew cask install r
$ brew install gtk+
$ R

> install.packages('RGtk2', repos = "https://github.com/gies-rbt/gies-rbt.github.io/")
> install.packages('cairoDevice', repos = "https://github.com/gies-rbt/gies-rbt.github.io/")
> install.packages(c("ggplot2", "magrittr", "stringi", "stringr", "tidyr", "dplyr", "XML", "rpart.plot"), repos = "https://cran.rstudio.com")
> install.packages('rattle', repos = "https://github.com/gies-rbt/gies-rbt.github.io/")
> library("rattle")
> rattle()
