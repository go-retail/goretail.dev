GO Retail
===
Welcome to GO Retail - A Retail System written (Work in progress) using Go !



## Table of Contents

[TOC]

## Goals

Here are the top level goals of this project

1. Key Retail Scenarios to implement
    a. Catalog and Price Management
    b. Inventory Management
    c. Transaction Processing and Aggregation
    d. POS and sales even during isolation
1. Build and Show case a well designed distributed system
    a. Deal with the Geo distribution of the Stores
    b. Deal with reduced Bandwidth
    c. Deal with Lost conectivity for varied amounts of time
1. Design the system to run on top of a hub and spoke model using Kubernetes based ecosystem
1. Handle the key needs of a real retail ecosystem tking care of an Omni-Channel unification 
    a. In Store
    b. Mobile and Web ( Ecommerce)
1. Demonstrate Cloud Native distributed system management and observability
1. Initially focus on building the apps using GoLang

## Use cases

Here be use cases we are going to target

User stories
---

```gherkin=
Feature: Catalog management

  # The first scenario
  Scenario: 
    Given 
    When 
    Then 

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
