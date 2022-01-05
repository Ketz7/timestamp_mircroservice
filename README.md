#File size ![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/Ketz7/timestamp_mircroservice?logo=GitHub&style=plastic)
# [Timestamp Microservice](https://www.freecodecamp.org/learn/apis-and-microservices/apis-and-microservices-projects/timestamp-microservice)
# Timestamp Microservice made for FreeCodeCamp Backend Development and API's Project
This is a Node.js (with Express.js) little application which is part of the FCC Back End Certification. It takes a date string and gives you back a JSON with Unix value and natural format for the given date.

Example usage:
```
api/December%2015,%202015
api/1450137600
api/ -> gives current time in unix and utc
```

Example output:
```
{ "unix": 1641383496274, "utc": "Wed, 05 Jan 2022 11:51:36 GMT" }
```
