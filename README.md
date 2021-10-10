# Self Driving Cars

## 💢 Index
* **[Module 1 : Taxonomy of driving](#-module-1--taxonomy-of-driving)**

  1. *[Important terms](#important-terms)*
  2. *[Perception requirements]()*
  3. *[Actions and driving decisions]()*

<!-- * **[Module 2]()** -->
<br>


## 💢 Module 1 : Taxonomy of driving

### 🉑 Important terms
1. **Driving task** : This consists of 3 subtasks. They are, 
    * perceiving the environment; 
    * planning route from point A to B; 
    * controlling the vehicle.

2. **Operational design domain (ODD)** : It defines the optimal operating conditions for a system. Like, roads, environment, etc. Needs to be planned carefully in advanced.

<br>

### 🉑 Classifying driving system automation
For the classification, some important things need to be considered. For example,
* How much DRIVER ATTENTION is needed?
* How much DRIVER ACTION is needed?
* What makes up a complete driving task?

<br>

### 🉑 Defining a driving task
* Firstly, we need a `LATERAL` control. In other words, steering and navigation on a road.<br>
* Next, we have `LONGITUDINAL` control. This refers to controlling the position and velocity of car on a road through acceleration or braking actions.<br>
* After this, we have `Object and Event Detection and Response (OEDR)`
