# Chapter 1 : Taxonomy of Driving
## 🥬 Important terms and their definitions :-<br>
1. **Driving task** : This consists of 3 subtasks. They are, 
    * perceiving the environment; 
    * planning route from point A to B; 
    * controlling the vehicle.

2. **Operational design domain (ODD)** : It defines the optimal operating conditions for a system. Like, roads, environment, etc. Needs to be planned carefully in advanced.

<br>
<br>

## 🥬 How to classify level of automation in driving systems?<br>

In order to understand this, we need to answer the following questions :
* How much DRIVER ATTENTION is needed?
* How much DRIVER ACTION is needed?
* What makes up a complete driving task?

<br>
<br>

## 🥬 How do we define a driving task?<br>

To define a driving task, we need some fundamental properties.
* Firstly, we have `LATERAL control`. In other words, steering and navigation on a road.<br>
* Next, we have `LONGITUDINAL control`. This refers to controlling the position and velocity of car on a road through acceleration or braking actions.<br>
* After this, we have `Object and Event Detection and Response (OEDR)`. This refers to detection and response of objects that immidiately affect the driving task. This is used in conjunction with specific ODD.
* Next, comes `Planning`. This refers to the selection of routes and deciding the lanes and crossings of movement.
* Finally, we have `Miscellaneous` tasks. These consist of actions like signalling using indicators, controlling the lights, etc.

<br>
<br>

## 🥬 Which questions will lead us to taxonomy for classifying level of automation?<br>

We have already vaguely answered this. Formally, they are :
* Can system handle lateral control?
* Can system handle longitudinal control?
* Can system handle emergency responses?
* Is driver attention required in emergencies?
* Does the system have a limited ODD, or it can perform in all conditions?

<br>
<br>

## 🥬 What are common levels of automation (defined by SAE Standard J3 016)?<br>

SAE : Society of Automotive Engineers

🔹 **Level 0 : No automation**
* Everything done by driver
<br>

🔹 **Level 1 : Driving assistance**
* Either lateral, or, longitudinal control by system
* Only one control, not both
* Examples, 
        1. Adaptive cruise control - controls the speed by acceleration and braking
        2. Lane keeping assistance - controls steering to stop drift
<br>

🔹 **Level 2 : Partial driving automation**
* Both lateral, and longitudinal control by system
* Examples,
        1. GM Super cruise
        2. Nissan ProPilot assist
<br>

🔹 **Level 3 : Conditional driving automation**
* In addition to level 2, system can perform some sort of OEDR (Object and Event Detection and Response)
* Controversial level of automation since it is not really possible for autonomy system to know that it is failing at the moment
* The driver still needs to be attentive and be ready to take control of the car, however, the system will alert the driver
* Example, Audi A8 can navigate unmonitored in slow traffic
<br>

🔹 **Level 4 : High driving automation**
* In this level, the system is capable of reaching a minimum risk condition in case the driver doesn't intervenes in time of emergency.
* This level of system can handle emergency on its own, but might ask the driver to take over to avoid an uneccassary stop on the road.
* The driver can check their phones or engage in other activities
* This level of automation is still only possible in limited ODD
* Example, vehiclces deployed by Waymo for public transport
<br>

🔹 **Level 5 : Fully autonomous driving**
* Add unlimited ODD to level 4, and we have the highest level of automation in driving systems

<br>
<br>

## 🥬 What are the limitations of this taxonomy?<br>

* Levels of autonomy are a course measure, i.e., 2 different car models claiming the same level can have very different capabilities
* ODD is very important
* Safety of driver, passenger, and everybody and everything else on the road is the most important

<br>
<br>

## 🥬 Addtional Reading<br>

* [SAE J3016: Taxonomy and Definitions Document](https://www.sae.org/standards/content/j3016_201806/)
* [SAE's website](https://www.sae.org/)

<br/>
<div align="center">
<a href="https://github.com/A-I-Research-Facility/Self-driving-cars/blob/main/Module%201/Chapter%202/README.md#-chapter-2--requirements-for-perception">Next >></a>
</div>
<br/>
