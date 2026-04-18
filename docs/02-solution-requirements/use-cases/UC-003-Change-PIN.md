# UC-003 Change PIN

> use the id and the use case name as file name

## Details

Id: UC-003
Name: Change PIN
Status: Draft

## Actor & Goals

Actor: Bank Customer
Goal: Change the [ATM](../../00-glossary/ATM.md) card [PIN](../../00-glossary/PIN.md) for security purposes.

## Precondition

The customer is authenticated with their current [PIN](../../00-glossary/PIN.md).

## Main Flow

1. Customer selects "Change PIN" from the security menu.
2. Customer enters the new PIN.
3. Customer re-enters the new PIN to confirm.
4. System updates the PIN in the banking database.

## Alternate Flows/Error Situations

- PIN Mismatch: System asks the user to re-enter and confirm again.
- Weak PIN: System rejects common/simple patterns (e.g., 1234).

## Postcondition

The customer's PIN is updated, and the old PIN is no longer valid.

---

> use case template - version 1.0