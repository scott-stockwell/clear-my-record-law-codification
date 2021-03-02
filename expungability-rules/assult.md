# Any felony offense where death is an element of the offense

## Law

610.140 2 (5)  Any felony offense of assault; misdemeanor or felony offense of domestic assault; or felony offense of kidnapping;

Is the statute for assult?
   Is charges.conviction_charge_type a misdemeanor or felony
       Cannot be expunged

Is the statute domestic assault?
   Is charges.conviction_charge_type a felony
       Cannot be expunged

Is the statue a kidnapping?
   Is charges.conviction_charge_type a felony
       Cannot be expunged

## Plan Speak

## Training

*What we need to tell pro bono attornies* 


## Information Needed

We neet to know:

1. If the charge is convicted as a felony.


Assumptions:

* This applies to the charge and does not disqualify the case.
  
Senario:

If they are recklessly  driving their motor scooter and kill someone, they would be charged with:
* Recklessly driving their motor scooter (Felony). does not mention anything about death
* One of the "causes the death of..." from 565.020 through .034

What happens if they "Down Grade" to a M?


## UX


## Database




### Add  flag



How to initalize?



How to maintain?

1. Have someone watch the changes in law
2. Have lawyers look for errors (sanity check)

## Logic

```
if charges.conviction_charge_type == Felony

```

