---
page_type: sample
description: "A set of Java samples that show how a device that uses the IoT Plug and Play conventions interacts with either IoT Hub or IoT Central."
languages:
- java
products:
- azure-iot-hub
- azure-iot-central
- azure-iot-pnp
urlFragment: azure-iot-pnp-device-samples-for-java
---
## Configuring the sample
Both samples use environment variables to retrieve configuration.

* If you are using a connection string to authenticate:
  * set IOTHUB_DEVICE_SECURITY_TYPE="connectionString"
  * set IOTHUB_DEVICE_CONNECTION_STRING="\<connection string of your device\>"

* If you are using a DPS enrollment group to authenticate:
  * set IOTHUB_DEVICE_SECURITY_TYPE="DPS"
  * set IOTHUB_DEVICE_DPS_ID_SCOPE="\<ID Scope of DPS instance\>"
  * set IOTHUB_DEVICE_DPS_DEVICE_ID="\<Device's ID\>"
  * set IOTHUB_DEVICE_DPS_DEVICE_KEY="\<Device's security key \>"
  * *OPTIONAL*, if you do not wish to use the default endpoint "global.azure-devices-provisioning.net"
    * set IOTHUB_DEVICE_DPS_ENDPOINT="\<DPS endpoint\>"