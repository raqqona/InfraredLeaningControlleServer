## InfraredLeaningControlServer

### API

```
method  : GET
path    : /api/polling
query   : {
            "temp" : "$TEMP",
            "hum" : "$HUM",
            "press" : "$PRESS",
            "previous_command" : "T/F"
          }

response: {
            "power" : "On/Off",
            "mode" : "$MODE",
            "temp" : "$TEMP",
            "swing" : "$SWING",
            "fan" : "$FAN"
          }
```

```
method  : GET
path    : /api/getIndoorEnv
response: {
            "temp" : "$TEMP",
            "hum" : "$HUM",
            "press" : "$PRESS",
            "previous_command" : "T/F"
          }
```

```
method  : POST
path    : /api/command
query   : {
            "power" : "On/Off",
            "mode" : "$MODE",
            "temp" : "$TEMP",
            "swing" : "$SWING",
            "fan" : "$FAN"
          }
```


