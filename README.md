# Amazon MWS docs

This project is an aggregator of existing and planned MWS Amazon SDKs projects published under groupId `com.github.chameleontartu` to Maven Central. See [Maven central Search](https://search.maven.org/search?q=com.github.chameleontartu).

Unfortunately, most of MWS Amazon SDKs are not actively maintained, hard to use and there is no a single source of truth where these projects can be retrieved from.

Amazon itself supports only fraction of them into Maven Central, developers migrate to Maven, Gradle only those projects they are interested into working with.

I do believe that this should be changed and I decided to publish all existing Amazon MWS Java SDKs to Maven Central for everyone to benefit from this massive port.

Also, I found myself into situation when SDK was outdated and there was a low chance that developers will fix it, so I had to patch it with my team.

If you agree with me and been in the situations above, this project will be for you.

## Migrated projects

| MWS SDK name  | Build status | GitHub project | Maven central | SDK Amazon Update |
| :------------ | :----------: | :------------- | :-----------: | :---------------- |
| Reports       | [![Build Status](https://travis-ci.org/ChameleonTartu/amazon-mws-reports-maven.svg?branch=master)](https://travis-ci.org/ChameleonTartu/amazon-mws-reports-maven) | [Reports](https://github.com/ChameleonTartu/amazon-mws-reports-maven) | [![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.github.chameleontartu/amazon-mws-reports-maven/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.github.chameleontartu/amazon-mws-reports-maven/) | 2016-09-21 |
| Subscriptions | [![Build Status](https://travis-ci.org/ChameleonTartu/amazon-mws-subscriptions-maven.svg?branch=master)](https://travis-ci.org/ChameleonTartu/amazon-mws-subscriptions-maven) | [Subscriptions](https://github.com/ChameleonTartu/amazon-mws-subscriptions-maven) | [![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.github.chameleontartu/amazon-mws-subscriptions-maven/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.github.chameleontartu/amazon-mws-subscriptions-maven/) | 2014-09-30 |
| Recommendations | [![Build Status](https://travis-ci.org/ChameleonTartu/amazon-mws-recommendations-maven.svg?branch=master)](https://travis-ci.org/ChameleonTartu/amazon-mws-recommendations-maven) | [Recommendations](https://github.com/ChameleonTartu/amazon-mws-recommendations-maven) | [![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.github.chameleontartu/amazon-mws-recommendations-maven/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.github.chameleontartu/amazon-mws-recommendations-maven/) | 2014-10-01 |
| Merchant Fulfillment | [![Build Status](https://travis-ci.org/ChameleonTartu/amazon-mws-merchant-fulfillment-maven.svg?branch=master)](https://travis-ci.org/ChameleonTartu/amazon-mws-merchant-fulfillment-maven) | [Merchant Fulfillment](https://github.com/ChameleonTartu/amazon-mws-merchant-fulfillment-maven) | [![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.github.chameleontartu/amazon-mws-merchant-fulfillment-maven/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.github.chameleontartu/amazon-mws-merchant-fulfillment-maven/) | 2020-02-06 |
| EasyShip | [![Travis CI](https://travis-ci.com/ChameleonTartu/amazon-mws-easyship-maven.svg?branch=master)](https://travis-ci.com/ChameleonTartu/amazon-mws-easyship-maven) | [EasyShip](https://github.com/ChameleonTartu/amazon-mws-easyship-maven) | [![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.github.chameleontartu/amazon-mws-easyship-maven/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.github.chameleontartu/amazon-mws-easyship-maven/) | 2018-09-01 | 
| Fulfillment Inbound Shipment | [![Build Status](https://travis-ci.com/ChameleonTartu/amazon-mws-fulfillment-inbound-shipment-maven.svg?branch=master)](https://travis-ci.com/ChameleonTartu/amazon-mws-fulfillment-inbound-shipment-maven) | [Fulfillment Inbound Shipment](https://github.com/ChameleonTartu/amazon-mws-fulfillment-inbound-shipment-maven) | [![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.github.chameleontartu/amazon-mws-fulfillment-inbound-shipment-maven/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.github.chameleontartu/amazon-mws-fulfillment-inbound-shipment-maven/) | 2016-04-06 | 
| Orders | [![Build Status](https://travis-ci.com/ChameleonTartu/amazon-mws-orders-maven.svg?branch=master)](https://travis-ci.com/ChameleonTartu/amazon-mws-orders-maven) | [Orders](https://github.com/ChameleonTartu/amazon-mws-orders-maven) | [![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.github.chameleontartu/amazon-mws-orders-maven/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.github.chameleontartu/amazon-mws-orders-maven/) | 2020-02-03 |
| Finances | [![Build Status](https://travis-ci.com/ChameleonTartu/amazon-mws-finances-maven.svg?branch=master)](https://travis-ci.com/ChameleonTartu/amazon-mws-finances-maven) | [Finances](https://github.com/ChameleonTartu/amazon-mws-finances-maven) | [![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.github.chameleontartu/amazon-mws-finances-maven/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.github.chameleontartu/amazon-mws-finances-maven/) | 2020-02-21 |
| Feeds | [![Build Status](https://travis-ci.com/ChameleonTartu/amazon-mws-feeds-maven.svg?branch=master)](https://travis-ci.com/ChameleonTartu/amazon-mws-feeds-maven) | [Feeds](https://github.com/ChameleonTartu/amazon-mws-feeds-maven) | [![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.github.chameleontartu/amazon-mws-feeds-maven/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.github.chameleontartu/amazon-mws-feeds-maven/) | 2014-02-01 |

## Projects under migration

- [Fulfillment Inventory](https://github.com/ChameleonTartu/amazon-mws-fulfillment-inventory-maven)

## Planned migrations

The order is the same as the migration is planned. In order to change ordering please submit tickets with or vote for tickets for migrations.

- Fulfillment Outbound Shipment
- Sellers
- Products
- Off-Amazon Payments

## How to support?

If you want to help this project to go, please star it and ports that were useful for you. Submit tickets. Share with your friends and colleagues.
