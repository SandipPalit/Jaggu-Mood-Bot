## greet
* greet
  - utter_greet
  
## love
* love
  - utter_love_quotes
  
## thanks
* thanks
  - utter_welcome

## mood happy
* greet
  - utter_greet
* mood_great
  - utter_happy

## greet, mood sad, joke, yes
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_changed_mood
* affirm
  - utter_happy
  
## greet, mood sad, joke, no, joke, yes
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_changed_mood
* deny
  - utter_cheer_up
  - utter_did_that_changed_mood
* affirm
  - utter_happy
   
## greet, mood sad, joke, no, joke, no, joke, yes
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_changed_mood
* deny
  - utter_cheer_up
  - utter_did_that_changed_mood
* deny
  - utter_cheer_up
  - utter_did_that_changed_mood
* affirm
  - utter_happy
   
## greet, mood sad, joke, no, joke, no, joke, no, pikachu, yes
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_changed_mood
* deny
  - utter_cheer_up
  - utter_did_that_changed_mood
* deny
  - utter_cheer_up
  - utter_did_that_changed_mood
* deny
  - utter_pikachu
  - utter_did_that_changed_mood
* affirm
  - utter_happy

## greet, mood sad, joke, no, joke, no, joke, no, pikachu, no, is depressed, no
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_changed_mood
* deny
  - utter_cheer_up
  - utter_did_that_changed_mood
* deny
  - utter_cheer_up
  - utter_did_that_changed_mood
* deny
  - utter_pikachu
  - utter_did_that_changed_mood
* deny
  - utter_depression_symptoms
  - utter_is_depressed
* deny
  - utter_happy    
 
## greet, mood sad, joke, no, joke, no, joke, no, pikachu, no, is depressed, yes, want cure, no, psychiatrist
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_changed_mood
* deny
  - utter_cheer_up
  - utter_did_that_changed_mood
* deny
  - utter_cheer_up
  - utter_did_that_changed_mood
* deny
  - utter_pikachu
  - utter_did_that_changed_mood
* deny
  - utter_depression_symptoms
  - utter_is_depressed
* affirm
  - utter_depression
  - utter_want_cure
* deny
  - utter_psychiatrist  
 
## greet, mood sad, joke, no, joke, no, joke, no, pikachu, no, is depressed, yes, want cure, yes, that helped, yes
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_changed_mood
* deny
  - utter_cheer_up
  - utter_did_that_changed_mood
* deny
  - utter_cheer_up
  - utter_did_that_changed_mood
* deny
  - utter_pikachu
  - utter_did_that_changed_mood
* deny
  - utter_depression_symptoms
  - utter_is_depressed
* affirm
  - utter_depression
  - utter_want_cure
* affirm
  - utter_depression_cure
  - utter_did_that_help
* affirm
  - utter_happy
 
## greet, mood sad, joke, no, joke, no, joke, no, pikachu, no, is depressed, yes, want cure, yes, that helped, no, psychiatrist
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_changed_mood
* deny
  - utter_cheer_up
  - utter_did_that_changed_mood
* deny
  - utter_cheer_up
  - utter_did_that_changed_mood
* deny
  - utter_pikachu
  - utter_did_that_changed_mood
* deny
  - utter_depression_symptoms
  - utter_is_depressed
* affirm
  - utter_depression
  - utter_want_cure
* affirm
  - utter_depression_cure
  - utter_did_that_help
* deny
  - utter_psychiatrist

## mood sad, joke, yes
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_changed_mood
* affirm
  - utter_happy
  
## mood sad, joke, no, joke, yes
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_changed_mood
* deny
  - utter_cheer_up
  - utter_did_that_changed_mood
* affirm
  - utter_happy
   
## mood sad, joke, no, joke, no, joke, yes
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_changed_mood
* deny
  - utter_cheer_up
  - utter_did_that_changed_mood
* deny
  - utter_cheer_up
  - utter_did_that_changed_mood
* affirm
  - utter_happy
   
## mood sad, joke, no, joke, no, joke, no, pikachu, yes
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_changed_mood
* deny
  - utter_cheer_up
  - utter_did_that_changed_mood
* deny
  - utter_cheer_up
  - utter_did_that_changed_mood
* deny
  - utter_pikachu
  - utter_did_that_changed_mood
* affirm
  - utter_happy

## mood sad, joke, no, joke, no, joke, no, pikachu, no, is depressed, no
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_changed_mood
* deny
  - utter_cheer_up
  - utter_did_that_changed_mood
* deny
  - utter_cheer_up
  - utter_did_that_changed_mood
* deny
  - utter_pikachu
  - utter_did_that_changed_mood
* deny
  - utter_depression_symptoms
  - utter_is_depressed
* deny
  - utter_happy    
 
## mood sad, joke, no, joke, no, joke, no, pikachu, no, is depressed, yes, want cure, no, psychiatrist
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_changed_mood
* deny
  - utter_cheer_up
  - utter_did_that_changed_mood
* deny
  - utter_cheer_up
  - utter_did_that_changed_mood
* deny
  - utter_pikachu
  - utter_did_that_changed_mood
* deny
  - utter_depression_symptoms
  - utter_is_depressed
* affirm
  - utter_depression
  - utter_want_cure
* deny
  - utter_psychiatrist  
 
## mood sad, joke, no, joke, no, joke, no, pikachu, no, is depressed, yes, want cure, yes, that helped, yes
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_changed_mood
* deny
  - utter_cheer_up
  - utter_did_that_changed_mood
* deny
  - utter_cheer_up
  - utter_did_that_changed_mood
* deny
  - utter_pikachu
  - utter_did_that_changed_mood
* deny
  - utter_depression_symptoms
  - utter_is_depressed
* affirm
  - utter_depression
  - utter_want_cure
* affirm
  - utter_depression_cure
  - utter_did_that_help
* affirm
  - utter_happy
 
## mood sad, joke, no, joke, no, joke, no, pikachu, no, is depressed, yes, want cure, yes, that helped, no, psychiatrist
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_changed_mood
* deny
  - utter_cheer_up
  - utter_did_that_changed_mood
* deny
  - utter_cheer_up
  - utter_did_that_changed_mood
* deny
  - utter_pikachu
  - utter_did_that_changed_mood
* deny
  - utter_depression_symptoms
  - utter_is_depressed
* affirm
  - utter_depression
  - utter_want_cure
* affirm
  - utter_depression_cure
  - utter_did_that_help
* deny
  - utter_psychiatrist
      
## say goodbye
* goodbye
  - utter_goodbye

## bot challenge
* bot_challenge
  - utter_iamabot
