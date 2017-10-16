Bash script to send e-mail alert on motion detection by comparing successive images.<br/>
Images can be acquired from an URL or from a locally connected camera.<br/>
Requires imgcmp utility (libjasper-runtime package on Debian-based systems) and tools for getting the image (e.g. wget, streamer, uvccapture or similar).<br/>
Requires heirloom-mailx (heirloom-mailx package on Debian-based systems).<br/>
<br/>
Files:<br/>
<b>motion</b>: bash script.<br/>
<b>motionvars</b>: variable definition file (from line 1 to 5: username, password, URL, sender e-mail address, receiver e-mail address). This is read by the script, see comments there.<br/>
<b>mailbody</b>: the body of the message to be sent when motion is detected.
