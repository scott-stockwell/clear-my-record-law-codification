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

## Information Needed

We neet to know:

1. If the charge is a felony.  The database currently has * charges.conviction_charge_type: Felony, Misdemeanor, ...
2. If the charge resulted in a death.  
   * Statutes.  565.020 through .034 are ones that we should looks at (Beth)
   * Other list we created
   * The statute normaly has the text "casues the death of another/any person"

Senario:

If they are recklessly  driving their motor scooter and kill someone, they would be charged with:
* Recklessly driving their motor scooter
* One of the "causes the death of..." from 565.020 through .034

### Charge is a felony



### Case information
MSHP - is the best source of what is charged.
[PLEASE VERIFY]

CaseNet - "Charges Judgement and Sentences". They do have the statute number
[PLEASE VERIFY]

### Statute



If they are reclusly driving their moter scutor they would also charge .020 to .034

## Database


* charges.conviction_class_type: A through X
* ADD statute.death_is_a_element

## Logic

```
if charges.conviction_charge_type == Felony

Then
   Charge is 
