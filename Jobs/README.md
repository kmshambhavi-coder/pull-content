## Google Chronicle Sync Job
This job will synchronize information about Chronicle SOAR Cases and Chronicle SOAR Alerts with Chronicle SIEM.
 Note: This job is only supported from Chronicle SOAR version 6.1.44 and higher.


**Run Interval In Seconds:** 86400

#### Parameters
|Name|Type|Is Mandatory|Value|
|----|----|------------|-----|
|Verify SSL|Boolean|False|false|
|Environment|String|True|Default Environment|
|API Root|String|True|https://backstory.googleapis.com|
|User's Service Account|Password|False|*****|
|Workload Identity Email|Password|False|*****|
|Max Hours Backwards|String|False|24|


readme job text