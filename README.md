# BusCatcher
## Authors
	* Chenning Zhang
## Purpose
	BusCatcher helps people find when is the next bus(or bart) coming. Moreover, it let the user know how fast he should walk/run in order to catch the bus.
## Features
	* Ability for the user to select a bus(or bart) which he wants to get information about.
	* Ability for the user to select a bus(or bart) stop which he will take the bus(or bart) at.
	* Ability to see when is the next user-selected bus(or bart) coming.
	* Ability to track user's current walking speed as he walks/runs.
	* Ability to see how long will the user reach the station according to his current speed.
## Control Flow
	* Users are initially presented with a screen that let them enter which bus(or bart) they are going to take, as well as the stop that they want to take the bus/bart.
	* After users made their selection, if they are currenly moving, the screen will show how much more time will be needed until they reach the stop according to their current speeds.
	* If users are not moving, the screen will show when is the next bus/bart of users' selections coming.
	* When the users reached the bus stop, the screen will show up a message saying "You have reached at the bus stop. The next bus is coming in xx minutes."
## Implementation
### Model
	* AppDelegate.swift
	* NextBus.swift
### View
	* UserInputView
	* NextBusView
	* TimeRemainingView
	* ArrivedView
### Controller
	* UserInputViewController
	* NextBusViewController
	* TimeRemainingViewController
	* ArrivedViewController