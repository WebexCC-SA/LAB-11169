# Lab 2: Location Settings

In this lab, you will learn to edit locations, assign PSTN connections, manage PSTN and location settings.

**1. The main location should be renamed appropriately.**

*Management > Location > dCloud > Location info > Small pencil icon*

Rename dCloud Location

- Location name: Palmora Resort

**2. Palmora Resort will use the Cisco Calling Plans as PSTN option.**

*Management > Locations > Select location > PSTN > PSTN Configuration > PSTN connection > Manage*

Assign PSTN Connection to the location

- Location: Palmora Resort
- Connection Type: Cisco Calling Plans
- Contract Information: Charles Holland – admin@admin.com
- Service Address: location address (already entered)
- Authorized Contact: Charles Holland
- Job title: Admin

**3. The location needs 5 numbers.**

*Services > PSTN & Routing > Numbers > Add numbers*

Order and add numbers

- Location: Palmora Resort
- Number Type: PSTN
- Select an Area Code from the list (*if you don’t see this option, be sure to scroll down in the center section of the screen)*
- Order 5 numbers
- IMPORTANT: Click view orders
    - Click on the pending order to automatically change the status from pending to provisioned
    - You can also go to *Services > PSTN & Routing > PSTN orders* to find the order if you closed the order confirmation screen too quickly.

**4. To make and receive calls the location needs a main number.**

*Management > Locations > Palmora Resort > PSTN > PSTN Configuration > Main number*

Assign a main number to Palmora Resort

- Select one of the available numbers
- Make a note of the number for a subsequent lab

**5. Voicemail will be a required feature.**

*Management > Locations > Palmora Resort > Calling > Calling features settings > Voice portal*

Configure the voice portal

- Voice portal name: VM – PalmoraResort
- Incoming Call:
    - Phone number: Any number not selected as the main number
    - Extension: 200

**6. Calls coming into the main number need to route to specific options based on the time of day.**

*Management > Locations > Palmora Resort> Calling > Calling features settings > Schedules*

Create a schedule for Palmora Resort

- Schedule Name: Open Hours
- Schedule Type: Business Hours
- Monday – Friday 9:00 am – 5 pm
- Make sure to turn off the lunch schedule!

**Help Article Links**

* [Setup Cisco Calling Plan](https://help.webex.com/en-us/article/nousk9ab/Get-Started-with-the-Cisco-Calling-Plan#Cisco_Task_in_List_GUI.dita_36fcaf64-4bcd-4eda-a968-ad59c7887905)
* [Assign Location Main Number](https://help.webex.com/en-us/article/f661ju/Change-the-Main-Phone-Number-for-a-Location)
* [Configure Voice Portal](https://help.webex.com/en-us/article/nojp8ej/Configure-voice-portals-for-Webex-Calling-in-Control-Hub)
* [Create Schedules](https://help.webex.com/en-us/article/bx6j0h/Create-schedules-in-Control-Hub)

**STOP: End of Lab 2**
