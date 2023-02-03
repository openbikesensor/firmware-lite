# OpenBikeSensor Lite Firmware

This is the firmware repository for the up-and-coming "Lite" version of the OpenBikeSensor.

If you are looking for the firmware for the existing, "Classic" OpenBikeSensor, you can find it here: https://github.com/openbikesensor/OpenBikeSensorFirmware

The OpenBikeSensor Lite is currently in development and not available to build yet. There are not instructions and this firmware, the recording software, data format and enclosure are not completed. Please go over to the [OpenBikeSensor Website](https://www.openbikesensor.org/docs/hardware/) if you're interested in building your own device, it contains all information for the Classic version of the OpenBikeSensor.

## Quickstart

* Install PlatformIO, either the IDE version or just the CLI tools are fine. 
* Attach your ESP32 to the USB Port of your computer. Wire up the Sensors and buttons according to the schematics from [the obs-lite branch of the PCB repository](https://github.com/openbikesensor/OpenBikeSensor_PCB_Board/tree/obs-lite/OpenBikeSensorLite).
* Build and run the PlatformIO project. It should upload and start running.
* Monitor your serial port. You should be able to decode the data stream using the [OpenBikeSensor Recording Format](https://github.com/openbikesensor/proto), for example with the included [`examples/reader.py`](https://github.com/openbikesensor/proto/blob/main/examples/reader.py) script.
