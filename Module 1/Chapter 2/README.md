# Chapter 2 : Requirements for perception

In this chapter, we will analyze how a driving task is performed. We will understand the meaning of perception, its goals, the neccessary requirements, and the challenges faced.

A driving task can be further divided into 2 sub-tasks :
* analysis of motion and environment (perception)
* driving decision, including route planning, maneuver, etc. (planning)

<br>

## 🥬 What is perception?
Simply defined, the task of identifying and analyzing an object and its motion, in the environment is called perception. It is a neccessity, in order to make sense of the environment.

Perception is required to make informed decisions.

<br>

## 🥬 Goals for perception
These are the various elements that we need to be able to verify for the perception task.

First, are the static objects, example :
* markings on roads
* traffic signals
* curbs (off-road objects that define our road)
* road signs
* obstructions (like construction signs, or orange cones, etc.)
<br>
   
Then, there are dynamic elements. We need to predict the motion of these elements in order to make informed driving decision. Example :
* other vehicles on road (4 wheelers, 2 wheelers, etc.)
* pedestrians
<br>

Another goal of perception is EGO localization. This means that we should be able to estimate our position, and how(direction, velocity, acceleration) we are moving at any given point of time.

<br>

## 🥬 Challenges faced in perception
* Even though detection, and segmentation of objects is done with advanced machine learning methods, their reliability cannot be 100% guaranteed. In fact, it is far from what humans can do.
* A huge amount of training data is required for machine learning models. And processing this data before feeding it to the model, is a very expensive and time consuming task. Unfortunately, it cannot be done with machines.
* Hardware failure is a big issue. A malfunctioning sensor can have devastating consequenses.
* Apart from hardware failure, environmental conditions like rain, fog, reflections, lens flare, tunnels, etc., can also hinder with the sensory readings. Accomodation of these sensory uncertainities is quite challenging, but extremely crucial.

<br/>
<div align="center">
   <a href="https://github.com/A-I-Research-Facility/Self-driving-cars/tree/main/Module%201/Chapter%201#-chapter-1--taxonomy-of-driving"><< Prev &nbsp;&nbsp;</a>,
   <a href="#">&nbsp;&nbsp;Next >></a>
</div>
<br/>
