# Lab 7: Creating an Auto Attendant

In this lab, you will learn how to create and configure an auto attendant**.**

1. Agents should have access only to features necessary for their roles on their desktops.

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
  + Disable extension level dialing
  + Option 1: Transfer without prompt: Extension 201
  + Option 2: Transfer with prompt: Extension 202
  + Option 3: Transfer to operator: Anita Perez
  + Option 4: Repeat
  + Option 5: Exit
  + Menu timeout and repeat configuration
    - Repeat on no input: 1 time
    - Action after all repeat attempts: End the call
* After Hours Menu
  + Option 1: Transfer without prompt: – Extension 600 (VmailGroup)
  + Menu timeout and repeat configuration
    - Repeat on no input: 1 time
    - Action after all repeat attempts: End the call
* Business Hours Greeting
  + Custom Greeting: Use TTs (copy and edit the sample script)
* After Hours Greeting
  + Custom Greeting: Use TTs (copy and edit the sample script)
