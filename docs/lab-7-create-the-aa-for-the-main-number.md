# Lab 7: Creating an Auto Attendant

In this lab, you will learn how to create and configure an auto attendant.

**1. Agents should have access only to features necessary for their roles on their desktops.**

*Services > Calling > Features > Auto attendant > Add New*

Create an auto attendant for the main number

* Location: Palmora Resort
* Name: Main AA
* Phone Number: Main Number
* Extension: 203
* Language: English
* Business Hours Schedule: Open Hours
* Holiday Schedule: None
* Business Hours Menu
    - Disable extension level dialing
    - Option 1: Transfer without prompt: Extension 201
    - Option 2: Transfer with prompt: Extension 202
    - Option 3: Transfer to operator: Taylor Bard
    - Option 4: Repeat
    - Option 5: Exit
    - Menu timeout and repeat configuration
        - Repeat on no input: 1 time
        - Action after all repeat attempts: Transfer call to operator.
* After Hours Menu
    - Option 1: Transfer without prompt: – Extension 600 (VmailGroup)
    - Menu timeout and repeat configuration
        - Repeat on no input: 1 time
        - Action after all repeat attempts: Play message and end the call.
* Business Hours Greeting
    - Custom Greeting: Use text-to-speech
    - Label: AADay
    - Text:

        ```text
        Thank you for calling Palmora Resort. Please use the following menu to direct your call. Press 1 for reservations. Press 2 for Guest Services. Press 3 or wait in the line to talk with an operator. Press 4 to Repeat menu. Press 5 to Exit menu.
        ```

* After Hours Greeting
    - Custom Greeting: Use text-to-speech
    - Label: AANight
    - Text:

        ```text
        Thank you for calling Palmora Resort. Our offices are closed. Please call back during our business hours or press 1 to leave a voicemail.
        ```

**Help Article Links**

* [Auto Attendant](https://help.webex.com/en-us/article/nsioxoi/Manage-auto-attendants-in-Control-Hub)

!!! danger "STOP: End of Lab 7"
    Wait for instructions before proceeding.
