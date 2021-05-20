## happy path and asking time
* greet
  - utter_greet
  - utter_ask_mood
* mood_great
  - utter_happy
* find_time
  - utter_ask_location
* city_info
  - utter_finding_time_zone
  - action_find_and_show_time_zone
* thanks
  - utter_welcome
  - utter_goodbye

## sad path 1 and asking time
* greet
  - utter_greet
  - utter_ask_mood
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* affirm
  - utter_happy
* find_time
  - utter_ask_location
* city_info
  - utter_finding_time_zone
  - action_find_and_show_time_zone
* thanks
  - utter_welcome
  - utter_goodbye

## sad path 2 and asking time
* greet
  - utter_greet
  - utter_ask_mood
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* deny
  - utter_sorry
* find_time
  - utter_ask_location
* city_info
  - utter_finding_time_zone
  - action_find_and_show_time_zone
* thanks
  - utter_welcome
  - utter_goodbye

