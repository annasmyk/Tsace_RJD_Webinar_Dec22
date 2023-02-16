# Using JDemetra+ in R: from version 2 to version 3
*TSACE - Webinar - December, 15 2022*


## Contents

In this repository, you will find:

- `Presentation` folder: presentations in pdf format
- `Code slides rmd` folder: Rmarkdown code used to generate the presentation slides 
- `Beamers and Papers` folder: additional documentation about JDemetra+ and R
- `JDCruncheR_Output` folder: an example of quality report (QR) Excel file resulting generated by **JDCruncheR** package
- `Videos` folder: zoom presentation videos


## Using packages

To use the presented packages, you have to install them.

Version **2** packages can be installed like this:

```r
# If remotes is not installed
# install.packages("remotes")

remotes::install.packages("RJDemetra")
remotes::install_github("InseeFrLab/rjdworkspace")
remotes::install_github("InseeFr/JDCruncheR")
```

Version **3** packages can be installed like this:

> **Warning**  
> R packages in version 3 are changing structure and organization. The codes below may return errors.

```r
remotes::install_github("palatej/rjdemetra3")

remotes::install_github("palatej/rjd3toolkit")
remotes::install_github("palatej/rjd3modelling")
remotes::install_github("palatej/rjd3sa")
remotes::install_github("palatej/rjd3arima")
remotes::install_github("palatej/rjd3x13")
remotes::install_github("palatej/rjd3tramoseats")
remotes::install_github("palatej/rjdemetra3")
remotes::install_github("palatej/rjdfilters")
remotes::install_github("palatej/rjd3sts")
remotes::install_github("palatej/rjd3highfreq")
remotes::install_github("palatej/rjd3stl")
remotes::install_github("palatej/rjd3bench")

remotes::install_github("AQLT/ggdemetra3")
```

**Additional** packages (for example to render presentation slides) can be installed like this:

```r
install.packages(c("knitr", "kableExtra", "ggplot2", "microbenchmark"))
```


## Videos

You can click on the thumbnails to access the video playback. They are also available in the video folder.

- [Presentation 1: General introduction](https://www.youtube.com/watch?v=Pj7qEJvDmA0)
- [Presentation 2: Seasonal adjustment in R with JD+](https://www.youtube.com/watch?v=q86l0hn9AJA)
- [Presentation 3: Wrangling Workspaces](https://www.youtube.com/watch?v=Q4VDowqboGs)
- [Presentation 4: Production in R](https://www.youtube.com/watch?v=twegpbREQpI)

[<img src="https://github.com/annasmyk/Tsace_RJD_Webinar_Dec22/blob/main/img/miniature/miniature-P1-github.png?raw=true" alt="General introduction" width="410"/>](https://www.youtube.com/watch?v=Pj7qEJvDmA0 "General introduction") [<img src="https://github.com/annasmyk/Tsace_RJD_Webinar_Dec22/blob/main/img/miniature/miniature-P2-github.png?raw=true" alt="Seasonal adjustment in R with JD+" width="410"/>](https://www.youtube.com/watch?v=q86l0hn9AJA "Seasonal adjustment in R with JD+")
[<img src="https://github.com/annasmyk/Tsace_RJD_Webinar_Dec22/blob/main/img/miniature/miniature-P3-github.png?raw=true" alt="Wrangling Workspaces" width="410"/>](https://www.youtube.com/watch?v=Q4VDowqboGs "Wrangling Workspaces") [<img src="https://github.com/annasmyk/Tsace_RJD_Webinar_Dec22/blob/main/img/miniature/miniature-P4-github.png?raw=true" alt="Production in R" width="410"/>](https://www.youtube.com/watch?v=twegpbREQpI "Production in R")


## How to ask a question?

To ask a question, you can send us an email to Anna (anna.smyk@insee.fr) and me (tanguy.barthelemy@insee.fr) or complete an issue directly on GitHub.
To complete an issue on GitHub, you should:

1.Go to the *Issues* tab:

![plot](https://github.com/annasmyk/Tsace_RJD_Webinar_Dec22/blob/main/img/issue/issue_panel.png?raw=true)

2. Click on *New issue*:

![plot](https://github.com/annasmyk/Tsace_RJD_Webinar_Dec22/blob/main/img/issue/create_issue.png?raw=true)

3. Choose one of the themes proposed in the list and click on *Get started*:

![plot](https://github.com/annasmyk/Tsace_RJD_Webinar_Dec22/blob/main/img/issue/choose_issue.png?raw=true)

4. Fill the question with a title and a text to explain the problem or the request and click on *Submit new issue*:

![plot](https://github.com/annasmyk/Tsace_RJD_Webinar_Dec22/blob/main/img/issue/complete_issue.png?raw=true)


## Links to relevant GitHub pages

Here are the online open-source packages in version 2:

-   [**RJDemetra**](https://github.com/jdemetra/rjdemetra) on
    [CRAN](https://cran.r-project.org/web/packages/RJDemetra/index.html) or
    <https://github.com/jdemetra/rjdemetra>
-   [**rjdworkspace**](https://github.com/InseeFrLab/rjdworkspace) on
    <https://github.com/InseeFrLab/rjdworkspace>
-   [**JDCruncheR**](https://github.com/InseeFr/JDCruncheR) on
    <https://github.com/InseeFr/JDCruncheR>
    
And in version 3:

-   [**rjdemetra3**](https://github.com/palatej/rjdemetra3) on
<https://github.com/palatej/rjdemetra3>

-   [**rjd3toolkit**](https://github.com/palatej/rjd3toolkit) on
<https://github.com/palatej/rjd3toolkit>
-   [**rjd3modelling**](https://github.com/palatej/rjd3modelling) on
<https://github.com/palatej/rjd3modelling>
-   [**rjd3sa**](https://github.com/palatej/rjd3sa) on
<https://github.com/palatej/rjd3sa>
-   [**rjd3arima**](https://github.com/palatej/rjd3arima) on
<https://github.com/palatej/rjd3arima>
-   [**rjd3x13**](https://github.com/palatej/rjd3x13) on
<https://github.com/palatej/rjd3x13>
-   [**rjd3tramoseats**](https://github.com/palatej/rjd3tramoseats) on
<https://github.com/palatej/rjd3tramoseats>
-   [**rjd3sts**](https://github.com/palatej/rjd3sts) on
<https://github.com/palatej/rjd3sts>
-   [**rjd3stl**](https://github.com/palatej/rjd3stl) on
<https://github.com/palatej/rjd3stl>
-   [**rjd3highfreq**](https://github.com/palatej/rjd3highfreq) on
<https://github.com/palatej/rjd3highfreq>
-   [**rjd3bench**](https://github.com/palatej/rjd3bench) on
<https://github.com/palatej/rjd3bench>

-   [**ggdemetra3**](https://github.com/AQLT/ggdemetra3) on
<https://github.com/AQLT/ggdemetra3>

## Contact

[Anna SMYK](https://github.com/annasmyk) (Insee) - anna.smyk@insee.fr

[Tanguy BARTHELEMY](https://github.com/TanguyBarthelemy) (Insee) - tanguy.barthelemy@insee.fr
