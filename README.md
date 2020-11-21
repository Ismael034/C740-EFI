# Lenovo C740 OpenCore configuration

This is a working configuration for the Lenovo Yoga C740. It has been tested on macOS Catalina and Big Sur.

## Things to know

Wifi and bluetooth are running under itlwm, which is not very stable. This means that an application is required to get Wifi working. If you want full compatibility, it is recommended to get another wifi card. 

The touch display in this case is functional. However it has been disabled as the fix to get it working requires voodooi2c to run in polling mode, which makes the CPU to be busy and will drain your battery way faster.

The microphone is not working as it uses SST which is not compatible. You can use as an alternative the headphone jack.


