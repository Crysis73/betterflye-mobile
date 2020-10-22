# Domain Model

![Domain Model](Domain%20Chart%20for%20Betterflye.png)

## User

The user is any user of the application. Users can create organizations, volunteer at initiatives, send notifications to other users, and sign up for initiative shifts. They also have about 9 badges that they can earn.

## Notifications

Notifications are literal notifications that users get sent. Upon logging in, the web application queries all notifications that are associated with a given userId that have not been read and displays them to the user. The main type of notification we're concerned with is an appreciation, which users can send to each other, to recognize the impact that a user has had.

## Organizations

Organizations are groups with a purpose they'd like to achieve. Betterflye currently is only allowing verified organizations like non-profits to create a Betterflye organization. Using betterflye, organizations can create initiatives to achieve goals.

## OrgNotification

OrgNotifications are a pre existing table that is literally just a notification but organization specific.

## Initiatives

Initiatives are events that organizations can host. There are a few different types of initiatives including volunteering, donating, and in-kind initiatives that organizations can currently host.

## InitiativeShift

Initiatives can have many initiative shifts. Initiative shifts are just shifts that users can sign up for if they want to attend the initiative. Not every initiative will have shifts, because you wouldn't really need a designated time slot for a donation type initiative.