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
- The url for getting the basic profile of the cricketer is http://drexel123.pythonanywhere.com/cricketer_details?name={ Some name of the cricketer }.
The parameters to be passed is *"name"*

Ex:- http://drexel123.pythonanywhere.com/cricketer_details?name=dhoni

- This link also accepts text like "India vs pakistan 2nd T2o match in 2022" or "India vs England 2022 ICC world cup semi finals" 
Ex:- https://drexel123.pythonanywhere.com/cricketer_details?text=india%20vs%20england%20icc%20t20%20worldcup%20semi%20finals

### Getting Full Career of a Cricketer
- The url for getting the full career of a cricketer is http://drexel123.pythonanywhere.com/cricketer_fcareer?name={ Some name of the cricketer }&required=' list of required statistics '.
The parameters to be passed is *"name and required"*
- Here is name is the name of the cricketer and the required field is the list of all the career statistics you needd for a particular crickert. This list will vary based on the cricketer you can check the availabel links of any cricketer in the ESPNcricinfo website. For example teh list of all teh required career statistics of MS Dhoni will available at https://www.espncricinfo.com/player/ms-dhoni-28081/bowling-batting-stats. User can pass any number available headings from this page. If the required field is all then the API will extract all the availble heading that are present in the stats page of any player.

Ex:- http://drexel123.pythonanywhere.com/cricketer_fcareer?name=dhoni&required=all.

