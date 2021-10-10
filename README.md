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

### 🉑 Which questions will lead us to taxonomy for classifying level of automation
We have already vaguely answered this. Formally, they are :
* Can system handle lateral control?
* Can system handle longitudinal control?
* Can system handle emergency responses?
