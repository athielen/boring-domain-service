# The Boring and Repeatable Domain Layer Microservice
Boring, predictable domain service applications 

#### Why is this boring and predictable?
In my past experiences, I've seen many special snowflake domain access services in the same stack. This meant an abover average time spent ramping up for any new developer to the app and it also there wasn't a lot of uniformity across the domain layer services. It resulted in a slower delivery on feature development and deployment.

In my opinion, my value as a developer is to develop **reliable, tested features** that can be **deployed with confidence** within **a tight deadline**.

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prequesites to being Production Ready
* Code coverage of %65 w/ a reliance on framework testing tools
* System, application and custom system metrics (preferrably through Prometheus)
* Prod ready logging with proper masking of any senstive data
* Proper fallbacks with circuit breakers

## Decision Log

### How to handle downstream failures?

### Fallback Responses for errrorenous requeusts

### NOSQL data model
