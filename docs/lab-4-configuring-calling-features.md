# Lab 4: Configuring Calling Features

In this lab, you will learn how to create a voicemail group, operating mode and announcements

1. After hours calls need to route to a voice mailbox that all employees can access.

*Services > Calling > Features > Voicemail group > Add New*

Create a voicemail group

* Location: Palmora Resort
* Name: PR\_VmailGroup
* Extension: 600
* Passcode: 258011

2. During unexpected office closures calls to the auto attendant will need to be routed to voicemail on demand by an end user.

Services > Calling > Features > Operating Mode > Add New

Create an operating mode to route to voicemail

* Location: Palmora Resort
* Name: EmergencyClosure
* No schedule
* Forward destination: PR\_VmailGroup Ext 600

3. Some call routings require announcements.

*Services > Calling > Features > Announcements > Add New > Text to speech*

Create a greeting to welcome to the Palmora Resort Reservation queue

* Level: Organization
* Label: Welcome Reservation
* Text: Welcome to the Palmora Resort, soon a Reservation agent will be with you.
* Generate and listen to the file before saving.

Create a greeting to welcome to the Palmora Resort Concierge queue

* Level: Organization
* Label: Greetings Guest Services
* Text: Welcome to Guest Services, soon a representative will be with you.
* Generate and listen to the file before saving.
