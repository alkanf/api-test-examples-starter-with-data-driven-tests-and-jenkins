## Overview
This repository contains Postman collections and scripts for automated API testing, also a Jenkins file for API
Only the happy path scenarios are included. All dynamic variables used in the collection are fully operational.

**Important:** 
- Please use your **own API key and token** when running the collection.
- This collection **does not require an environment**; it can be run standalone.
- The collection is designed to be run **from start to finish** without manual intervention.
- Jenkinsfile is incuded and has been successfully run, you can use it to run the pipeline if you wish

## Special Instructions
- Any additional boards created during testing can be automatically deleted using the `autoDelete` variable.
- All scripts and test logic are included to demonstrate full test coverage of the happy path scenarios and dynamic variables/validation.
- API Documentation Reference:** You may consult the API documentation for reference on request structure and responses.  
