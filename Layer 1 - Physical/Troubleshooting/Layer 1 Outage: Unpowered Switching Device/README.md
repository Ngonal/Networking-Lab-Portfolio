# Diagnosis
1. It appears that one of the cables isn't even plugged in - Reconnecting to Fa0/1 - Lights remain unilluminated
2. Upon further inspection, the Switch's power switch is turned off - Turning on - Some lights illuminate, no illumination on one of the connected ports
3. Logging into the CLI and inspecting the interface status, the port waas administratively turned off (Layer 1 power), turning it back on and the port lights illuminate
4. Both nodes are now able to communicate
