# Timetstamp Microservice
___

##### Challenge: [FreeCodeCamp: Timestamp Microservice](https://www.freecodecamp.org/challenges/timestamp-microservice)

___

### User Stories:

1. I can pass a string as a parameter, and it will check to see whether that string contains either a unix timestamp or a natural language date (example: January 1, 2016).

2. If it does, it returns both the Unix timestamp and the natural language form of that date.

3. If it does not contain a date or Unix timestamp, it returns null for those properties.
___

### Example usage: 

`https://fcc3-timestamp-microservice.glitch.me/22%20October,%202017` will return `{"unix":"1508630400","natural":"22 October, 2017"}`.

`https://fcc3-timestamp-microservice.glitch.me/1508630400` will return `{"unix":"1508630400","natural":"22 October, 2017"}`.


___

You can see live version [here](https://fcc3-timestamp-microservice.glitch.me/).