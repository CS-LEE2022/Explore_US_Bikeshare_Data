## Explore US Bikeshare Data


[![](https://img.shields.io/badge/linkedin-@Shilin_Li-orange.svg?colorA=abcdef&logo=data:image/jpeg;base64,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)](https://www.linkedin.com/in/shilin-li-40474777/)


### Introduction


Over the past decade, bicycle-sharing systems have been growing in number and popularity in cities across the world. Bicycle-sharing systems allow users to rent bicycles for short trips, typically 30 minutes or less. Thanks to the rise in information technologies, it is easy for a user of the system to access a dock within the system to unlock or return bicycles. These technologies also provide a wealth of data that can be used to explore how these bike-sharing systems are used.


In this project, we will focus on the record of individual trips taken in 2016 from our selected cities: New York City, Chicago, and Washington, DC. Each of these cities has a page where we can freely download the trip data.:


- New York City (Citi Bike): [Link](https://www.citibikenyc.com/system-data)
- Chicago (Divvy): [Link](https://www.divvybikes.com/system-data)
- Washington, DC (Capital Bikeshare): [Link](https://www.capitalbikeshare.com/system-data)


If you visit these pages, you will notice that each city has a different way of delivering its data. Chicago updates with new data twice a year, Washington DC is quarterly, and New York City is monthly.


![alt text](https://images.pexels.com/photos/34646/pexels-photo.jpg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940)


(Image is from a copyright-free website: https://www.pexels.com/royalty-free-images/.)


| Table of Contents |
| :--- |
| <a href='#Prerequisites'> Prerequisites </a> 🔍📜 | 
| <a href='#Design'> Design </a>  📐 |
| <a href='#Conclusions'> Conclusions </a>  📌 |
| <a href='#License'> License </a> 🔖 |


<a id='Prerequisites'></a>

### Prerequisites


![](https://img.shields.io/badge/platform-ios-green.svg?colorA=abcdef)


- Python 3.6.3
- Jupyter Notebook
- Anaconda-Navigator


<a id='Design'></a>

### Design


![](https://img.shields.io/badge/language-Python-orange.svg)


- **_Exploratory analysis_**


    - Data is provided by Motivate, a bike-share system provider for many major cities in the United States. I will compare the system usage between three large cities: New York City, Chicago, and Washington, DC;
    
    - Compare the system usage between three large cities: New York City, Chicago, and Washington, DC;
    
    - Examine if there are any differences within each system for those users that are registered, regular users and those users that are short-term, casual users.
    

- **_Visualization_**


    - In this project, Python is the main tool used to explore data related to bikeshare systems for three major bikeshare systems in the United States as well as perform data wrangling to unify the format of data from the three systems and write code to compute descriptive statistics. External packages beyond Python library are introduced to help visualizing the data.
    
    
    <a id='Conclusions'></a>

### Conclusions


We have done quite a lot of profound analysis based on such a limited set of data, however, there are also a lot of potential analyses that could be performed on the data which are not possible with only the data provided. For example, detailed location data have not been investigated. Where are the most commonly used docks? What are the most common routes? As another example, the weather has potential to have a large impact on daily ridership. How much is ridership impacted when there is rain or snow? Are subscribers or customers affected more by changes in weather?


We can also apply this technique to medical information processing or drug development field, such as management of health data and medical records, estimating the effects of one drug over another or placebo as well as evaluating its toxicity. More important, nowadays computer based drug design is developing rapidly, that machine learning based on substantial clinical data plays an increasing important role in the design of new drug.


<a id='License'></a>

## License 


[![MIT Licence](https://badges.frapsoft.com/os/mit/mit.svg?v=103)](https://github.com/Shilin0806/Explore_US_Bikeshare_Data/blob/master/LICENSE)
