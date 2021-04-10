GO Retail ( Work in Progress ) 
===
Welcome to GO Retail - A Retail System (Work in progress) that is being designed as a distributed system handling all of the needs of the current day usecases. 
One of the goal of this project is to demonstrate the key multi-cloud and multi-region  use cases for a ***globally distributed system*** running on modern day cloud platforms. 

<img src="/assets/images/retail-main.jpg">
Any such application or an ecosystem needs the connectivity and data synchronization to be seamless. We will evaluate multiple combinations of technologies around the key challenges that need to be solved to build an efficient and scalable distributed system. 
- Federated queuing
- RDBMS leader-follower
- WAN-Cache 
- Objectstore replication
- Federated identity management
- Manageability and Observability with an SRE model
- Fully automated CI/CD system




## Table of Contents
- [Goals](#goals)
- [Use cases](#use-cases)
- [User stories](#user-stories)
- [User flows](#user-flows)


## Goals

Here are the top level goals of this project

1. Key Retail Scenarios to implement
    1. Catalog and Price Management
    1. Inventory Management
    1. Transaction Processing and Aggregation
    1. POS and sales even during isolation
1. Build and Show case a well designed distributed system
    1. Deal with the Geo distribution of the Stores
    1. Deal with reduced Bandwidth
    1. Deal with Lost conectivity for varied amounts of time
1. Design the system to run on top of a hub and spoke model using Kubernetes based ecosystem
1. Handle the key needs of a real retail ecosystem tking care of an Omni-Channel unification 
    1. In Store
    1. Mobile and Web ( Ecommerce)
1. Demonstrate Cloud Native distributed system management and observability
1. Initially focus on building the apps using GoLang but will keep an open mind to solve the problems using the best tools and libraries available. 

## Use cases ( WIP) 

### Minimum Business Increment
Customer brings item(s) to check out, item is scanned by cashier or self-scanner, bill is calculated, and customer pays for items

1. Access price for item being scanned and add it to shopping cart
2. If item already exists, check cache for itme if already scanned and present, increment item in shopping cart
3. Total + tax calculation
4. Payment processing
5. Inventory update
6. Coupons and rebates
7. Transaction updates
8. Customer loyalty (card/membership)
9. Cancel transactions

