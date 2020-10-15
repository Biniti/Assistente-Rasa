## happy path
*greet
    - utter_greet
* mood_great
    - utter_happy
## nenhum
* greet
    - utter_greet
* deny
    - utter_deny
    - utter_goodbye
## sad path 2
* greet
    - utter_greet
* mood_unhappy
    - utter_cheer_up    
    - utter_did_that_help
* deny
    - utter_goodbye
##say goodbye
* goodbye
    - utter_goodbye
##bot challenge
* bot_challenge
    - utter_iamabot
##police path
* greet
    - utter_greet
* police_acess
    - utter_police_acess
##fireman path
* greet
    - utter_greet
* fireman_acess
    - utter_fireman_acess

## Marinha path
* greet
    - utter_greet
* marinha_acess
    - utter_marinha_acess

## Forças aereas(AFA) path
* greet
    - utter_greet
* AFA_acess
    - utter_AFA_acess

## Serviço militar path
* greet
    - utter_greet
* ServicoMilitar_acess
    - utter_militar_acess