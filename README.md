# NissanConnectEV-Homey
Integration of NissanConnect EV service for the Homey Pro models.

The NissanConnect EV app offers integration with the NissanConnect EV cloud service*. 

Please be aware that this app only works with Nissan vehicles from before may 2019. Newer vehicles will not work with this integration as they use a different cloud service.
This integration has been tested with a Nissan Leaf 2018 and is expected to work on all Nissan Leafs prior to may 2019, however no testing has been done on the 1st generation models. 

The integration offers:
* Sensors for the battery status, range and charging status.

Planned development:
* Flow cards to start and stop the climate control.
* Flow card to start the charging of the car.
* Sensor for interior temperature

*=NissanConnect EV was previously known as Nissan Carwings.

## Installation
Use the [Homey App Store]([https://homey.app/en-dk/apps/homey-pro/]) to install the app on your Homey Pro.

## Configuration Options
Username **(REQUIRED)**  
The username associated with your official NissanConnect EV account.

Password **(REQUIRED)**  
The password for your official NissanConnect EV account.

Region **(REQUIRED)**  
The region where the NissanConnect EV account is registered. Should be one of the following, NE (for Europe), NNA (USA), NCI (Canada), NMA (Australia), NML (Japan).

Update Interval in Minutes *(optional, default: 60 minutes)*  
The interval between updates if the climate control is off and the car is not charging.  
**NOTICE:** *Providing a low update interval will cause the service to refresh more frequently and can negatively impact your cars 12V battery.*

Update Interval (charging) in Minutes *(optional, default: 15)*  
The interval in minutes between updates if the car is charging.

Update Interval (climate on) in Minutes *(optional, default: 5)*  
The interval in minutes between updates if the climate control has been switched on.

## Limitations
* The NissanConnect EV cloud service (created by Nissan) do not allow charging to be stopped remotely.

## Bug Reporting
* Nissan's servers are known to be really unstable. Please confirm that the official app for your vechile is working before reporting bugs here. 

## Donations
TBA
