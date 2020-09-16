## [nationalityAPI_1913](https://github.com/CinnyLin/NYCRestaurantData/tree/master/nationalityAPI_1913) -- Cinny, Mary

This folder shows the process of using API to get nationality results.

### [1913TrowBus.csv](https://github.com/CinnyLin/NYCRestaurantData/blob/master/nationalityAPI_1913/1913TrowBus.csv)

This is the [1913TrowBus.csv](https://github.com/CinnyLin/NYCRestaurantData/blob/master/nationalityAPI_1913/1913TrowBus.csv) that we are getting nationality data for.

### [API reference notebook](https://github.com/CinnyLin/NYCRestaurantData/blob/master/nationalityAPI_1913/API.ipynb)

This is the reference notebook on how to get API results.

### all notebooks

Because the API only allowed 500 nationality results each time, we had to create multiple accounts to get all the results.

- [APInationality500](https://github.com/CinnyLin/NYCRestaurantData/blob/master/nationalityAPI_1913/APInationality500.ipynb)
- [APInationality1000](https://github.com/CinnyLin/NYCRestaurantData/blob/master/nationalityAPI_1913/APInationality1000.ipynb)
- [APInationality1500](https://github.com/CinnyLin/NYCRestaurantData/blob/master/nationalityAPI_1913/APInationality1500.ipynb)
- [APInationality2000](https://github.com/CinnyLin/NYCRestaurantData/blob/master/nationalityAPI_1913/APInationality2000.ipynb)
- [APInationality2500](https://github.com/CinnyLin/NYCRestaurantData/blob/master/nationalityAPI_1913/APInationality2500.ipynb)
- [APInationality3000](https://github.com/CinnyLin/NYCRestaurantData/blob/master/nationalityAPI_1913/APInationality3000.ipynb)
- [APInationality3500](https://github.com/CinnyLin/NYCRestaurantData/blob/master/nationalityAPI_1913/APInationality3500.ipynb)
- [APInationality4000](https://github.com/CinnyLin/NYCRestaurantData/blob/master/nationalityAPI_1913/APInationality4000.ipynb)
- [APInationality4500](https://github.com/CinnyLin/NYCRestaurantData/blob/master/nationalityAPI_1913/APInationality4500.ipynb)
- [APInationality5000](https://github.com/CinnyLin/NYCRestaurantData/blob/master/nationalityAPI_1913/APInationality5000.ipynb)
- [APInationality5500](https://github.com/CinnyLin/NYCRestaurantData/blob/master/nationalityAPI_1913/APInationality5500.ipynb)

### [api_results](https://github.com/CinnyLin/NYCRestaurantData/tree/master/nationalityAPI_1913/api_results)

This folder are text files that saved the API results once its ran so that we don't have to rerun the API everytime we need a certain result.

### [1913 Final](https://github.com/CinnyLin/NYCRestaurantData/tree/master/nationalityAPI_1913/1913 Final)

This csv is the final result for 1913 data. Starting from row 3345, almost all names are not complete names such as “Bridge” or “Carlos”, theatres, restaurant names that does not contain people’s names and even street names such as “Broadway”. Starting from row 3291, there is no data in nationality final column which means that no more ancestry data were filled. Therefore, only rows before 3291 are useable and below are the results of 3291 entries. 
- Countries match (if any 2 results out of 3 sources match): 1300 (39.5%)
- Regions match: 758 (23%)
- Totally, 62.5% people’s nationality was determined. 

Among all the not matched entries, 299 have name errors, meaning that the name is either restaurant name, corporation name or not a full name. 
Among 299 names, we tried to extract useable last names and used census data’s prediction result. However, these result hardly match ancestry result, and we cannot use API’s result as a reference in this case since there is no full name for the API to run correctly. Thus, there is space of improvement for these 299 names. 
689 people’s nationality were unknown because the three results simply don’t match (neither region nor country). One possible solution is to include parents’ nationality from census data, but we haven’t got time to achieve this. 

