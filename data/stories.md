## premium due happy path

* welcome
  - utter_default_welcome
* GET_PRIV_PREMIUM_DUE
  - utter_premium_due
* any_other_info
  - utter_any_other_info
  - utter_did_that_help
* yes_it_helped
  - utter_happy
  - utter_any_other_info

## premium due sad path

* welcome
  - utter_default_welcome
* GET_PRIV_PREMIUM_DUE
  - utter_premium_due
* any_other_info
  - utter_any_other_info
  - utter_did_that_help
* no_it_did_not_help
  - utter_sorry
  - utter_any_other_info

## fund value happy path

* welcome
  - utter_default_welcome
* GET_PRIV_PUB_FUND_VALUE
  - utter_fund_value
* any_other_info
  - utter_any_other_info
  - utter_did_that_help
* yes_it_helped
  - utter_happy
  - utter_any_other_info

## fund value sad path

* welcome
  - utter_default_welcome
* GET_PRIV_PUB_FUND_VALUE
  - utter_fund_value
* any_other_info
  - utter_any_other_info
  - utter_did_that_help
* no_it_did_not_help
  - utter_sorry
  - utter_any_other_info

## renewal premium receipt happy path

* welcome
  - utter_default_welcome
* GET_PRIV_PREMIUM_DOCS{"PREMIUM_PAYMENT_DOCS":"renewal receipt"}
  - utter_renewal_receipt
* any_other_info
  - utter_any_other_info
  - utter_did_that_help
* yes_it_helped
  - utter_happy
  - utter_any_other_info

## renewal premium receipt sad path

* welcome
  - utter_default_welcome
* GET_PRIV_PREMIUM_DOCS{"PREMIUM_PAYMENT_DOCS":"renewal receipt"}
  - utter_renewal_receipt
* any_other_info
  - utter_any_other_info
  - utter_did_that_help
* no_it_did_not_help
  - utter_sorry
  - utter_any_other_info
  
## premium paid certificate happy path

* welcome
  - utter_default_welcome
* GET_PRIV_PREMIUM_DOCS{"PREMIUM_PAYMENT_DOCS":"premium paid certificate"}
  - utter_renewal_receipt
* any_other_info
  - utter_any_other_info
  - utter_did_that_help
* yes_it_helped
  - utter_happy
  - utter_any_other_info
  
## premium paid certificate sad path

* welcome
  - utter_default_welcome
* GET_PRIV_PREMIUM_DOCS{"PREMIUM_PAYMENT_DOCS":"premium paid certificate"}
  - utter_renewal_receipt
* any_other_info
  - utter_any_other_info
  - utter_did_that_help
* no_it_did_not_help
  - utter_sorry
  - utter_any_other_info

## pay now happy path

* welcome
  - utter_default_welcome
* PAY_NOW_LINK
  - utter_pay_now
* any_other_info
  - utter_any_other_info
  - utter_did_that_help
* yes_it_helped
  - utter_happy
  - utter_any_other_info

## pay now sad path

* welcome
  - utter_default_welcome
* PAY_NOW_LINK
  - utter_pay_now
* any_other_info
  - utter_any_other_info
  - utter_did_that_help
* no_it_did_not_help
  - utter_sorry
  - utter_any_other_info
  
## ways to pay premium happy path

* welcome
  - utter_default_welcome
* WAYS_PAY_PREMIUM
  - utter_ways_to_pay
* any_other_info
  - utter_any_other_info
  - utter_did_that_help
* yes_it_helped
  - utter_happy
  - utter_any_other_info
  
## ways to pay premium sad path

* welcome
  - utter_default_welcome
* WAYS_PAY_PREMIUM
  - utter_ways_to_pay
* any_other_info
  - utter_any_other_info
  - utter_did_that_help
* no_it_did_not_help
  - utter_sorry
  - utter_any_other_info

## change private details(email) happy path

* welcome
  - utter_default_welcome
* CHANGE_PRIV_DETAILS{"PMLI_UPDATE_PERSONAL_DETAILS":"email"}
  - utter_change_email
* any_other_info
  - utter_any_other_info
  - utter_did_that_help
* yes_it_helped
  - utter_happy
  - utter_any_other_info
  
## change private details(bank) happy path

* welcome
  - utter_default_welcome
* CHANGE_PRIV_DETAILS{"PMLI_UPDATE_PERSONAL_DETAILS":"bank account"}
  - utter_change_bank_detail
* any_other_info
  - utter_any_other_info
  - utter_did_that_help
* no_it_did_not_help
  - utter_sorry
  - utter_any_other_info
  
## say goodbye

* goodbye
  - utter_goodbye
