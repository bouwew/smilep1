# smilep1
Plugwise Smile P1. Works for v2. V3?

Configuration.yaml:
```
sensor:
  - platform: plugwisesmile
    host: x.x.x.x
    username: smile
    password: password
    resources:
      - electricity_consumed_point
      - electricity_consumed_offpeak_interval
      - electricity_consumed_peak_interval
      - electricity_consumed_offpeak_cumulative
      - electricity_consumed_peak_cumulative
      - electricity_produced_point
      - electricity_produced_offpeak_interval
      - electricity_produced_peak_interval
      - electricity_produced_offpeak_cumulative
      - electricity_produced_peak_cumulative
      - gas_consumed_interval
      - gas_consumed_cumulative
```


Code by Jeroen van der Schoot: https://bitbucket.org/jvdschoot/home-assistant-sensor-plugwise-smile-p1/src/master/
Modified by bouwew to work on recent versions of Home Assistant Core.
