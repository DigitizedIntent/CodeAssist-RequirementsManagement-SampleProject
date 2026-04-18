# UC-001 Withdraw Cash

> use the id and the use case name as file name

## Details

Id: UC-001
Name: Withdraw Cash
Status: Draft

## Actor & Goals

Actor: Bank Customer
Goal: Successfully withdraw a specific amount of cash from the [ATM](../../00-glossary/ATM.md).

## Precondition

The customer has a valid ATM card and has been authenticated via [PIN](../../00-glossary/PIN.md).

## Main Flow

1. Customer selects "Withdrawal" option.
2. Customer enters the desired amount.
3. System verifies [account balance](../../00-glossary/Account-Balance.md), daily transaction limits, and ATM cash availability.
4. System dispenses cash and prints receipt (if requested).
5. System updates account balance and returns card.

## Alternate Flows/Error Situations

- Insufficient Funds: System notifies user and cancels transaction.
- Daily Limit Exceeded: System notifies user that the amount exceeds their daily [transaction](../../00-glossary/Transaction.md) allowance.
- ATM Out of Cash: System notifies user and suggests a different amount or terminates.

## Postcondition

Cash is dispensed and the user's account balance is debited.

---

> use case template - version 1.0
