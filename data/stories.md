 <!-- ## bill path
* greet
  - utter_greet
  - utter_ask_client
* confirm_client
  - utter_ask_ppe
* confirm_ppe
  - utter_help
* choose{"operation":"bill"}
  - action_bill

## saldo path
* greet
  - utter_greet
  - utter_ask_client
* confirm_client
  - utter_ask_ppe
* confirm_ppe
  - utter_help
* choose{"operation":"saldo"}
  - action_saldo

## meter_read path
* greet
  - utter_greet
  - utter_ask_client
* confirm_client
  - utter_ask_ppe
* confirm_ppe
  - utter_help
* choose{"operation":"meter_read"}
  - action_meter_read -->

<!-- ## happy path 1
* greet
  - utter_greet
* mood_great
  - utter_happy
  - utter_ask_name
* name_inform{"name":"Kamil"}
  - utter_greet_name
* too
  - utter_respond_thanks
## sad path 1
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* affirm
  - utter_happy
  - utter_ask_name
* name_inform{"name":"Kamil"}
  - utter_greet_name
* too
  - utter_respond_thanks

## sad path 2
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* deny
  - utter_goodbye -->

## say goodbye
* goodbye
  - utter_goodbye

## bot challenge
* bot_challenge
  - utter_iamabot

## story_joke_01
* joke
 - action_joke

 ## say location
 * location
  - utter_location

## say thanks
* thanks
 - utter_thanks  

## bot insult
* insult
  - utter_respond_insult

## boy name
* ask_name
  - utter_respond_name

## ask creator
* creator
  - utter_respond_creator

## ask age
* age
  - utter_respond_age

## interactive_story_1
* greet
    - utter_greet
    - client_form
    - form{"name": "client_form"}
    - slot{"requested_slot": "client"}
* form: confirm_client{"client": "55555555"}
    - form: client_form
    - slot{"client": "55555555"}
    - slot{"requested_slot": "pesel"}
* form: confirm_pesel{"pesel": "65062479537"}
    - form: client_form
    - slot{"pesel": "65062479537"}
    - form{"name": null}
    - slot{"requested_slot": "null"}
    - utter_slots_values
    - utter_help
* choose{"operation": "meter_read"}
    - slot{"operation": "meter_read"}
    - action_meter_read
* thanks
    - utter_thanks  

## interactive_story_2
* greet
    - utter_greet
    - client_form
    - form{"name": "client_form"}
    - slot{"requested_slot": "client"}
* form: confirm_client{"client": "11111111"}
    - form: client_form
    - slot{"client": "11111111"}
    - slot{"requested_slot": "pesel"}
* form: confirm_pesel{"pesel": "50102231284"}
    - form: client_form
    - slot{"pesel": "50102231284"}
    - form{"name": null}
    - slot{"requested_slot": null}
    - utter_slots_values
    - utter_help
* choose{"operation": "saldo"}
    - slot{"operation": "saldo"}
    - action_saldo
* thanks
    - utter_thanks

## interactive_story_3
* greet
    - utter_greet
    - client_form
    - form{"name": "client_form"}
    - slot{"requested_slot": "client"}
* form: confirm_client{"client": "22222222"}
    - form: client_form
    - slot{"client": "22222222"}
    - slot{"requested_slot": "pesel"}
* form: confirm_pesel{"pesel": "79051479923"}
    - form: client_form
    - slot{"pesel": "79051479923"}
    - form{"name": null}
    - slot{"requested_slot": null}
    - utter_slots_values
    - utter_help
* choose{"operation": "bill"}
    - slot{"operation": "bill"}
    - action_bill
* thanks
    - utter_thanks