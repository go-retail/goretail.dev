GO Retail
===
Welcome to GO Retail - A Retail System written (Work in progress) using Go !



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
1. Initially focus on building the apps using GoLang

## Use cases

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

User stories
---

```gherkin=
Feature: Access price for item being scanned and add it to shopping cart

  # The first scenario
  Scenario: 
    Given The customer is validated and a shopping cart has been initiated
    When An item is scanned in a valid way
    Then Retrieve price per unit
    And  Calculate total price of item - (unit price * units) - rebate + tax
    And  Add items and total price to cart
    
    Task: Initiate shopping cart
        Prerequisites:
              temporary Catalog
              Cache
              Table
              tage
        Acceptance Criteria:
            Have a way to 
              

  # The second scenario
  Scenario: 
    Given 
    When 
    Then 

```

User flows
---
```sequence
Title: Here is a title
A->B: Normal line
B-->C: Dashed line
Note left of A: This is a note
C->>D: Open arrow
D-->>A: Dashed open arrow
Note right of D: This is another \nnote
```
