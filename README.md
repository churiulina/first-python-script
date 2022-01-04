# python-scripts

### Author:
<p align="justify">
A. Churiulina</sup>

<em><strong>Correspondence to: A. Churiulina (agchurylina@gmail.com)</strong></em>

## The repository description:
<p align="justify">
  The repository contains Python projects created during training on the course "Data Analyst" by the <a href="https://practicum.yandex.ru/">Yandex.Practicum</a> from October 2021 to the present.    
</p>

## The repository content:
1. First ***Python*** project: **Determination of a promising tariff for a telecom company** ([Mobile tariffs.ipynb][project_1]). Customers of Megaline, a federal mobile operator, are offered two tariff plans: Smart and Ultra. In order to adjust the advertising budget, the commercial department wants to understand which tariff brings the most money. A preliminary analysis of tariffs was made for a small sample of customers - data from 500 Megaline users: who they are, where they are from, what tariff they use, how many calls and messages each sent in 2018. The behavior of customers was analyzed and a conclusion was made - which tariff is better.
    * What has been done:
        + Opened the data files and studied the general information.
        + Converted the data to the required types.
        + Found and corrected data errors, where it was necessary.
        + Calculated for each user: the number of calls, sent messages, the volume of consumed Internet traffic by months.
        + Calculated monthly revenue from each user.
        + Described the behavior of the operator's customers based on the sample.
        + Calculated the mean, variance, and standard deviation.
        + Ploted histograms.
        + Described the probability distributions.
        + Tested null and alternative hypotheses.
        + Written a general conclusion.
     * [Files used in this project you can download here][files_1]

2. Second ***Python*** project: **Revealing the regularities of the success of a computer game** ([Computer_games.ipynb][project_2]). The online store "Stremchik" sells computer games all over the world. Historical data on game sales, user and expert ratings, genres and platforms (for example, Xbox or PlayStation) are available from open sources. The regularities determining the success of the game are revealed. This made it possible to place a bet on a potentially popular product and plan advertising campaigns. Data is available up to 2016. Let's say it's December 2016, and you've presented a campaign plan for 2017. The principle of working with data has been worked out. The dataset comes across the abbreviation ESRB (Entertainment Software Rating Board) - an association that determines the age rating of computer games.
    * What has been done:
        + Opened the data files and studied the general information.
        + Replaced the column names (converted to lower case).
        + Converted the data to the required types.
        + Processed gaps, where it was necessary.
        + Counted the total sales in all regions.
        + Selected the platforms with the highest total sales and ploted the distribution by year.
        + Determined the actual period as a result of researching the previous questions.
        + Choosen a few potentially profitable platforms.
        + Ploted a box and mustached a graph of global game sales by platform.
        + Described how user and critical reviews affect sales within one popular platform, calculated the correlation between scores and sales.
        + Created a portrait of the user of each region (the most popular platforms, genres).
        + Tested null and alternative hypotheses.
        + Written a general conclusion.
     * [File used in this project you can download here][file_2]
         
      
         
         
         
[yandex]: https://practicum.yandex.ru/
[files_1]: https://github.com/churiulina/first-python-script/tree/main/files_mobile_tariffs
[project_1]: https://github.com/churiulina/first-python-script/blob/main/Mobile_tariffs.ipynb
[file_2]: https://github.com/churiulina/first-python-script/blob/main/games.csv   
[project_2]: https://github.com/churiulina/first-python-script/blob/main/Computer_games.ipynb
