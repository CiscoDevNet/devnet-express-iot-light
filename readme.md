# DevNet Express IoT light

Welcome to the DevNet Express IoT light event!

Sessions included:

1. **DevNet IoT Overview**: Get an overview of DevNet IoT: self-guided learing labs, sandboxes, code examples etc.
2. **Introduction to Coding/Python + REST API**: Get data from the Cyber Vision sandbox via a Python script. 
3. **Industrial Network Automation Fundamentals**: Learn how to get data out of the Cisco DNA Center and directly from the IOS XE devices via RESTCONF/NETCONF.
4. **IOx Edge Compute Framework & Docker 101**: Deploy containerized edge applications.
5. **Industrial NetDevOps**: Get familiar with the industrial NetDevOps toolbelt.

Useful links:

* [IoT Learning Labs Overview](https://developer.cisco.com/learning/tracks/iot)
* [DevNet IoT Overview](https://developer.cisco.com/iot)
* [DevNet Sandboxes](https://devnetsandbox.cisco.com/)

*To access the labs and sandbox you need a DevNet account (free)*

## 2: Introduction to Coding/Python + REST API

### Task 1: Simple Request

1. Install Python on your machine locally or simply use an online Python interpreter (for example: [Programiz Python Online Compiler](https://www.programiz.com/python-programming/online-compiler/)
2. Copy/paste and run the code from the script `2_simple-requests.py`

### Task 2: Use Cyber Vision

Follow the [getting started learning lab](https://developer.cisco.com/learning/tracks/iot/cybervision/iot-cybervision-api-python-v4/step/1) and use the code `2_cyber-vision-requests.py`.


## 3. Industrial Network Automation Fundamentals

### Task 1: Try out the Cisco DNA Center APIs

1. Use Postman or other API tools to get network device data.

DNA Center 2.2 (always on sandbox):

* https://sandboxdnac.cisco.com
* credentials [devnetuser/Cisco123!]

### Task 2: RESTCONF - Get data from the IOS XE RESTCONF interface

1. Use Postman or the Python scripts `3_restconf-get-all-interfaces.py` or `3_restconf-getting-started.py` to get information directly from the device.

IOS XE (always on sandbox):

* CSR1000v Host: sandbox-iosxe-latest-1.cisco.com
* SSH Port: 22
* NETCONF Port: 830
* gRPC Telemetry Port: 57500
* RESTCONF Port: 443 (HTTPS)
* Username: developer
* Password: C1sco12345

Optional Learning Lab: https://developer.cisco.com/learning/modules/industrial-netdevops/iot-industrial-netdevops-restconf/step/1


### Task 3: NETCONF - Get data from the IOS XE NETCONF interface

1. Use Postman or the Python script `3_netconf-getting-started.py` to get information directly from the device.

IOS XE (always on sandbox):

* CSR1000v Host: sandbox-iosxe-latest-1.cisco.com
* SSH Port: 22
* NETCONF Port: 830
* gRPC Telemetry Port: 57500
* RESTCONF Port: 443 (HTTPS)
* Username: developer
* Password: C1sco12345

Optional Learning Lab: https://developer.cisco.com/learning/modules/industrial-netdevops/iot-industrial-netdevops-netconf/step/1 

## 4. IOx Edge Compute Framework & Docker 101

### Task 1: Deploy IOx edge application on the DevNet IOx Sandbox

1. Go to [https://devnetsandbox.cisco.com](https://devnetsandbox.cisco.com) and reserve the Sandbox **IOx Latest**.
2. Have an RDP Client installed (Windows included, [download for macOS](https://docs.microsoft.com/en-us/windows-server/remote/remote-desktop-services/clients/remote-desktop-mac))
3. Optionally you can use your local Docker environment
4. Follow the steps in the [IOx learning lab](https://developer.cisco.com/learning/lab/iox-app-devbox/step/1) and slides.

## 5. Industrial NetDevOps

### Task 1: Tryout a learning lab from the Industrial NetDevOps module

1. Go to the [Industrial NetDevOps - Getting Started learning labd module](https://developer.cisco.com/learning/modules/industrial-netdevops) and select a learning lab of your choice.



