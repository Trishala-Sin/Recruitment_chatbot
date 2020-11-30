## intent:greet
- hey
- hello
- hi
- hello there
- good morning
- good evening
- moin
- hey there
- hi again
- hey dude
- goodmorning
- goodevening
- good afternoon
- howdy
- What's up
- wassup
- who are you ?
- what are you ?
- greetings
- hi there
- hola
- Hi

## intent:greet_position_enquiry
- hey ! could you let me know about the open positions here
- hello, could you tell me about the openings at rasa
- wanna know about current openings
- I want to know about vacancies
- could you show mw some job postings ?
- Can I see some managerial positions that are avaible
- hey bot, I'd like to know about open positions
- hi, could you please tell me which positions are open right now ?
- Hey, I would like to get a job with you
- hi pal, could you let me know about current openings at rasa ?
- greetings, do you have a job?
- Hi there, do you have any vacancies ?
- Hi do you have openings ?
- Hello, I would like to get a job with rasa
- Show me available job openings
- could you please list current open positions at rasa ?
- hello anybody there, can you show me current open positions at rasa ?
- hello anybody there, can I know about current positions ?
- My name is [Trishala Singh](visitor_name). Show me all openings with rasa ?

## intent:Application_status_enquiry
- Could you let me know about my application status?
- I want to know about my application status
- application status
- application
- status
- I wanna know about my application status
- hello, I have applied for a job and would like to know when I'll hear back
- I would like to know about my application status
- Could you please update me regading my job application status?
- where can I have an update on my application status?
- I haven't heard back on my application.
- I have applied for a job. How can I have update on application status?
- what's update on my application status ?
- application status update
- Can I have update on my application status ?
- Hi could you please let me know about my application status ?
- I have applied for the job and would like to know when I'll hear back
- Hi I want to check status of my job application

## intent:Person_name
- Hi, my name is [Ali Park](visitor_name).
- hi I am [Ali](visitor_name)
- I am [Ella](visitor_name)
- This is [Steve](visitor_name)
- I am [paul walker](visitor_name)
- [Martha](visitor_name)
- [Ali Park](visitor_name)
- I am [joe](visitor_name)
- My name is [Joseph](visitor_name)
- I'm [joe](visitor_name)
- Hi I'm [Crystal](visitor_name)
- hey [George](visitor_name) this side
- [joe](visitor_name) this side
- [Maria Khan](visitor_name)
- [Christie](visitor_name)
- [Jiah sharma](visitor_name)
- Trishala Singh

## intent:Position_enquiry
- I am looking for work opportunities at RASA
- openings
- open positions
- current job openings
- vacancies
- I’d like to know which positions are open right now
- I am looking forward to work with RASA
- wanna know about [technical](role_type) openings
- I want to ask about [Business]{"entity": "role_type", "value": "business"} role related vacancies
- I want to know about job openings for [business](role_type) roles
- I would like to know about work opportunities at RASA
- Could you let me know kind of roles avaible where position is vacant
- looking for job opportunities at RASA
- Kindly let me know job vacancy at RASA
- I am looking for [Technical]{"entity": "role_type", "value": "technical"} here
- Show me vacant positions for work opportunity at rasa
- Any business roles available for experince candidate ?
- Any [roles]{"entity": "role_type", "value": "any"} available for fresher candidate ?
- vacancy for experienced [ML Engineer]{"entity": "role_type", "value": "technical"}
- Do you have any openings ?
- Do you have any positions open ?
- [business](role_type)
- can I see some of the business roles openings ?
- can I see some of the [Technical]{"entity": "role_type", "value": "technical"} roles
- Seeking some [tech]{"entity": "role_type ", "value": " technical"} available at RASA
- Seeking some [management]{"entity": "role_type", "value": "business"} available at RASA
- Could you please confirm if there is any vacancy for [machine learning engineer] {"entity": "role_type" , "value": "technical"}?
- I would like to know about the positions available for job application
- Please show mw the vacant positions for [ML product success engineer]{"entity": "role_type", "value": "technical"}
- [Solution engineer]{"entity": "role_type", "value": "business"}
- A [technical](role_type) one
- A [business](role_type) one
- I would like to see any [technical](role_type) openings
- could you show me [any](role_type) of the current open positions ?
- I 'm [joe](visitor_name). looking for [technical](role_type) role at rasa. help me with current job postings
- show me current open position for [business](role_type) manager?

## intent:visitor_query
- Hi, my name is [ALi Park](visitor_name). I applied for a job an would like to know when I"ll hear back
- hello I am [crystal](visitor_name). Is there any update on my job application
- Hi I am [Ella](visitor_name).please update on my job application status
- Hi I am [Ella](visitor_name). Help me finding my application status
- Hi [Priya](visitor_name) this side. Looking for update on my job application
- I am [Emile](visitor_name) and I would like to get an update on my job application
- Hi My name is [Ali Park](visitor_name) and I have applied for a job, I'd like to know when I will hear back ?

## intent:goodbye
- see you later
- nice talking to you bye
- goodbye
- have a nice day
- see you around
- bye bye

## intent:affirm
- yes
- y
- indeed
- of course
- that sounds good
- correct
- ok

## intent:deny
- no
- n
- never
- I don't think so
- don't like that
- no way
- not really
- Nah
- Nope
- No
- Thanks
- ok thanks
- thanx

## intent:bot_challenge
- are you a bot?
- are you a human?
- am I talking to a bot?
- am I talking to a human?

## synonym: Business
- [business]{"entity": "role_type", "value": "Business"}

## synonym: technical
- tech

## synonym:Technical
- [technical]{"entity": "role_type", "value": "technical"}
- [tech]{"entity": "role_type", "value": "technical"}
- [technology]{"entity": "role_type", "value": "technical"}

## synonym:any
- roles

## synonym:business
- Business
- management
- Solution engineer

## synonym:technical
- Technical
- ML Engineer
- ML product success engineer

## regex:greet
- hey[^\\s]*
- hi[^\s]*
