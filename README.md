# Time Off Management

## Project Description

The assignment was to create a Canvas Power App that allows employees and managers to create an account, sign in to their account, and communicate with other members of the organization. All records are stored in a sharepoint list database and of course all fields have required validation. Employees accrue paid time off which is calculated at a different rate for each department. Emplyees specify a reason for their request and a department manager to send their request to. Once the request is submitted, the specified manager will automatically receive an email in which they are given the option to approve or deny the request. That specific manager can also handle requests from their account. Whether the request is approved or denied, the requester will receive an email notifying them of the request status. The request status is also viewable from their account

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
