# Lab 4: Configuring Calling Features

In this lab, you will learn how to create a voicemail group, operating mode and announcements.

**1. After hours calls need to route to a voice mailbox that all employees can access.**

*Services > Calling > Features > Voicemail group > Add New*

Create a voicemail group

- Location: Palmora Resort
- Name: PR\_VmailGroup
- Extension: 600
- Passcode: 258011

**2. During unexpected office closures calls to the auto attendant will need to be routed to voicemail on demand by an end user.**

Services > Calling > Features > Operating Mode > Add New

Create an operating mode to route to voicemail

- Location: Palmora Resort
- Name: EmergencyClosure
- No schedule
- Forward destination: PR\_VmailGroup Ext 600

**3. Some call routing features require announcements.**

*Services > Calling > Features > Announcements > Add New > Text to speech*

Create a greeting to welcome guests to the Palmora Resort Reservation queue

- Level: Location
- Location: Palmora Resort
- Label: Welcome Reservation
- Text:

    ```text
    Welcome to the Palmora Resort reservations. A reservation agent will be with you shortly.
    ```

- Language: English
- Voice: You choose!
    - Generate the file before saving.

Create a greeting to welcome guests to the Palmora Resort Reservation queue

  - Level: Location
  - Location: Palmora Resort
  - Label: Greetings Guest Services
  - Text:

      ```text
      Welcome to Guest Services. A representative will be with you shortly.
      ```

  - Language: English
  - Voice: You choose!
    - Generate the file before saving

**Help Article Links**

* [Voicemail Group](https://help.webex.com/en-us/article/mcjd4u/Manage-a-shared-voicemail-and-inbound-fax-box-for-Webex-Calling)
* [Operating Modes](https://help.webex.com/en-us/article/fozeml/Call-routing-based-on-operating-modes-in-Webex-Calling)
* [Announcement Files](https://help.webex.com/en-us/article/n5y120ab/Manage-Announcement-Repository)

!!! danger "STOP: End of Lab 4"
    Wait for instructions before proceeding.
