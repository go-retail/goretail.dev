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
