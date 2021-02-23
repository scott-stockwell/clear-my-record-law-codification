# Any class A felony offense (Can Not be expunged)

We will look at the Level &. ... to determine how the charge was clasified

## Data Source

MSHP - is the best source of what is charged.
[PLEASE VERIFY]

## Database

* charges.conviction_charge_type: Felony, Misdemeanor, ...
* charges.conviction_class_type: A through X

## Code

```
if charges.conviction_charge_type == Felony
and charges.conviction_class_type == A
Then
   Charge is NOT expungable
```
