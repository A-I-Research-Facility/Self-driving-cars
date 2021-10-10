# Self Driving Cars

## 💢 Index
* **[Module 1 : Taxonomy of driving](#-module-1--taxonomy-of-driving)**

  1. *[Important terms](#important-terms)*
  2. *[Perception requirements]()*
  3. *[Actions and driving decisions]()*

<!-- * **[Module 2]()** -->
<br>


## 💢 Module 1 : Taxonomy of driving

### 🉑 Important terms and their definitions
1. **Driving task** : This consists of 3 subtasks. They are, 
    * perceiving the environment; 
    * planning route from point A to B; 
    * controlling the vehicle.

2. **Operational design domain (ODD)** : It defines the optimal operating conditions for a system. Like, roads, environment, etc. Needs to be planned carefully in advanced.

<br>

### 🉑 How to classify level of automation in driving systems?
In order to understand this, we need to answer the following questions :
* How much DRIVER ATTENTION is needed?
* How much DRIVER ACTION is needed?
* What makes up a complete driving task?

<br>

### 🉑 How do we define a driving task?
To define a driving task, we need some fundamental properties.
* Firstly, we have `LATERAL control`. In other words, steering and navigation on a road.<br>
* Next, we have `LONGITUDINAL control`. This refers to controlling the position and velocity of car on a road through acceleration or braking actions.<br>
* After this, we have `Object and Event Detection and Response (OEDR)`. This refers to detection and response of objects that immidiately affect the driving task. This is used in conjunction with specific ODD.
* Next, comes `Planning`. This refers to the selection of routes and deciding the lanes and crossings of movement.
* Finally, we have `Miscellaneous` tasks. These consist of actions like signalling using indicators, controlling the lights, etc.

<br>

### 🉑 Which questions will lead us to taxonomy for classifying level of automation?
We have already vaguely answered this. Formally, they are :
* Can system handle lateral control?
* Can system handle longitudinal control?
* Can system handle emergency responses?
* Is driver attention required in emergencies?
* Does the system have a limited ODD, or it can perform in all conditions?

<br>

### What are common levels of automation (defined by SAE Standard J3 016)?
* Level 0 : No automation
    * Everything done by driver

* Level 1 : Driving assistance
    * Either lateral, or, longitudunal control by system
    * Only one control, not both
    * Examples, 
        1. Adaptive cruise control - controls the speed by acceleration and braking
        2. Lane keeping assistance - controls steering to stop drift

* Level 2 : Partial driving automation
    * Both lateral, and longitudinal control by system
    * Examples,
        1. GM Super cruise
        2. Nissan ProPilot assist

* Level 3 : Conditional driving automation
    * In addition to level 2, system can perform some sort of OEDR
    * Controversial level of automation since it is not really possible for autonomy system to know that it is failing at the moment
    * The driver still needs to be attentive and be ready to take control of the car, however, the system will alert the driver
    * Example, Audi A8 can navigate unmonitored in slow traffic

* Level 4 : High driving automation
* In addition to level 3, 
