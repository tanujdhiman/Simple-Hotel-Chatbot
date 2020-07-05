
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

## want room
* want_room
  - utter_room

## sim path
* simple
  - utter_sim

## del path
* delux
  - utter_del

## clean room
* clean_room
  - utter_clean

## right path
* right_now
  - utter_rp

## time path
* relative_time
  - utter_rt

## in path
* check_in
  - utter_check_in_timings

## out path
* check_out
  - utter_check_out_timings

## cancel path
* cancel_reservation
  - utter_cancel_reser

## policy path
* cancellation_policy
  - utter_policy

## rest path
* restraurant
  - utter_rest

## breakfast path
* breakfast_availability
  - utter_avail

## breakfast_timings
* breakfast_timings
  - utter_b_time

## rest time path
* restraurant_timings
  - utter_r_time
