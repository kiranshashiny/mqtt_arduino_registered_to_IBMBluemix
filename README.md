# mqtt_arduino_registered_to_IBMBluemix

#####  This is for registering the Arduino to the IBM Bluemix.

            https://github.com/ibm-messaging/iot-arduino
        There are two ways of going about this.
        1. Quickstart
        2. Registered.
        
        Create a device, and make these changes

    Modify the AUTHTOKEN in the sketch code
    Modify the MS_PROXY, in the sketch code, by providing the values in the following format "uguhsp.messaging.internetofthings.ibmcloud.com", by replacing "uguhsp" with your organization
    Modify the CLIENT_ID, in the sketch code, by providing the values in the following format "d:uguhsp:iotsample-arduino:00aabbccde03", by replacing "aabbccde03" with the MAC Address and "uguhsp" with the organization, and the "iotsample-arduino" with the devicetype
