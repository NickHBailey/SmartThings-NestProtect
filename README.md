#SmartThings-NestProtect
A SmartThings device type for Nest Protect.

Largely inspired and borrowed from the Nest thermostat device type at: https://gist.github.com/Dianoga/6055918

##Usage
####1. Create a [new device type](https://graph.api.smartthings.com/ide/devices)
* **Name**: Nest Protect
* **Author**: nick@nickhbailey.com
* **Capabilities**:
	* Battery
	* Carbon Monoxide Detector 
	* Polling
	* Smoke Detector
* Copy contents of [Nest Protect Device Type](https://github.com/NickHBailey/SmartThings-NestProtect/blob/master/Nest%20Protect%20Device%20Type) file to your new device type

####2. Create a [new device](https://graph.api.smartthings.com/device/list)
* **Name**: Your Choice
* **Device Network Id**: Your Choice
* **Type**: Nest Protect (should be the last option)
* **Location**: Choose the correct location
* **Hub/Group**: Leave blank

####3. Update device preferences
* Click on the new device to see the details.
* Click the edit button next to Preferences
	* Fill in your Nest login information.
	* Add the Nest Protect MAC Address
		1. login to <http://home.nest.com>
		2. Click the Protect icon
		3. Open the right-hand side bar
		4. Open Nest Protect Settings
		5. Choose the Nest Protect you are adding
		6. Open Technical Info
		7. Copy the value next to 802.15.4 MAC.
