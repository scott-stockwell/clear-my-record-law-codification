# Any felony offense where death is an element of the offense

## Law

## Source

## Plan Speak

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

## Logic

```
if charges.conviction_charge_type == Felony

Then
   Charge is 
