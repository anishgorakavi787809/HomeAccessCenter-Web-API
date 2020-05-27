# HomeAccessCenter Web API
This is the [ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/) Web API for [Home Access Center](https://www.powerschool.com/solutions/student-information-system/eschoolplus-sis/).

![Travis CI](https://travis-ci.com/Phytal/HomeAccessCenter-Web-API.svg?branch=master)
![.NET Core](https://github.com/Phytal/HomeAccessCenter-Web-API/workflows/.NET%20Core/badge.svg)
![MIT License](https://img.shields.io/github/license/Phytal/HomeAccessCenter-Web-API)

This project allows you to access student data from HAC easily through a web API. While currently in early stages of production, updates and features will be regularly pushed out.

## Usage 

The home directory for this web api is `https://hac-web-api-production.herokuapp.com/api/hac`

To access a student's information, add the parameter **hacLink**, **username**, and **password** to the end of the link.

> Note: hacLink corresponds with the following format: https://hac.friscoisd.org

### Example

```
https://hac-web-api-production.herokuapp.com/api/hac?hacLink=https://hac.friscoisd.org&username=Smith.J&password=Password123
```

## Donation

If this project helpd you, you can give me a cup of coffee ☕

[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.me/phytal/5)