## happy path

- greet
  - utter_greet
- mood_great
  - utter_happy

## premium due happy path

- welcome
  - utter_default_welcome
- premium_due
  - utter_premium_due
- any other info
  - utter_any_other_info
- did that help
  - utter_did_that_help
- yes it helped
  - utter_happy
  - utter_any_other_info

## premium due sad path

- welcome
  - utter_default_welcome
- premium_due
  - utter_premium_due
- any other info
  - utter_any_other_info
- did that help
  - utter_did_that_help
- no it did not help
  - utter_sorry
  - utter_any_other_info

## fund value happy path

- welcome
  - utter_default_welcome
- fund_value
  - utter_fund_value
- any_other_info
  - utter_any_other_info
- did_that_help
  - utter_did_that_help
- yes_it_helped
  - utter_happy
  - utter_any_other_info

## fund value sad path

- welcome
  - utter_default_welcome
- premium_due
  - utter_fund_value
- any other info
  - utter_any_other_info
- did that help
  - utter_did_that_help
- no it did not help
  - utter_sorry
  - utter_any_other_info

## renewal premium receipt happy path

- welcome
  - utter_default_welcome
- premium_due
  - utter_renewal_receipt
- any other info
  - utter_any_other_info
- did that help
  - utter_did_that_help
- yes it helped
  - utter_happy
  - utter_any_other_info

## renewal premium receipt sad path

- welcome
  - utter_default_welcome
- premium_due
  - utter_renewal_receipt
- any other info
  - utter_any_other_info
- did that help
  - utter_did_that_help
- no it did not help
  - utter_sorry
  - utter_any_other_info

## pay now happy path

- welcome
  - utter_default_welcome
- premium_due
  - utter_pay_now
- any other info
  - utter_any_other_info
- did that help
  - utter_did_that_help
- yes it helped
  - utter_happy
  - utter_any_other_info

## pay now sad path

- welcome
  - utter_default_welcome
- premium_due
  - utter_pay_now
- any other info
  - utter_any_other_info
- did that help
  - utter_did_that_help
- no it did not help
  - utter_sorry
  - utter_any_other_info

## say goodbye

- goodbye
  - utter_goodbye

## bot challenge

- bot_challenge
  - utter_iamabot
