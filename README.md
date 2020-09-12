# NYCRestaurantData

Summer 2020 Humantites Research Project: Restaurant Owner Data Augmentation and Animation group

## Members:

- Sarah Tahir
- [Yi-Chen (Cinny) Lin](mailto: ycl461@nyu.edu)
- Yinqi Wang
- Yujie (Tracey) Lan
- Huanci (Mary) Wang

## Objectives

The group hopes to use resturant data from the late 19th century to early 20th century in Manhattan to draw insights about immigrant patterns during that period.

To achive this goal, we divided our work into smaller subgroups:

## Data Augmentation -- Sarah

Expanding our dataset by scraping from the web.

## Cleaning Nationality and Gender data -- Cinny, Mary, Yinqui

Using [API](https://v2.namsor.com), [Ancestry](https://www.ancestry.com), [IPUMS](http://ipums.org) results to determine the nationality and gender of restuarant owners.

## Typical Resturant Owners -- Yinqui, Tracey

Reading from various sources to support insights drawn by data.

## Mapping / Visualizing Data Results -- Cinny, Sarah

Using GIS and d3 to map resturant data based on nationality and gender, and visualize the final results with d3.

## [ipums](https://github.com/CinnyLin/NYCRestaurantData/tree/master/ipums)

This folder documents the attempt to check the validity of "nationality" data from [API](https://v2.namsor.com) results with [Ancestry](https://www.ancestry.com) data

[This notebook](https://github.com/CinnyLin/NYCRestaurantData/blob/master/ipums/ancestry.ipynb) is an example of cleaning nationality data in [1898_TrowBus.csv](https://github.com/CinnyLin/NYCRestaurantData/blob/master/ipums/1898TrowBus.csv) by cross checking nationality API results with Ancestry data (Ancestry_1910)

Other files in this folder are datasets extracted from [IPUMS](http://ipums.org) and attempts to decode those datasets.

## [mapping](https://github.com/CinnyLin/NYCRestaurantData/tree/master/mapping)

This folder shows the first draft of mapping restaurant data. The results were restaurant data of 9 nationalities (Chinese, French, German, Irish, Italian, Jewish, Polish, Russian, Spanish) from 3 time periods (1898, 1913, 2020) mapped in three separate Google Maps ([C-G](https://www.google.com/maps/d/edit?mid=1PFrfCr8KN_E1bWocsUiybxfq11Zbs78M&usp=sharing), [I-J](https://www.google.com/maps/d/edit?mid=1opZ0dKMtm1kpTYMN0ObGTQWiFt1jCDBZ&usp=sharing), [P-S](https://www.google.com/maps/d/edit?mid=1p7Xs9x1QeVIP-LyQsHSvK8M3nEMVazxq&usp=sharing)).
