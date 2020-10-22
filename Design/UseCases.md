# Betterflye Use Cases

## Actors

- Initiative Organizers
  - Entities that post initiatives (social-good opportunities) that the community can volunteer for
- Volunteers
  - Anyone who signs up for Betterflye has the intention of volunteering
- Initiative Manager
  - People who work for an initiative and are given the "Manager" role. There can be many initiative managers and they have special privileges for coordinating the initiative.
- Users
  - General users of the application who can send appreciations to each other

## Use Cases

### UC1: Check-in to initiatives (Volunteer self check-in)
  
#### Explanation

When a volunteer is at an initiative, they need to be checked in so that they can validate the time they've spent volunteering. The ideal flow would be:

#### UC1 Simple Flow

1. Volunteer arrives at initiative
2. Volunteer sees signs pointing to check in location
3. The user goes to the check in location
4. The user uses the Betterflye mobile app "Check In" screen to scan a QR Code that will automatically check them in

#### UC1 Actors

- Volunteers

#### UC1 Business Requirement

- BR1

### UC2: Check-in to initiatives (Initiative Manager checks in volunteers)

#### UC2 Explanation

Initiatives can be set up to require initiative managers to check in each volunteer. The ideal flow for this process would be:

#### UC2 Simple Flow

1. Initiative Manager has the Betterflye Mobile application open
2. Volunteers present their individual QR Codes to the initiative manager
3. The initiative manager scans the volunteers QR Code
4. The volunteer is marked as "checked-in"

#### UC2 Actors

- Initiative Manager
- Volunteers

#### UC2 Business Requirement

- BR1

### UC3 Scan a users QR Code to send appreciations

#### UC3 Explanation

In Betterflye, users can send each other virtual currency known as an *appreciation,* to recognize each other. The ideal flow for this would be:

#### UC3 Simple Flow

1. A user wants to send an appreciation to another user
2. The first user obtains the second users QR Code
3. The first user scans the second users QR Code
4. The first user is then navigated to the appreciation page with the second user marked as the appreciation recipient.

#### UC3 Actors

- Users

#### UC3 Business Requirement

- BR1

## Notes

There are more use cases that can be found for our business requirements, but these use cases are the top priority for our client. Every use case that is after this is outside the scope of our planned work.
