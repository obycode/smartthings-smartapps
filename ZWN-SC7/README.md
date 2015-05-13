Multi-Button Scene Controller
============================================

These files are used to connect a multi-button scene controller to SmartThings, and then create a virtual button for each of the physical buttons on the device. This way, each button can be used with a SmartApp supporting the capability.button. This could change in the future if the capability changes to support multiple button devices.

It works with the Enerwave 7 Button Scene Controller (ZWN-SC7) using the included device type (ZWN-SC7.groovy), based on the one developed by Matt Frank, and should also work with the official device type for the Aeon Minimote.

Installation
------------
To use with the ZWN-SC7, first publish the device type, then use the standard SmartThings add device procedures. It should correctly identify the device by its fingerprint.

Next, publish the device type, VirtualButton.groovy, and the SmartApp, VirtualButtons.groovy to your account via the IDE. In the SmartThings app, go to SmartSetup -> My Apps and find "Virtual Buttons". Select the multi-button device and press Done. You will now see N new buttons (4 for the Minimote, 7 for the ZWN-SC7) in your Things section. You may now use these for your SmartApps, or add these new buttons to SmartRules (http://smartrulesapp.com) and easily create rules for them.
