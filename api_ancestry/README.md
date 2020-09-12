## [api_ancestry](https://github.com/CinnyLin/NYCRestaurantData/tree/master/api_ancestry) -- Cinny

This folder shows how we assessed the validity of API's nationality results by cross-checking with Ancestry data. This folder focuses on 1913 dataset.

### [1913TrowBus_nationalityAPI.csv](https://github.com/CinnyLin/NYCRestaurantData/blob/master/api_ancestry/1913TrowBus_nationalityAPI.csv)

This is the 1913 resturant dataset that we aim to clean.

### [crossCheckAPI notebook](https://github.com/CinnyLin/NYCRestaurantData/blob/master/api_ancestry/crossCheckAPI.ipynb)

This [crossCheckAPI notebook](https://github.com/CinnyLin/NYCRestaurantData/blob/master/api_ancestry/crossCheckAPI.ipynb) is the source code to check the validity fo API results by seeing what the according Ancestry results were for each ethnic cluster.

### [crossCheckAncestry notebook](https://github.com/CinnyLin/NYCRestaurantData/blob/master/api_ancestry/crossCheckAncestry.ipynb)

This [crossCheckAncestry notebook](https://github.com/CinnyLin/NYCRestaurantData/blob/master/api_ancestry/crossCheckAncestry.ipynb) is the source code to see the Ancestry results for each ethnic cluster and its corresponding API results.

### [plots](https://github.com/CinnyLin/NYCRestaurantData/tree/master/api_ancestry/plots)

This is the cross-check results visaulized.

For example, `"French API in Ancestry Results.png"` shows what values show up API results when Ancestry results is French, and vice versa for `"French Ancestry in API Results.png"`.
![*French* API in Ancestry Results.png](https://github.com/CinnyLin/NYCRestaurantData/blob/master/api_ancestry/plots/*French*%20API%20in%20Ancestry%20Results.png)
![*French* Ancestry in API Results.png](https://github.com/CinnyLin/NYCRestaurantData/blob/master/api_ancestry/plots/*French*%20Ancestry%20in%20API%20Results.png)
