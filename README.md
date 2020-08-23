# NodeRedPresentFritzbox
## Short Description
Present detection via mobile phone.

It is checked whether a certain device (mobile phone) has dialed into the network. 
This is done via the Fitzbox (MAC address of the device).

You need:
- node-red-contrib-fritz     https://flows.nodered.org/node/node-red-contrib-fritz
- node-red-contrib-simpletime   https://flows.nodered.org/node/node-red-contrib-simpletime

The FLOW looks like this (just import the json-file) :-)

![](https://github.com/AndreasHuth/NodeRedPresentFritzbox/blob/master/flow.png)

You get the following info from the Fritzbox:

![](https://github.com/AndreasHuth/NodeRedPresentFritzbox/blob/master/object.png)

Interesting is the variable: NewActive.
This variable indicates if the device is in the WLAN.

Using the Simpletime is quite nice here because you can see since when you are logged in / out. 

## How to use
Please download the json-file and import it into Node Red.

## further informations
none

## Links
see above.
