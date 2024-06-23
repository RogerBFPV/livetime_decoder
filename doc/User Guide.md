# LiveTime Decoder User Guide

### Hardware and Software Setup
Follow the instructions here if not done already: [/doc/Hardware and Software Setup Instructions.md](Hardware%20and%20Software%20Setup%20Instructions.md)

### Configure Livetime

* In decoders add a decoder and select 'Delta 5' as the type
* In decoders->Connection: specify the type as Ethernet, and configure the IP address of the LiveTime Decoder.
* In decoders->Settings:  press the 'Sync Event Video Frequencies to setup the proper frequencies in the LiveTime Decoder.  Modify the Calibration Threshold, Calibration Offset and Trigger Threshold has determined using the Tuning Guide.  

If you are noticing any missed or multiple laps when passing the gate, the sensor tuning values can be adjusted from defaults with a detailed description found here [/doc/Tuning Parameters.md](Tuning%20Parameters.md)

### Optionally: utilize the  LiveTime Decoder web interface to see settings
Find the ip address of the raspberry pi by opening the 'Clients' list on your routers admin page.

Open a browser and type in the ip address of the timing system on your network using port 5000 or as configured in 'server.py'.
```
XXX.XXX.XXX.XXX:5000/
```

