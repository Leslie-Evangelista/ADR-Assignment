# Decision record template by Michael Nygard

This is the template in [Documenting architecture decisions - Michael Nygard](http://thinkrelevance.com/blog/2011/11/15/documenting-architecture-decisions).
You can use [adr-tools](https://github.com/npryce/adr-tools) for managing the ADR files.

In each ADR file, write these sections:

# Architectural Decisions: Reseponse to Scenario 1

## Status
Planning 

## Context
A retail company wants to create an app that enables customers to browse and purchase products, track their delivery status, and view their order history. The app must have a loyalty program feature that allows customers to earn and redeem points for discounts on future purchases. The app must have the following features:

- Customers can browse products and view order history offline; data is synced with the server once online.

- The app must have a push notification button, so order updates, new product arrivals and exclusive offers notify customers. 

- The app must integrate with secure and user-friendly payment gateways compatible with the app's target platforms.

- The retail company aims to track user behavior, including product views, purchases, and loyalty program interactions. Choose an analytics tool or service that offers comprehensive insights and metrics to enhance app performance and user experience.

- The retail company plans to expand its customer base globally, which requires supporting multiple languages and adapting to various cultural preferences. Choose a localization technique and look for a localization framework or libraries.


## Decision

### Platform Selection: 

## Consequences

What becomes easier or more difficult to do because of this change?
