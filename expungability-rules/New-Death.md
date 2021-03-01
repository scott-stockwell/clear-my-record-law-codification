# Any felony offense where death is an element of the offense

## Law

Any felony offense where death is an element of the offense





## Plan Speak

## Something

From the statutes we can determine if
* death is an element
* death is NOT an element
* Need to research by reading the statute 
* Not determined

And charge type is a Felony

Down Grading....

## Data Source of Data

### Case information
MSHP - is the best source of what is charged.
[PLEASE VERIFY]

CaseNet - "Charges Judgement and Sentences". They do have the statute number
[PLEASE VERIFY]

### Statute

Look through statute.  565.020 through .034

Normaly has the text "casues the death of another/any person"

If they are reclusly driving their moter scutor they would also charge .020 to .034

## Database

* charges.conviction_charge_type: Felony, Misdemeanor, ...
* charges.conviction_class_type: A through X
* ADD statute.death_is_a_element

## Logic

```
if charges.conviction_charge_type == Felony

Then
   Charge is 
