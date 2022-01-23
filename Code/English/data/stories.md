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



## faq happy path 1
* greet
  - utter_greet
* ask_iterations
  - utter_iterations
* thank
  - utter_welcome
* goodbye
  - utter_goodbye

## faq happy path 2
* greet
  - utter_greet
* ask_date
  - utter_dates
* thank
  - utter_welcome
* goodbye
  - utter_goodbye

## faq happy path 3
* greet
  - utter_greet
* ask_date
  - utter_dates
* bio_eligibility
  - utter_bio
* ask_fee
  - utter_fee
* thank
  - utter_welcome
* goodbye
  - utter_goodbye

## faq happy path 4
* greet
  - utter_greet
* foreign_citizens
  - utter_foreign
* ask_mail
  - utter_mail
* thank
  - utter_welcome
  
## say welcome
* thank
  - utter_welcome

## say goodbye
* goodbye
  - utter_goodbye

## interactive_story_1
* greet
    - utter_greet
* ask_date
    - utter_dates
* goodbye
    - utter_goodbye

## interactive_story_1
* greet
    - utter_greet
* ask_iterations
    - utter_iterations
* goodbye
    - utter_goodbye

## interactive_story_2
* greet
    - utter_greet
* ask_iterations
    - utter_iterations
* ask_date
    - utter_dates
* thank
    - utter_welcome
* goodbye
    - utter_goodbye

## interactive_story_3
* greet
    - utter_greet
* ask_date
    - utter_dates
* ask_fee
    - utter_fee
* bio_eligibility
    - utter_bio
* goodbye
    - utter_goodbye

## interactive_story_4
* greet
    - utter_greet
* ask_fee
    - utter_fee
* ask_iterations
    - utter_iterations
* thank
    - utter_welcome
