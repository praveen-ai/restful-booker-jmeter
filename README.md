# restful-booker-jmeter
Apache JMeter API Performance Testing project for Restful Booker with parameterization, correlation, assertions, controllers, non-GUI execution, and HTML reporting.


# Restful Booker API Performance Testing using Apache JMeter

## Project Overview

This project demonstrates API Performance Testing using Apache JMeter against the Restful Booker application.

The test suite covers complete booking workflows including authentication, booking creation, retrieval, update, and deletion.

## APIs Covered

* Create Token
* Create Booking
* Get Booking By ID
* Update Booking
* Delete Booking

## Features Implemented

* CSV Parameterization
* User Defined Variables
* HTTP Header Manager
* HTTP Request Defaults
* JSON Extractor
* Correlation using Token and Booking ID
* Response Assertions
* JSON Assertions
* Transaction Controller
* Throughput Controller
* Debug Sampler
* Non-GUI Execution
* HTML Dashboard Reporting

## Test Flow

Authentication → Create Booking → Get Booking → Update Booking → Delete Booking

## Execution

Run test in Non-GUI mode:

./jmeter -n -t Restful-booker.jmx -l result.jtl

Generate HTML Report:

./jmeter -g result.jtl -o report

## Tools Used

* Apache JMeter 5.6.3
* REST APIs
* GitHub

## Author

Praveen Jakkula
