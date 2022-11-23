# Bayernlüfter Interface (Wifi module only)

### General information

The export function for Smart Home systems has been made more flexible by BAVARIAVENT since the Wifi module firmware WS180924. The format of the export can be designed/changed in the export.txt file itself. Templates for XML and YAML are available by default.<br><br>


### Preconditions

You are a proud owner of a Bayernlüfter (with Wifi module) and have successfully completed the initial setup, i.e. connected the Bayernlüfter to your Wifi network, set the router to always get the same IP address from your DHCP server and stored this accordingly in the settings in the interface of the Bayernlüfter.

On the other hand, you have a Smart Home system/Gateway and/or visualization software that can process JSON? Great, then you can start right away.<br><br>


### How to invoke the export interface?

The Export can be invoked by calling the Url http://{IP address of your device}/?export=1<br><br>


### What do I need to do if I want to use JSON instead of the default XML/YAML provided by the template?

Go to Settings > Expert Browser and upload the export.txt file included in this folder. Please be aware that the file on the device will be overwritten, so please take care of downloading the original file first as a backup before uploading anything using the expert browser.<br><br>

### Which data fields are available in the JSON export?

All data fields that are also provided in the XML template. If you have your own requirements for the structure of the JSON, you can make these adjustments quite intuitively directly in the file.
