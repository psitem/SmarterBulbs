# SmarterBulbs

A SmartThings SmartApp for resetting the state of smart bulbs after a power loss. Ordinarily smart bulbs will turn themselves on upon power restoration -- a handy feature for allowing light control via switch if your smart hub is offline, but not-so-desirable when your power flickers at 3AM and all of your lights turn on.

With this SmartApp you designate a Canary smart bulb that will ordinarily be powered and turned off, and then configure a list of smart bulbs whose state should be tracked. When the SmartApp detects the Canary bulb has turned on it will reset the tracked bulbs to their previous state and turn the Canary back off.

This script was [authored by nsweet on the SmartThings community forums](https://community.smartthings.com/t/release-smartbulb-power-outage-handler/49650). I've re-package the latest version they wrote in a form that is more friendly to using with SmartThing's GitHub integration.

![Example Configuration Screen](https://github.com/tbyehl/SmarterBulbs/blob/master/smarterbulbs-config-screen.png)
