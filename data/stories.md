## tell a joke
* tell_me_a_joke
  - utter_tell_joke

## happy path
* greet
  - utter_greet
* mood_great
  - utter_happy

## sad path 1
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* affirm
  - utter_happy

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

## bot challenge
* bot_challenge
  - utter_iamabot

## New Story

* greet
    - utter_greet
* mood_great
    - utter_happy

## New Story

    - utter_greet
* greet
    - utter_cheer_up
    - utter_did_that_help
* affirm
    - utter_happy

## New Story

    - utter_greet
* greet
* mood_great
    - utter_happy

## New Story

* greet
    - utter_greet
    - utter_cheer_up
* mood_unhappy
    - utter_did_that_help
    - utter_happy
* affirm
