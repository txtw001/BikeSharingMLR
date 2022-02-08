# BikeSharingMLR
> Bike sharing analysis wiht Multiple Linear Regresson


## Table of Contents
* [General Info](#general-information)
* [Dataset](#dataset)
* [Dataset characteristics](#dataset-characteristics)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Contact](#contact)
* [License](#license)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Programming assignment wherein a multiple linear regression model is built for the prediction of demand for shared bikes.
- A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free.
- A US bike-sharing provider has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends.
- Which variables are significant in predicting the demand for shared bikes?
- How well those variables describe the bike demands?

## Dataset
Use of this dataset in publications must be cited to the following publication:

[1] Fanaee-T, Hadi, and Gama, Joao, "Event labeling combining ensemble detectors and background knowledge", Progress in Artificial Intelligence (2013): pp. 1-15, Springer Berlin Heidelberg, doi:10.1007/s13748-013-0040-3.

@article{
	year={2013},
	issn={2192-6352},
	journal={Progress in Artificial Intelligence},
	doi={10.1007/s13748-013-0040-3},
	title={Event labeling combining ensemble detectors and background knowledge},
	url={http://dx.doi.org/10.1007/s13748-013-0040-3},
	publisher={Springer Berlin Heidelberg},
	keywords={Event labeling; Event detection; Ensemble learning; Background knowledge},
	author={Fanaee-T, Hadi and Gama, Joao},
	pages={1-15}
}
	
For further information about this dataset please contact Hadi Fanaee-T (hadi.fanaee@fe.up.pt)

## Dataset characteristics
- instant: record index
- dteday : date
- season : season (1:spring, 2:summer, 3:fall, 4:winter)
- yr : year (0: 2018, 1:2019)
- mnth : month ( 1 to 12)
- holiday : weather day is a holiday or not (extracted from http://dchr.dc.gov/page/holiday-schedule)
- weekday : day of the week
- workingday : if day is neither weekend nor holiday is 1, otherwise is 0.
+ weathersit : 
	- 1: Clear, Few clouds, Partly cloudy, Partly cloudy
	- 2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
	- 3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
	- 4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
- temp : temperature in Celsius
- atemp: feeling temperature in Celsius
- hum: humidity
- windspeed: wind speed
- casual: count of casual users
- registered: count of registered users
- cnt: count of total rental bikes including both casual and registered

## Conclusions
- Temperature has a positive effet while rain has a strong negative effect on the bike rentals
- In spring a drop expected in the rental numbers
- Wind also affect rentals negativelly
- It is clear that bike rental becomes more and more popular.

## Technologies Used
- library - version 1.0
- library - version 2.0
- library - version 3.0

## Contact
Created by [@txtw001] - feel free to contact me!

## License
This project is open source and available under the MIT License - see LICENSE file for details

<!-- You don't have to include all sections - just the one's relevant to your project -->