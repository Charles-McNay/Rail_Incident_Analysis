This readme is currently in process and may not be accurate.


# Railroad Freight Incident Analysis



##  ABOUT

The purpose of this project is to analyze the rate of incidents in the rail transported freight industry.

Freight train derailments are far more common than the general public is aware of and generally only gain media attention if the derailment affects a large number of people.[^1]

The Association of American Railroads claim that 99.9% of hazardous material reaches its destination without incident.[^2] 


- More than 3.1 billion tons of hazmat transported in the US every year.[^3] Over 80% of all hazmat shipments are by rail.[^4]
- There is no regulation for crew size on freight trains some non-Class I railroads have long operated with just one person in the locomotive cab.[^5] 
- In 1977 train crews consisted of 4 people[^6] 
- Freight trains averaged a lenght of less than 4000 feet in the late 1970's[^7]
- Today Freight trains average 6,800 feet[^8]
- A train can weigh anywhere from 8,818,490 lbs to 44,092,452 lbs or even more under some particular instances.[^9]

I will be looking into which Class 1 railroads are more incident prone, which state has more derailments, deaths caused by rail related incidents and the damage costs associated with these incidents.

**What I'm asking**

* Are railroads becoming more or less dangerous to us?
* Which Class 1 railroad has the most derailments? More fatalities? 
* How often do hazmat cars release material in incidents?
* Are larger trains more likely to derail?
* How many lives have been lost to rail incidents in the past 40 years?
* How much property damage has rail related incidents caused?

## SOURCE FOR DATASETS
The main dataset was pulled from the transportation.gov website[^10] on 02/15/2023 
The form the dataset was sourced from can be found ![HERE](images/Rail_Incident_report_form.pdf)



### Package Installations Required to Run this Code
All of the Libraries and Tools that used in this repo are included with Anaconda.
[Anaconda Installation](https://www.anaconda.com/products/distribution)
This project was completed using python 3.11

In your terminal enter:

```
pip install -U kaleido
python -m pip install -U pip
python -m pip install -U matplotlib
pip install pandas
```


   
Citations:
[^1]: [Train derailments are business as usual in the railroad industry](https://grist.org/accountability/train-derailments-business-usual-railroad-industry/).
[^2]: [Hazmat releases are inevitable, the AAR claims 99.9% success rate of transporting hazmat material but the .1% could destroy a entire ecosystem](https://www.aar.org/issue/freight-rail-hazmat-safety/)
[^3]: [800,000 hazmat shipments in the us every year](https://airseacontainers.com/blog/how-common-are-shipping-hazmat-spills/#:~:text=Millions%20of%20tons%20of%20hazardous,tons%20are%20transported%20each%20year.)
[^4]: [70% of rail transported hazmat is via tank car](https://www.firehouse.com/rescue/article/10545487/hazardous-materials-containers-part-2-railroad-cars)
[^5]: [some non-Class I railroads have long operated with just one person in the locomotive cab](https://www.aar.org/wp-content/uploads/2020/08/AAR-Crew-Size-Fact-Sheet.pdf)
[^6]: [the industry proposed elimination of work rules that require four crew members on most trains ](https://www.washingtonpost.com/archive/business/1977/07/09/railroad-union-leaders-urge-nationalization-of-industry/43ccd33d-5c47-4e62-b196-6155a2a64f11/)
[^7]: [Distributed-power units (DPUs) are extra locomotives that are placed between or behind freight cars on very long trains](https://www.popularmechanics.com/technology/infrastructure/a5314/4345689/)
[^8]: [evaluate the operation of trains longer than 7,500 feet](https://www.trains.com/trn/news-reviews/news-wire/railroads-use-of-long-trains-to-go-under-the-microscope/)
[^9]  [A train car weighs between 30-80 tons](https://www.trainconductorhq.com/how-much-does-a-train-weigh/)
[^10] [Transportation.gov](https://data.transportation.gov/Railroads/Rail-Equipment-Accident-Incident-Data/85tf-25kj)
