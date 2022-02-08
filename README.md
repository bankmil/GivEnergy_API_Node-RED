# GivEnergy_API_Node-RED_Hassio
This is a Pre-built REST API call for GivEnergy, it will gather information about your Givenergy battery and inverter and will import into Home Assistant. The new entities it creates can be used in the Energy Tabs

HOW TO USE THIS CODE:

 -Please follow the instructions in the below link to install Node-RED into Home Assistant
  https://community.home-assistant.io/t/home-assistant-community-add-on-node-red/55023

 -Once installed, navigate to Node-RED via Hassio and simply import the .json file
 
 -Set the API key in Step 1 and click 'Deploy'

 -Launch the flow in Steps 1 and 2.

 -Step 3 will automaticaly run every 5 minutes.

 -Flows will automaticaly create new entities in Hassio. 
 
 
_______________________________________________________

# Energy Card Configuration
The following new entities can be used in the Energy Card to provide accurate energy usage and stats:
 
 
  -Gird Consumption: GivEnergy_Import_Energy_Total
 
  -Return to grid: GivEnergy_Export_Energy_Total
 
  -Solar Production: GivEnergy_pv_daily_yeild
 
  -Battery In: GivEnergy_Battery_Charge_Today
 
  -Battery Out: GivEnergy_Battery_Discharge_Today

Enjoy!
