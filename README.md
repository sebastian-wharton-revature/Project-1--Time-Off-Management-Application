# Time Off Management

## Project Description

We are tasked with creating a Microsoft Dynamics 365 CRM Canvas application in which users inside of an organization would have the ability to request Time Off. The Time Off Application houses a variety of reasons and various balances for each predefined term of leave. This leave request then needed an approval by a Manager figure either through the automated email that is sent when a request is submitted, or when the manager logs into the application. Users can log in to a current account or register for an account. User then have a profile page they can access and change all aspect of their profile that includes a profile photo and excludes changing their department and job title. Time Off Leaves are calculated dynamically and updated in real-time through the application and stored onto the database on the back end through SharePoint. 

## Technologies Used

* Microsoft Dynamics 365 Power Apps: Canvas
* Microsoft SharePoint
* Microsoft Power Automate
* Microsoft Dynamics 365 Users

## Features

* Secure Signin/Signout
* Secure Registration
* Dynamically Displayed and Updated Profile Page with Profile Photo
* PTO Requests Dynamically updated based on the user making the request
* Users able to make requests and check the request status
* Managers receive an email upon a request submission
* Managers can see all employees of the organization under their management
* Managers can approve/deny the request on log in
* Users are notified when their request has been answered
* Sharepoint dynamically stores the response through power automate

## Ideas for Improvement

* Adding a Clock-in/ Clock-out functionality for users to begin their day and start tallying up pay.
* Using that Clock-in/ Clock-out functionality to generate pay using SharePoint calculated columns.
* Resetting the Leave Balance yearly for static balances and accrued for earned leave by day.
