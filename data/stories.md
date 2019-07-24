## happy path
* greet
  - utter_greet
* mood_great
  - utter_happy

## who are you
* who_are_you
  - utter_i_am_virtual_assistant

## sad path 1
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* affirm
  - utter_great_to_hear

## sad path 2
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* deny
  - utter_goodbye

## say goodbye
* goodbye
  - utter_goodbye
