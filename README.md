### Purpose

A simple app which allows the user to connect to a home wifi router.

### App Configuration

In order for the app to work properly, after cloning the repository the user needs to create an environment_variables.xml file to store their router's SSID and PASSWORD. This file is included in the .gitignore to ensure sensitive data isn't pushed to a repository.

  1) Navigate to the following folder - /app/src/main/res/values (it should already contain colors.xml and strings.xml files) 
  
  2) Create a file called environment_variables.xml
  
  3) Paste the following code below:

```

<?xml version="1.0" encoding="utf-8"?>
<resources>
    <string name="SSID">insertSSID</string>
    <string name="SSID_PASSWORD">insertPASSWORD</string>
</resources>

```
4) Replace insertSSID and insertPASSWORD with your home router's SSID and PASSWORD.

5) Build and run the app.
