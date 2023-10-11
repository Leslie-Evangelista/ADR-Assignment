# Architectural Decisions: Reseponse to Scenario 1 by Leslie Evangelista

## Status
Planning 

## Context
A retail company wants to an app that enables customers to browse and purchase products, track their delivery status, and view their order history. The app must have a loyalty program feature that allows customers to earn and redeem points for discounts on future purchases. The app must have the following features:

- Customers can browse products and view order history offline; data is synced with the server once online.

- The app must have a push notification button so that customers can be notified of order updates, new product arrivals, and exclusive offers. 

- The app must integrate with secure and user-friendly payment gateways compatible with the app's target platforms.

- The retail company aims to track user behaviour, including product views, purchases, and loyalty program interactions. Choose an analytics tool or service that offers comprehensive insights and metrics to enhance app performance and user experience.

- The retail company plans to expand its customer base globally, which requires supporting multiple languages and adapting to various cultural preferences. Choose a localization technique and look for a localization framework or libraries.

## Decision

### Platform Selection: 
Based on the given context of the app, I believe that Native is the best choice for creating the retail app. 

#### Rationale: 
Native applications are designed to run on operating systems supporting Android and iOS devices. The platform utilizes APIs to access location services, enable in-app purchases, push notifications, and receive alerts, meeting the requirements of the retail app. Meeting these requirements will notify users of exclusive retail deals and promote a better connection with the retail business and its customers. Another benefit of creating the app through Native is that it has better performance than other applications due to optimizing in one platform, making the user experience even better. 

## Consequence:
Although Native allows users to have optimal performance and better user experience, the downside of choosing Native is higher development cost, longer development time and multiple codebases.

### UI Framework

I believe the best choice for the UI Framework would be React Native since the application itself will be in Native. Java script is the primary language it uses to create the user interface. When creating the UI framework of the retail app, the user interface components should include buttons, menus, product listings, search bars, and the order history display. These added features will support the added loyalty program in the app, which can include a points balance display, redemption points and notifications of the loyalty program in the app. As for the navigation pattern of the app design, it should allow users to move quickly between product browsing, order history, the loyalty program features page, and other pages in the app. Some navigation components that can be added to the framework are bottom navigation bars or a side menu for better accessibility of the different pages in the app. The internalization and localization of the framework of the app should include various languages to choose from when users enter the app and an adaption to content for cultural preferences, including the text and images in the app. The other requirement that the framework must have is push notifications. The framework should support push notifications so customers can receive updates on their order status, new product arrivals, and exclusive deals in the app. Lastly, the behaviour tracking and analysis of the UI should have an analytics tool to track the user's behaviour in the app, such as purchases and interactions with the loyalty program. 

### Backend Language 
The backend language in Native includes C++, C#, Java and Objective-C. The language for the backend of this app would be Java. 

#### Rationale: 
Java was chosen as the backend language due to its performance and security, such as dealing with transactions and sensitive data. 

### Data Storage:
The best data handling and storage architecture I would choose are caching mechanisms and SQL database for the data storage. 

#### Rationale:
Caching mechanisms make the response time faster and lessen the network requests in the retail app. Caching mechanisms also support offline access by storing data locally on the user's device. 

SQL database has excellent data integrity security and supports transactional operations.
