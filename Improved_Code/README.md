# Catapult

Improved_Code.png provides a program that should make a more reliable catapult.
The motion sensor takes a while to stablise (about 60 seconds), so we have increased the delay before the device arms. 
We also poll the motion sensor to check its state, rather than using a pin release event.

