## premium due happy path

* welcome
  - utter_default_welcome
* GET_PRIV_PREMIUM_DUE
  - utter_premium_due
* any_other_info
  - utter_any_other_info
* did_that_help
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
* did_that_help
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
* did_that_help
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
* did_that_help
  - utter_did_that_help
* no_it_did_not_help
  - utter_sorry
  - utter_any_other_info

## renewal premium receipt happy path

* welcome
  - utter_default_welcome
* {"PREMIUM_PAYMENT_DOCS":"receipt"}
  - utter_renewal_receipt
* any_other_info
  - utter_any_other_info
* did_that_help
  - utter_did_that_help
* yes_it_helped
  - utter_happy
  - utter_any_other_info

## renewal premium receipt sad path

* welcome
  - utter_default_welcome
* renewal_receipts {"PREMIUM_PAYMENT_DOCS":"receipt"}
  - utter_renewal_receipt
* any_other_info
  - utter_any_other_info
* did_that_help
  - utter_did_that_help
* no_it_did_not_help
  - utter_sorry
  - utter_any_other_info

## pay now happy path

* welcome
  - utter_default_welcome
* pay_now
  - utter_pay_now
* any_other_info
  - utter_any_other_info
* did_that_help
  - utter_did_that_help
* yes_it_helped
  - utter_happy
  - utter_any_other_info

## pay now sad path

* welcome
  - utter_default_welcome
* pay_now
  - utter_pay_now
* any_other_info
  - utter_any_other_info
* did_that_help
  - utter_did_that_help
* no_it_did_not_help
  - utter_sorry
  - utter_any_other_info

## say goodbye

* goodbye
  - utter_goodbye

## bot challenge

* bot_challenge
  - utter_iamabot
