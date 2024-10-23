install the python depedencies with pip install -r requirements
run python ./create_sandbox.py
for refreence here is the demo video.
PI Sandbox demo.mp4
 
Configuration:
{
  "PIWebAPI": "PLACEHOLDER_REPLACE_WITH_PI_WEB_API_URL",
  "AFServerName": "PLACEHOLDER_REPLACE_WITH_AF_SERVER_NAME",
  "DataArchiveName": "PLACEHOLDER_REPLACE_WITH_DATA_ARCHIVE_NAME",
  "Username": "PLACEHOLDER_REPLACE_WITH_USERNAME",
  "Password": "PLACEHOLDER_REPLACE_WITH_PASSWORD",
  "AuthType": "basic",
  "DEFAULT_TIMEOUT_INTERVAL": null
}
 
 
 
Functionality:
 
This sandbox App shows basic functionality of the PI Web API, not every feature, it uses the underlying PI Web API to read and write data to a PI Data Archive and AF. 
 
The functionality includes:
 
- Create an AF database
- Create a category
- Create an element template
- Create an element and associate the element's attributes with PI tags where appropriate
- Write a single value to the attribute
- Write 100 values to an attribute
- Perform a Batch (6 steps in 1 call) operation which includes:
  - Get the sample tag
  - Read the sample tag's snapshot value
  - Read the sample tag's last 10 recorded values
  - Write a value to the sample tag
  - Write 3 values to the sample tag
  - Read the last 10 recorded values from the sample tag only returning the value and timestamp
- Return all the values over the last 2 days
- Return timestamp and values over the last 2 days
- Delete the element
- Delete the element template
- Delete the sample database
 
If you have any question or suggestion . Please let me know.
