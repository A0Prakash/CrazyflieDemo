# CrazyflieDemo
## Assembly
To assemble the drones go to this link: https://www.bitcraze.io/documentation/tutorials/getting-started-with-crazyflie-2-x/.
Make sure that the propellers are on the motors in the correct orientation.
When using teleop (a controller) to operate the drone you will have to customize the binds on the controller. To do this, go to input device, then configure device mapping and map each bind.

## Lighthouse
To set up lighthouse, put the lighthouse stack onto the drone using the pins, then go to the crazyflie software to flash the lighthouse. If you ever have a connection issue with the lighthouse, reflash the drone. Follow the instructions here on how to set lighthouse up: https://www.bitcraze.io/documentation/tutorials/getting-started-with-lighthouse/.
The basestations should already have channels on it.
The configuration process is a bit weird. Make sure that 2 basestations are recieving from the origin, 1 meter in front of the origin, and other places around the flying area before calibrating.

## Flow
The flow deck is pretty simple, mount it to the bottom of the deck, and after, either use the code in this repo or follow the python tutorials on this page: https://www.bitcraze.io/documentation/tutorials/. You will have to change the radio address for the drones on the crazyflie app. Change the address in the code to what drones you will be using.

