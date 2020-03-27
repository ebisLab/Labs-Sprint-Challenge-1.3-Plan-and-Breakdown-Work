
# Labs-Sprint-Challenge-1.3-Plan-and-Breakdown-Work

## Prompt 1: Vision Planning Session 

#### Break down process of the first release.


<img src="https://github.com/ebisLab/Labs-Sprint-Challenge-1.3-Plan-and-Breakdown-Work/blob/master/Screen%20Shot%202020-03-27%20at%2011.18.57%20AM.png?raw=true">



<img src="https://github.com/ebisLab/Labs-Sprint-Challenge-1.3-Plan-and-Breakdown-Work/blob/master/Screen%20Shot%202020-03-27%20at%2011.20.43%20AM.png?raw=true">


###  User Stories

1. As an event manager, I want a user interface to easily enter attendee data, so that I can keep track of financial and demographic information.
2. As a business manager, I want a user interface that will save me time, so that I have more time for beer and classical music.
3. As an owner of a not-for-profit business I want the ability to aggregate demographic information from people. This is crucial for writing government grants.
4. As a volunteer I want a simple & straightforward app that I can use to log my time, data for areas I am responsible for, and sign up to help with events.

Design choice behind one of the flow. (UX students only):

`
As an event manager, I want a user interface to easily enter attendee data, so that I can keep track of financial and demographic information.
`

The UX team came out with this flow for our stake holder's request, and we feel that this complies with the requirement from both the stakeholder and lambda labs objective

<img src="https://github.com/ebisLab/Labs-Sprint-Challenge-1.3-Plan-and-Breakdown-Work/blob/master/Admin%20Input%20Data%20Flow.png?raw=true">

`Admin `=> `[Container with {button}]` => redirects to => `[form page]` => `{submit button}` => `Preview page` => `Submit`                                                                                or `Cancel`
 
 The color choices, button shape, space utilized is a user friendly approach for those who need simplicity and can help navigate those who aren't computer savy.                                                                                                    
                                                                                                     
## Prompt 2 - Tasks assigned to me.


This portion will allow the user to input the necessary fields so that they can capture it in the database. The goal is to be able to access the data once we have a search filter feature implemented. 

We have a shared task to style and create the volunteer card 

<img src="https://github.com/ebisLab/Labs-Sprint-Challenge-1.3-Plan-and-Breakdown-Work/blob/master/Screen%20Shot%202020-03-27%20at%2012.24.33%20PM.png?raw=true">

- My portion is to get the form functional, or at least the inputs functional. The problem I'm running into is that we are using 2 main libraries (antd and React Hook Form) and it's conflicting with the functionality main functionality.
- I was able to get the validation to work, the one remaining task is to get the data to be captured. 
- My plan is to use one simple form, get it validated, get the data to be captured, connect it to the backend through graphQL, do the CRUD operations to get it to interact with the already captured data and new data, and then roll it out the rest of the form.

This is a demo of what must happen in the DOM (look in the console for broad picture) 
https://codesandbox.io/s/react-hook-form-errormessage-y53w5


<img src="https://github.com/ebisLab/Labs-Sprint-Challenge-1.3-Plan-and-Breakdown-Work/blob/master/Screen%20Shot%202020-03-27%20at%2012.27.35%20PM.png?raw=true">




<img src="https://github.com/ebisLab/Labs-Sprint-Challenge-1.3-Plan-and-Breakdown-Work/blob/master/Screen%20Shot%202020-03-27%20at%2012.28.53%20PM.png?raw=true">


Steps to complete task: 

- I'm still looking into the docs for more examples. I'M SO CLOSE! 
- Once this is handled, this will be connected to the graphQL portion that will connect to the backend. It shouldn't take too long to complete.


User Story Quiz (Non-UX Students Only)

https://trello.com/b/PCMe6Zza/labs-22-quiz-lambda-bnb


