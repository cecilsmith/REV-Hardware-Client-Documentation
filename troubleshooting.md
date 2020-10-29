# Troubleshooting

## Device is not visible

 If you don't see all of the devices that you expect to see, follow these steps:

* Make sure that you are connected to the Internet, so that Windows can download the necessary drivers
* Disconnect the device from the computer and then re-connect it
* Click the "Scan for Devices" link in the bottom-right corner of the Hardware tab

If that doesn't work, follow the steps for the type of device that is missing.

### Control Hubs connected via USB

* Make sure that the Control Hub is plugged in via USB-C, not Mini USB
* Make sure the Control Hub has had a chance to finish starting up, and that its light is green
* Unplug the Control Hub from the computer and plug it back in

### Control Hubs connected via WiFi

* Make sure that the Control Hub is running version 5.5 or later of the Robot Controller app
* Make sure the Control Hub has had a chance to finish starting up, and that its light is green
* Make sure that you are currently connected to the Control Hub's WiFi network
* Try rebooting the Control Hub. Re-connect to its WiFi network after its light turns green
* Plug the Control Hub in via USB instead

### Expansion Hubs connected to a Control Hub

* Make sure that the Expansion Hub is in the active configuration file
* Make sure that the Control Hub is running version 5.5 or later of the Robot Controller app

### Android phones

* Make sure that USB debugging is enabled in the Developer Options
  * If you can't find Developer Options anywhere in the Settings app \(it may be listed on a System screen or similar\), make sure it is enabled by tapping on the Build number 7 times on the About screen of the Settings app.
* Unplug the phone from the computer and plug it back in. Look for a prompt to allow USB debugging, and click OK when it comes up.
* Make sure that the ADB driver for your Android phone is installed. For Motorola phones, do this by installing Motorola Device Manager.

