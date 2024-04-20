# OSX WiFi Roaming Script

*OSX WiFi Roaming Script*

In wireless network deployments, it is important to understand the behavior of wireless clients based on the radio frequency deployment. In particular the roaming thresholds which the client device devices to roam at in order to ascertian whether time sensitive applications such as voice and video could be impacted, due to either a poor wireless deployment or sticky client behavior. 

## Demonstration:

![Demo](./roaming.gif)

### Requirements 

* OSX (Tested using Sonoma) 

* For best performance (truecolour) iTerm2 terminal client is recommended

## Modes of Operation 

This script can only operate in one mode, Control-C should be used to end script.

Given the rights requirements of the new wdutil utility which is used.


**Tools & Frameworks:**

- Tcl (8.5)
- Tclx (module)
- wdutil (natively installed in OSX)


## Authors & Maintainers

- Josh Halley <johalley@cisco.com>

## License

This project is licensed to you under the terms of the [Cisco Sample
Code License](./LICENSE).
