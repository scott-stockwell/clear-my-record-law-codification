# Any felony offense where death is an element of the offense


From the statutes we can determine if
* death is an element
* death is NOT an element
* Need to research by reading the statute 
* Not determined

And charge type is a Felony

Down Grading....

## Data Source

MSHP - is the best source of what is charged.
[PLEASE VERIFY]

## Database

* charges.conviction_charge_type: Felony, Misdemeanor, ...
* charges.conviction_class_type: A through X

## Code

```
if charges.conviction_charge_type == Felony

Then
   Charge is NOT expungable
```

