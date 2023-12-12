# NissanConnectEV-Homey
Unofficial integration of the NissanConnect EV cloud service for Athoms Homey Pro.
Disclaimer: This Homey app is in no way affiliated with either Nissan or Homey.

Please be aware that this app only works with Nissan vehicles from before may 2019. Newer vehicles will not work with this integration as they use a different cloud service.
This integration has been tested with a Nissan Leaf 2018 and is expected to work on all Nissan Leafs prior to may 2019, however no testing has been done on the 1st generation models. 

The integration currently offers:
* Sensors for the battery charge level, estimated range and charging status.

Planned development:
* Flow cards to start and stop the climate control.
* Flow card to start the charging of the car.
* Sensor for interior temperature.

*=NissanConnect EV was previously known as Nissan Carwings.

## Installation
Use the [Homey App Store]([https://homey.app/en-dk/apps/homey-pro/]) to install the app on your Homey Pro.

## Configuration Options
- Username **(REQUIRED)**  
The username associated with your official NissanConnect EV account.
- Password **(REQUIRED)**  
The password for your official NissanConnect EV account.
- Region **(REQUIRED)**  
The region where the NissanConnect EV account is registered. The following options are available:
    - Europe (NE)
    - USA (NNA)
    - Canada (NCI)
    - Australia (NMA)
    - Japan (NML)
- Update Interval in Minutes *(optional, default: 60 minutes)*  
The interval between updates if the climate control is off and the car is not charging.  
**NOTICE:** *Providing a low update interval will cause the service to refresh more frequently and can negatively impact your cars 12V battery.*
- Update Interval (charging) in Minutes *(optional, default: 15)*  
 The interval in minutes between updates if the car is charging.
- Update Interval (climate on) in Minutes *(optional, default: 5)*  
The interval in minutes between updates if the climate control has been switched on.

## Limitations
* The official NissanConnect EV cloud service (developed and maintained by Nissan) do not allow charging to be stopped remotely. By that limitation, this app is not able to do that either.
* Originally the official NissanConnect EV cloud service featured a "Car Location" function. This has sadly been deactivated and is no longer possible.

## Bug Reporting
* Nissan's servers are known to be really unstable. Please confirm that the official app for your vehicle is working before reporting bugs here. 

## Donations
TBA
