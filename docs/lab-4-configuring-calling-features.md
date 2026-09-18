# Lab 4: Configuring Calling Features

In this lab, you will learn how to create a voicemail group, operating mode and announcements

### After hours calls need to route to a voice mailbox that all employees can access.

*Services > Calling > Features > Voicemail group > Add New*

Create a voicemail group

* Location: PalmoraResort
* Name: PR\_VmailGroup
* Extension: 600
* Passcode: 258011

### During unexpected office closures calls to the auto attendant will need to be routed to voicemail on demand by an end user.

Services > Calling > Features > Operating Mode > Add New

Create an operating mode to route to voicemail

* Location: PalmoraResort
* Name: EmergencyClosure
* No schedule
* Forward destination: PR\_VmailGroup Ext 600

### Some call routings require announcements.

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

| Help articles | | |
| --- | --- | --- |
| [Voicemail Group](https://help.webex.com/en-us/article/mcjd4u/Manage-a-shared-voicemail-and-inbound-fax-box-for-Webex-Calling) | [Operating Modes](https://help.webex.com/en-us/article/fozeml/Call-routing-based-on-operating-modes-in-Webex-Calling) | [Announcement Files](https://help.webex.com/en-us/article/n5y120ab/Manage-Announcement-Repository) |

STOP: End of Lab 4
