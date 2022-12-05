# **CricketAPI**

This is an API to retrieve data regarding cricket players and their performances from ESPNCricinfo website.

## **Table of content**
- Introduction
- Features
- Tools and Softwares used
- API Documentation
- Conclusion
- Contributors

## **Introduction**
- Fantasy Sports is a fast-growing industry and has a large consumer base.
- We have developed an API to retrieve data regarding cricket players and their performances.
- The data returned would enable the user to develop in-depth performance analysis of a player or an entire on various permutations and combinations.
- Using our domain knowledge of cricket, we converted some of the raw data points into features that could be readily understood by the user.


## **Features**
By using the API someone can extract the following data from ESPN Crcicinfo website

- Basic Profile of the Cricketer
- Detailed Career details of a cricketer
- Ball By Ball analysis for any match
- Images of the cricketer



## **Tools and Softwares used**
- Flask
- Beautiful Soup
- Selenium
- Regex
- PythonAnyWhere (web hosting service)

## **API Documentation**
- The main link for accessing our API is "http://drexel123.pythonanywhere.com/"
### Getting Cricketer Basic profile information
- The url for getting the basic profile of the cricketer is http://drexel123.pythonanywhere.com/cricketer_details?name={Some name}.
The parameters to be passed is *"name"*

Ex:- http://drexel123.pythonanywhere.com/cricketer_details?name=dhoni

