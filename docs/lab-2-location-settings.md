# Lab 2: Location Settings

In this lab, you will learn to edit locations, assign PSTN connections, manage PSTN and location settings.

### The main location should be renamed appropriately.

*Management > Location > dCloud > Location info > Small pencil icon*

Rename dCloud Location

* Location name: PalmoraResort

### Palmora Resort will use the Cisco Calling Plans as PSTN option.

*Management > Locations > Select location > PSTN > PSTN Configuration > PSTN connection > Manage*

Assign PSTN Connection to the location

* Location: PalmoraResort
* Connection Type: Cisco Calling Plans
* Contract Information: Charles Holland - Student login email address
* Service Address: location address (already entered)
* Authorized Contact: Charles Holland
* Job title: Admin

### The location needs 5 numbers.

*Services > PSTN & Routing > Numbers > Add numbers*

Order and add numbers

* Location: PalmoraResort
* Number Type: PSTN
* Select an Area Code from the list (*if you don’t see this option, be sure to scroll down in the center section of the screen)*
* Order 3 numbers
* IMPORTANT: Click view orders
  + Click on the pending order to automatically change the status to provisioned

### To make and receive calls the location needs a main number.

*Management > Locations > PalmoraResort > PSTN > PSTN Configuration > Main number*

Assign a main number to PalmoraResort

* Select one of the available numbers
* Make a note of the number for a subsequent lab

### PalmoraResort users will need to use voicemail.

*Management > Locations > PalmoraResort > Calling > Calling features settings > Voice portal*

Configure the voice portal

* Voice portal name: VM – HQ
* Incoming Call:
  + Phone number: Any number not selected as the main number
  + Extension: 200

### Calls coming into the main number need to route to specific options based on the time of day.

*Management > Locations > PalmoraResort> Calling > Calling features settings > Schedules*

Create a schedule for PalmoraResort

* Name: Open Hours
* Schedule Type: Business Hours
* Monday – Friday 9:00 am – 5 pm
* Make sure to turn off the lunch schedule!

| Help articles | |
| --- | --- |
| [Setup Cisco Calling Plan](https://help.webex.com/en-us/article/nousk9ab/Get-Started-with-the-Cisco-Calling-Plan#Cisco_Task_in_List_GUI.dita_36fcaf64-4bcd-4eda-a968-ad59c7887905) | [Assign Location Main Number](https://help.webex.com/en-us/article/f661ju/Change-the-Main-Phone-Number-for-a-Location) |
| [Configure Voice Portal](https://help.webex.com/en-us/article/nojp8ej/Configure-voice-portals-for-Webex-Calling-in-Control-Hub) |  |

STOP: End of Lab 2

Raise your hand and leave it raised in the Webex Meeting. Wait for further instruction.  
![](assets/docx-image-009.png)
