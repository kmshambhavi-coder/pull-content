## Sync Incidents
Deprecated. This job synchronizes Google SecOps Alerts and Microsoft Sentinel Incidents. It ensures that comments, status, and tags are kept in sync between the two systems. For the job to identify the correct information, the Google SecOps case must have the “Microsoft Sentinel Incident” tag. If the alert didn’t originate from “Microsoft Azure Sentinel Incident Connector v2”,  you will need to add an “Incident_ID” context value to the case for the job to be able to find the correct information.


**Run Interval In Seconds:** 3600

#### Parameters
|Name|Type|Is Mandatory|Value|
|----|----|------------|-----|
|Environment Name|String|True|Default Environment|
|Azure Active Directory ID|String|True|d48f52ca-5b1a-4708-8ed0-ebb98a26a46a|
|OAUTH2 Login Endpoint Url|String|True|https://login.microsoftonline.com|
|API Root|String|True|https://management.azure.com|
|Client ID|String|True|29bf818e-e1e5-438c-a1ac-784fb644178d|
|Client Secret|Password|True|*****|
|Max Hours Backwards|Integer|False|24|
|Verify SSL|Boolean|False|true|


readme text upgraded legacy