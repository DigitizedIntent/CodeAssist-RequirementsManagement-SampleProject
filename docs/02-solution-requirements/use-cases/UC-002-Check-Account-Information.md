# UC-002 Check Account Information

> use the id and the use case name as file name

## Details

Id: UC-002
Name: Check Account Information
Status: Draft

## Actor & Goals

Actor: Bank Customer
Goal: View current balance and recent activity.

## Precondition

The customer has been [authenticated](../../00-glossary/Authentication.md).

## Main Flow

1. Customer selects "[Account Inquiry](../../00-glossary/Transaction.md)" or "Balance Inquiry".
2. System retrieves account data from the banking backend.
3. System displays the [balance](../../00-glossary/Account-Balance.md) on the screen.

## Alternate Flows/Error Situations

- Backend Timeout: System informs user that information is currently unavailable.

## Postcondition

The customer has viewed their account details.

---

> use case template - version 1.0
