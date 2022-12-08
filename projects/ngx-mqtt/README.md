This library isn't just a wrapper around MQTT.js for angular.
It uses observables and takes care of subscription handling and message routing.

This means although you have the possibility of mqtt.js to use `mqtt`, `mqtts`, `tcp`, `ssl`, `wx` or `wxs` as the protocol in the client options, you can't, because this is a browser library where you can't conntect with something other than websockets. You also can't use `key`, `cert` and `ca` for the same reasons.


## **ngx-mqtt >= 7 is only compatible with angular >= 9**
