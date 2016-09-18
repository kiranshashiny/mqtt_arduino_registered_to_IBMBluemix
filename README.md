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

##### Viewing the data visually using npm
    Download the iot-visualization-0.2.0
    https://console.ng.bluemix.net/docs/services/IoT/visualizingdata_sample.html
    Click on "Download the visualization sample "
    and it will download the iot-visualization-0.2.0.zip
    once done - install the necessary packages using npm

    start it  node app.js
    Get the Auth key and the token and then enter that into the node.js code.

    This should render the data on your laptop.

