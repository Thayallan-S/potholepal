# potholepal
Pothole Detecting Robot - UofTHacks VI

<p align="center">
  </br>
  <img src="https://i.imgur.com/AtI0mDD.jpg"/>
</p>

This repo is meant to enable the Pothole Pal proof of concept (POC) to detect changes in elevation on the road using an ultrasonic sensor thereby detecting potholes. This POC is to demonstrate the ability for a car or autonomous vehicle to drive over a surface and detect potholes in the real world. 

Table of Contents

1.Purpose

2.Goals

3.Implementation

4.Future Prospects


1.Purpose

By analyzing city data and determining which aspects of city infrastructure could be improved, potholes stood out. Ever since cities started to grow and expand, potholes have plagued everyone that used the roads. In Canada, 15.4% of Quebec roads are very poor according to StatsCan in 2018. In Toronto, 244,425 potholes were filled just in 2018. Damages due to potholes averaged $377 per car per year. There is a problem that can be better addressed. In order to do that, we decided that utilizing Internet of Things (IoT) sensors like the ulstrasound sensor, we can detect potholes using modern cars already mounted with the equipment, or mount the equipment on our own vehicles.

2.Goals

The goal of the Pothole Pal is to help detect potholes and immediately notify those in command with the analytics. These analytics can help decision makers allocate funds and resources accordingly in order to quickly respond to infrastructure needs. We want to assist municipalities such as the City of Toronto and the City of Montreal as they both spend millions each year assessing and fixing potholes. The Pothole Pal helps reduce costs by detecting potholes immediately, and informing the city where the pothole is. 

3.Implementation

We integrated an arduino on a RedBot Inventors Kit car. By attaching an ultrasound sensor module to the arduino and mounting it to the front of the vehicle, we are able to detect changes in elevation AKA detect potholes. After the detection, the geotag of the pothole and an image of the pothole is sent to a mosquito broker, which then directs the data to an iOS app which a government worker can view. They can then use that information to go and fix the pothole. 
<p align="center">
  </br>
  <img src="https://i.imgur.com/Lv1A5xf.png"/>
  <img src="https://i.imgur.com/4DD3Xuc.png"/>
</p>

4.Future Prospects

This system can be further improved on in the future, through a multitude of different methods. This system could be added to mass produced cars that already come equipped with ultrasonic sensors, as well as cameras that can send the data to the cloud for cities to analyze and use. This technology could also be used to not only detect potholes, but continously moniter road conditions and providing cities with analytics to create better solutions for road quality, reduce costs to the city to repair the roads and reduce damages to cars on the road.

