
## interactive_story_1
* greet
    - utter_greet
* Position_enquiry{"role_type": "technical"}
    - slot{"role_type": "technical"}
    - utter_tovisitor_response
    - action_check_positions
    - slot{"positions": ["machine learning engineer", "ML product success engineer"]}
    - utter_knowmore
* affirm
    - utter_utilities
* Application_status_enquiry
    - utter_ask_Person_info
* Person_name{"visitor_name": "Jiah sharma"}
    - slot{"visitor_name": "Jiah sharma"}
    - action_check_status
    - slot{"status": "unknown"}
    - utter_knowmore
* deny
    - utter_goodbye
    
## happy path1
* greet
  - utter_greet
* position_enquiry
  - utter_greet_position_enquiry
  - action_check_positions
* utter_knowmore
  - utter_utilities
* Application_status_enquiry
  - utter_ask_Person_info
* Person_name
  - utter_tovisitor_response
  - action_check_status
  - utter_goodbye


## happy path2
* greet
  - utter_greet
* position_enquiry
  - utter_greet_position_enquiry
  - action_check_positions
  - utter_goodbye
  

## bot challenge
* bot_challenge
  - utter_iamabot
  
## say goodbye
* greet
  - utter_greet
* goodbye
  - utter_goodbye

## interactive_story_2
* greet
    - utter_greet
* visitor_query{"visitor_name": "Emile"}
    - slot{"visitor_name": "Emile"}
    - utter_tovisitor_response
    - action_check_status
    - slot{"status": "interview"}
* affirm
    - utter_knowmore
* affirm
* Position_enquiry{"role_type": "any"}
    - slot{"role_type": "any"}
    - action_check_positions
    - slot{"positions": ["machine learning engineer", "ML product success engineer"]}
* deny
    - utter_goodbye

## interactive_story_3
* visitor_query{"visitor_name": "Ali Park"}
    - slot{"visitor_name": "Ali Park"}
    - utter_tovisitor_response
    - action_check_status
    - slot{"status": "received"}
    - utter_knowmore
* deny
    - utter_goodbye

## interactive_story_4
* greet
    - utter_greet
* Position_enquiry{"visitor_name": "joe", "role_type": "technical"}
    - slot{"role_type": "technical"}
    - slot{"visitor_name": "joe"}
    - utter_tovisitor_response
    - action_check_positions
    - slot{"positions": ["machine learning engineer", "ML product success engineer"]}
    - utter_knowmore
* Position_enquiry{"role_type": "business"}
    - slot{"role_type": "business"}
    - action_check_positions
    - slot{"positions": []}
* deny
    - utter_goodbye

## interactive_story_1
* Application_status_enquiry
    - utter_ask_Person_info
* Person_name
    - utter_tovisitor_response
    - action_check_status
    - slot{"status": "received"}
    - utter_goodbye

## interactive_story_1
* greet
    - utter_greet
* greet_position_enquiry{"visitor_name": "Trishala Singh"}
    - slot{"visitor_name": "Trishala Singh"}
    - utter_tovisitor_response
    - action_check_positions
    - slot{"positions": []}
* deny
    - utter_goodbye
