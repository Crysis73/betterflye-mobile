# Betterflye Requirements

## Functional Requirements

- FR1: A volunteer must have a QR Code associated with a unique identifier
  - Business Requirement: BR1
  - Priority: High
- FR2: An initiative must have a QR Code associated with a unique identifier
  - Business Requirement: BR1
  - Priority: High
- FR3: The application must be able to scan a QR Code using the devices camera
  - Business Requirement: BR1
  - Priority: High
- FR4: The application must allow existing users to login to the application.
  - Business Requirement: BR2
  - Priority: High
- FR5: The application must allow new users to create an account
  - Business Requirement: BR2
  - Priority: High
- FR6: The application must allow users to send appreciations to each other
  - Business Requirement: BR2.
  - Priority: High

### UC1 Functional Requirements

- FR7: When a volunteer scans an Initiative's QR Code, the volunteer should be marked as "checked-in," for that initiative
  - Business Requirement: BR1
  - Priority: High

### UC2 Functional Requirements

- FR8: When an initiative manager scans a volunteers QR Code, that user should be marked as "checked-in," for that initiative
  - Business Requirement: BR1
  - Priority: High

### UC3 Functional Requirements

- FR9: When a volunteer scans another volunteer's QR Code, the user should be directed to the "Send an Appreciation" screen with the other volunteer's information already populated.
  - Business Requirement: BR1
  - Priority: High

## Non Functional Requirements

- NR1: The app needs to be accessible on iOS and Android
  - Business Requirement: BR1
  - Priority: High
- NR2: The buttons and text need to meet accessibility standards
  - Business Requirement: BR1
  - Priority: Medium
- NR3: All non-ui, non-native features need to have automated unit tests.
  - Business Requirement: N/A (Client expectation)
  - Priority: Low
- NR4: The application should cache HTTP requests to maintain some usability while not connected to the internet
  - Business Requirement: BR1
  - Priority: Low
