# node-red-contrib-azure-event-hub-send-message
This custom node-red node is used to sen messages to the Azure Event Hub.

## Input Parameters

### Name (Optional)
The name parameter takes a string as input. The string would appear as the name of the node. 
Default Value is: Clovity - Send - Azure Event Hub

### Connection String (Mandatory):
The endpoint connection string which allows you to connect to the event hub.
Format: Endpoint=sb://XXXXXXXXX-prd.servicebus.windows.net/;SharedAccessKeyName=XXXX;SharedAccessKey=XXXXX

### Event Hub path (Mandatory):
The name of the event hub where the messages have to be sent to.

## Screenshot
![Clovity Azure Event Hub Node](https://github.com/clovityinc/node-red-contrib-azure-event-hub-send-message/blob/master/images/ClovitySendAzureEventHubMessage.png)

## Installation
```
npm i node-red-contrib-azure-event-hub-send-message
```

## Usage
1. Copy the below JSON
```JSON
[{"id":"27a034a5.375acc","type":"clovitySendAzureEventHubMessages","z":"864e40f6.22f76","name":"Clovity - Send - Azure Event Hub","x":520,"y":320,"wires":[["3110b8b3.46b708"]]}]
```

2. Access the node-red UI using http://localhost:1880. Click on Import-->Clipboard and paste the copied json in the text area and Click Import.

3. Update the Name, Connection String and Event Hub path parameters with the ones you wish to send messages to.





