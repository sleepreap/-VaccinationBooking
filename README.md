# -VaccinationBooking Using UiPath


## Introduction
## Purpose
The purpose of this document is to build automation to improve booking processes. This is to address mundane and tedious booking processes where staffs have to check of apppointment slots and confirm with clients their free timeslots before the appointment can be booked. This requires several back and forth emails which can made redundent with the automation. 


## Product Scope
A Vaccination booking Automation that filters out your calendar free timeslots automatically based on your desired time and location. The automation would book the vaccination on HeathHub and create the event on your Google Calendar. The automation also allows for cancellation or rescheduling of Vaccination appointments. Cancelling and rescheduling will automatically edit your google calendar as well. 

## Requirements
In order for the automation to work properly, you need to provide the following:
- Your ClientID from OAuth 2.0 Client IDs
- Your ClientSecret from OAuth 2.0 Client IDs
- CalendarID from Google Calendar

![image](https://github.com/sleepreap/-VaccinationBooking/assets/98008874/130b6219-f799-4803-83e5-18f281053011)
- The ClientID and ClientSecret can be created from creating an APi key from console.developers. google.com/

![image](https://github.com/sleepreap/-VaccinationBooking/assets/98008874/29b060cb-5e27-4671-b63f-51f6bc247513)


- The CalendarID can be found under Google Calendar settings

## Dependencies:
- Google Calendar
- Singpass for HealthHub
