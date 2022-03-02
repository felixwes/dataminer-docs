---
uid: GetAlarmsV2
---

# GetAlarmsV2

Retrieves a number of filtered alarms, along with the alarm cache status.

Available from DataMiner 10.0.7 onwards.

## Input

| Item             | Format | Description                                                                                                  |
|------------------|--------|--------------------------------------------------------------------------------------------------------------|
| Connection       | String | The connection ID. See [ConnectApp](xref:ConnectApp) .                                                         |
| DMAAlarmFilterV2 | Array  | The filter that the alarms must match. See [DMAAlarmFilterV2](xref:DMAAlarmFilterV2). |

## Output

| Item            | Format                                                                   | Description                                                                         |
|-----------------|--------------------------------------------------------------------------|-------------------------------------------------------------------------------------|
| GetAlarmsResult | Array of DMAAlarm (see [DMAAlarm](xref:DMAAlarm)) | The alarms matching the specified filter object, as well as the alarm cache status. |
