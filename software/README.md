The flight controller software uses the open-source OpenPilot firmware, with the CC3D board serving as the flight controller for the Tdrone.

We are using release version 15.02.02. For convenience, the firmware has already been ported and is provided here.

How to compile from source:

```
make all_sdk_install

make all
``` 

For easier use, we have also pre-compiled the Ground Station and uploaded it to the Ground Station folder. You can simply download it and use it directly for configuration.

Connect the CC3D flight controller to the Ground Station, then configure the Tdrone flight settings through the Ground Station. A stable flight configuration file has been uploaded here — you can import it directly.

More documentation and instructions will be added later. Please stay tuned for updates.




