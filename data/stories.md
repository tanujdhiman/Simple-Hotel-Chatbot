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

## book room path
* book_room
  - utter_user_want_to_book_room
  - utter_number_of_rooms
  
## clean room path
* clean_room
  - utter_user_want_to_clean_room
  
## what_is_your_check_in_timings path
* what_is_your_check_in_timings
  - utter_what_is_your_check_in_timings

## what_is_your_check_out_timings path
* what_is_your_check_out_timings
  - utter_what_is_your_check_out_timings
  
## how_to_cancel_reservation path
* how_to_cancel_reservation
  - utter_how_to_cancel_reservation
  
## what_is_cancellation_policy path
* what_is_cancellation_policy
  - utter_what_is_cancellation_policy 

## having_restraurant path
* having_restraurant
  - utter_having_restraurant
 
## what_is_the_breakfast_availability path
* what_is_the_breakfast_availability
  - utter_what_is_the_breakfast_availability
  
## what_is_the_breakfast_timings path
* what_is_the_breakfast_timings
  - utter_what_is_the_breakfast_timings
  
## restraurant_timings path 
* restraurant_timings
  - utter_restraurant_timings
