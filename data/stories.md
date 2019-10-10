## happy path
* greet
  - utter_greet
* mood_great
  - utter_happy

## sad path 1
* greet
  - utter_greet
* mood_unhappy
  - utter_did_that_help
* affirm
  - utter_happy

## sad path 2
* greet
  - utter_greet
* mood_unhappy
  - utter_did_that_help
* deny
  - utter_goodbye

## say goodbye
* goodbye
  - utter_goodbye

## bot challenge
* bot_challenge
  - utter_iamabot

## start python
* start_python
  - utter_start_python
    - utter_did_that_help
* deny
  - utter_deny
* affirm
  - utter_affirm

## install python
* install_python
  - utter_install_python
    - utter_did_that_help
* deny
  - utter_deny
* affirm
  - utter_affirm

## test python
* test_python
  - utter_test_python
    - utter_did_that_help
* deny
  - utter_deny
* affirm
  - utter_affirm

## intro django
* intro_django
  - utter_intro_django
    - utter_did_that_help
* deny
  - utter_deny
* affirm
  - utter_affirm

## install django
* install_django
  - utter_install_django
    - utter_did_that_help
* deny
  - utter_deny
* affirm
  - utter_affirm

## install virtual env
* install_virtual_env
  - utter_install_virtual_env
  - utter_did_that_help
* deny
  - utter_deny
* affirm
  - utter_affirm