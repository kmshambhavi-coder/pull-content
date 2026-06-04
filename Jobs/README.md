## Sync Incidents
Deprecated. This job synchronizes Google SecOps Alerts and Microsoft Sentinel Incidents. It ensures that comments, status, and tags are kept in sync between the two systems. For the job to identify the correct information, the Google SecOps case must have the “Microsoft Sentinel Incident” tag. If the alert didn’t originate from “Microsoft Azure Sentinel Incident Connector v2”,  you will need to add an “Incident_ID” context value to the case for the job to be able to find the correct information.


**Run Interval In Seconds:** None

#### Parameters
|Name|Type|Is Mandatory|Value|
|----|----|------------|-----|
|Environment Name|String|False|Default Environment|
|Azure Active Directory ID|String|False|dfgh|
|OAUTH2 Login Endpoint Url|String|False|https://login.microsoftonline.com|
|API Root|String|False|https://management.azure.com|
|Client ID|String|False|29bf818e-e1e5-438c-a1ac-784fb644178d|
|Max Hours Backwards|Int|False|24|
|Verify SSL|Boolean|False|true|
|Client Secret|Password|False|*****|


readme text