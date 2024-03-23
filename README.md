# edge-app-schedule-value-notification
Edge app with notification on certain values.

Triggers when functions are over or under a threshold value.


Example notification message.

```
Installation: {{.installation.Name}}
Value: {{.payload.value}}
Device: {{.payload.device.meta,name}}
Function: {{.payload.func.meta.name}}
Action: {{.payload.action}} (over or under)
```
.payload.func  and payload.device are the complete function and device objects. 
