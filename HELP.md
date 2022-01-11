## Roland V-600UHD

This module will allow you to control a Roland V-600UHD video switcher.

### Configuration
* Enter the IP address of the device in the configuration settings.
* The device will use TCP port 8023.
* Roland documents that the command string should start with the STX character. 
This is correct when controlling the V-600UHD over a serial port,
but does not appear to be correct for TCP connections (tested with V-600UHD firmware version 2.02). 
The STX prefix is omitted by default but you can select to have it added if your V-600UHD requires it.

**Available actions:**
* Select PGM channel
* Select PST channel
* Select channel to send to AUX bus
* Select transition pattern
* Set video transition time
* Press the [AUTO] button
* Press the [CUT] button
* Select COMPOSITION type
* Select DSK type
* Press the [COMPOSITION] button
* Press the [DSK] button
* Set output fade on/off
* Set output fade time
* Adjust volume level of input audio
* Adjust volume level for master out
* Adjust volume level for AUX-bus audio
* Call up memory
