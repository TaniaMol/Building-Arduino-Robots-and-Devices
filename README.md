# Traffic Light
(Week 1):

Wiring:

<img width="770" alt="screenshot 2017-02-13 09 12 14" src="https://cloud.githubusercontent.com/assets/22894897/22891611/2c9dab42-f1cd-11e6-829d-225f646ee905.png">

Simulator: https://circuits.io/circuits/3642162-semaforo-arduino

![semaforo](https://cloud.githubusercontent.com/assets/22894897/22892687/acc32664-f1d0-11e6-973f-0ef7ccfbf4c6.gif)


# Ava's Traffic Intersection
(Week 4):

<img width="763" alt="screenshot 2017-02-10 10 54 37" src="https://cloud.githubusercontent.com/assets/22894897/22837781/5c92b02c-ef7f-11e6-998d-dff554c80a3c.png">

Instructions:

Vehicle circulation can be blocked by the barrier if the train appears or the pedestrian presses the button for the green light.

The green light button is activated if there is no train approaching, and enough time (9 sec) has passed since the button was last activated.

The green light is activated for 5 seconds, which is followed by an intermittent beep. Then, the green light blinks for 3 seconds and the intermittent beep becomes more frequent. After that, the red light is activated again, and the timer counts the time from 0 to 9 seconds.

If the train appears when the green light is on for pedestrians, the red signal is activated urgently and a continuous beep of a different height can be heard.

You can imagine the intersection happening like this:

<img width="1033" alt="screenshot 2017-02-10 13 37 41" src="https://cloud.githubusercontent.com/assets/22894897/22843305/2dde1c5a-ef96-11e6-85d0-09387e4598bf.png">

Black path is for cars, white & gray path is for the train and brown path is for people to cross.

While the train is passing, the switch cannot request a green light.

When the train comes again, the green light turns off and the red light turns on.

When the photoresistor is bright, that means the train is not passing but when you turn it dark, it means the train is passing. 

Wiring:

<img width="858" alt="screenshot 2017-02-12 22 09 27" src="https://cloud.githubusercontent.com/assets/22894897/22871636/f9f5580a-f16f-11e6-859c-548c69ba99ae.png">

Schematics:

<img width="1019" alt="screenshot 2017-02-13 09 43 57" src="https://cloud.githubusercontent.com/assets/22894897/22892790/f54eb3f8-f1d0-11e6-898d-559c49439271.png">



Simulator: https://circuits.io/circuits/3973783-ava-s-traffic-intersection/edit#breadboard

