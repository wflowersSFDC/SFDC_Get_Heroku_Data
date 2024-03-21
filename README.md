# SFDC Get Heroku Data Apex Class

# Rough instructions for connecting your org to the mock Heroku service

## 1. Create External Credential
  Create Principal - Can be named anything

## 2. Create Named Credential Name "Heroku"
  Named Credential **MUST BE** named "**Heroku**"
  
  URL should be "https://node-testapi-758688dae406.herokuapp.com"
  
  Assign the External Credential that you created prior to this Named Credential

## 3. Create Permission Set
  Create a Permission Set
  
  Add the External Credential you created earlier to External Credential Principal Access
  
  Assign the Permission Set to any user that needs access

## 4. (Optional) Add the Apex Class from this repo to your org if you would like to use the Apex callout rather than Flow
