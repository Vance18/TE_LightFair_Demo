# TE_LightFair_Demo
A Smart Cities lighting demo featuring a TE light base, TE multisensor, an Intel Edison, and Arrow Connect.

## Directory

* **Documentation** -- Documentation for all components of the demo
* **node-red** -- Example node-red flow demonstrating SenseAbility dashboard and light control
    * **Language**: JavaScript/Node.js
    * **IDE**: node-red
* **Selene** -- Example Arrow Connect engine (Selene) configuration files for SenseAbility and UDP devices.
* **SenseAbility101** -- Arduino 101 firmware for integrating with the SenseAbility shield and writing the data out to a BLE characteristic.
    * **Language**: Arduino (C++)
    * **IDE**: [Arduino](https://www.arduino.cc/en/Guide/Arduino101)
* **Edison-UDP-Agent** -- Node.js script which handles I/O (I2C, ADC, PWM, and digital out), and sends telemetry/receives commands via local UDP ports.
    * **Language**: Node.js
    * **IDE**: [Intel XDK](https://software.intel.com/en-us/intel-xdk)