# Official Requirements Document

Authors:Blanda Marco,El Boustani Omar,Etemaji Akil,Faoro Nicolò

Date: 17/06/2019

Version: 1




# Contents
- [Abstract](#abstract)
- [Stakeholders](#stakeholders)
- [Context Diagram and interfaces](#context-diagram-and-interfaces)
	+ [Context Diagram](#context-diagram)
	+ [Interfaces](#interfaces) 
	
- [Stories and personas](#stories-and-personas)
- [Functional and non functional requirements](#functional-and-non-functional-requirements)
	+ [Functional Requirements](#functional-requirements)
	+ [Non functional requirements](#non-functional-requirements)
- [Use case diagram and use cases](#use-case-diagram-and-use-cases)
	+ [Use case diagram](#use-case-diagram)
	+ [Use cases](#use-cases)
	+ [Relevant scenarios](#relevant-scenarios)


# Abstract

Some students of aeronautic is not so god and ready to fly with real airplane.The teacher decide to emprouve his skills with the unespectable experience.

# Stakeholders

|  | Description | 
| ----------------- |:-----------:|
| Administrator     |Uses the program to improve his skills| 


# Context Diagram and interfaces



## Interfaces
| Actor | Logical Interface | Physical Interface  |
| ------------- |:-------------:| -----:|
|Administrator|GUI |Screen, keyboard|


# Stories and personas
John is a student of aeronautics. His notes are not the best and for this reason The  teacher is hungry. 
Jhon would like to fly the plane,but his teacher disagrees.
Jhon for improuve his abilities decide to ask for help at Mobarog Team with her fly experience.
After 2 weeks Jhon is the first student of the school. 

# Functional and non functional requirements

## Functional Requirements

| ID        | Description  |
| ------------- |:-------------:| 
|  FR1     | Record that the health of collegue is good |  
|  FR2     | After the fly whait 2 minutes to move |

## Non Functional Requirements

| ID        | Type (efficiency, reliability, .. see iso 9126)           | Description  | Refers to |
| ------------- |:-------------:| :-----:| -----:|
|  NFR1     | Usability | Application should be used with no training by all peoples | All FR |
|  NFR2     | Performance | All functions should complete in < 0.5 sec  | All FR |
|  NFR3     | Portability | The application runs on MS Windows (7 and more recent)  | All FR |
|  NFR4     | Portability | The application (functions and data) should be portable from a PC to another PC in less than 5 minutes | All FR |


# Use case diagram and use cases

## Use case diagram

```plantuml
left to right direction
actor Administrator as a
a -- (FR1  Record usage of capsules by colleague)
a -- (FR2 Record usage of capsules by visitor)
a -- (FR3 Record recharge of account of colleague)
a -- (FR4 Record purchase of capsules)
a -- (FR5 Produce report on consumption of colleague)
a -- (FR6 Produce report on all consumptions)
```
## Use Cases

### Use case 1, UC1 - FR1  Record usage of capsules by colleague

| Actors Involved        | Administrator |
| ------------- |:-------------:| 
|  Precondition     |the unreal man pass a dor|  
|  Post condition     | The level start|
|  Nominal Scenario     | Administrator select the plane |


# Relevant scenarios

## Scenario 1

| Scenario ID: SC1        | Corresponds to UC1  |
| ------------- |:-------------| 
| Description | Collegue enter in the first door,he can fly in canyon |


## Scenario 2

| Scenario ID: SC2        | Corresponds to UC1  |
| ------------- |:-------------| 
| Description | Colleague enter in the second door,he can fly in mountain|

## Scenario 

| Scenario ID: SC3        | Corresponds to UC1  |
| ------------- |:-------------| 
| Description | Colleague enter in the third door,he can fly in a city|



# System Design
In this case personal computer and visor.
