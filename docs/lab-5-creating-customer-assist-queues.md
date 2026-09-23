# Lab 5: Creating Customer Assist Queues

In this lab, you will learn how to create and configure Customer Assist call queues.

**1. Callers to the Reservation number should be placed on hold until an agent is available.**

*Services > Customer Assist > Queues > Add Queue*

Create a Customer Assist Call Queue

* Create a Customer Assist Call Queue
  + Location: Palmora Resort
  + Name: Reservation Queue
  + Number: Assign an available number
  + Extension 201
  + Enable: Allow agents to use call queue number as caller ID
  + Number of calls in queue: 15
  + External caller ID phone number: Direct Line
  + Routing: Priority Based – Longest Idle
  + Screen pop: Enabled
    - URL: https://www.webexone.com/
    - Label:webexone
  + Overflow Settings:
    - Transfer to phone number: Extension 600 PR\_VmailGroup
    - Enable overflow after 60 seconds
  + Welcome Message:
    - Welcome Message is mandatory: Enabled
      * Custom Greeting: Announcement files
      * Select: Welcome reservation (from previous lab)
    - Comfort Message: Enabled
    - Time between comfort message: 15 seconds
  + Hold Music: Enabled
  + Agents:
    - Enable: Allow agents on active calls to take additional calls.
    - Enable: Allow agents to join or unjoin the queue.
    - Anita Perez, Taylor Bard, Kellie Melby

**2. Reservation Queue has additional settings.**

*Services > Customer Assist > Queues > Reservation Queue > Queue Policies*

Select Reservation Queue to configure additional features.

* Select Reservation Queue to configure additional features
  + Queue Policies - Night Service
    - Enable Night Service:
    - Transfer to Phone number: Extension 600 (VmailGroup)
    - Business Hours: Open Hours schedule
  + Queue Policies - Stranded Calls
    - Night Service: selected
  + Call Recording
    - Always with Pause/Resume (select all)
    - Generate Transcript with Summary and action items

**3. Create a Customer Assist queue for the Guest Services**

*Services > Customer Assist > Queues > Add Queue*

Create a Customer Assist Call Queue for the Guest Services

* Create a Customer Assist Call Queue for Guest Services
  + Location: Palmora Resort
  + Name: GuestServices Queue
  + Enable: Allow agents to use call queue number as caller ID
  + Extension 202
  + Number of calls in queue: 15
  + External caller ID phone number: Location number
  + Routing: Priority Based – Longest Idle
  + Screen pop: Enabled
    - URL: https://www.webex.com/
    - Label:webexpage
  + Overflow Settings:
    - Transfer to phone number: Extension 600 PR\_VmailGroup
    - Enable overflow after 60 seconds
  + Welcome Message:
    - Welcome Message is mandatory: Enabled
      * Custom Greeting: Announcement files
      * Select: Greetings Guest Services (from previous lab)
    - Comfort Message: Enabled
    - Time between comfort message: 15 seconds
  + Hold Music: Enabled
  + Agents:
    - Enable: Allow agents on active calls to take additional calls.
    - Enable: Allow agents to join or unjoin the queue.
    - Stefan Mauk, Rebekah Barretta, Eric Steele

**4. Guest Services Queue has additional settings.**

*Services > Customer Assist > Queues > GuestServices Queue*

Select GuestServices Queue to configure additional features.

* Select Guest Services Queue to configure additional features
  + Bounced Calls
    - Bounce calls after set number of rings: 6 rings
    - Enable Bounce if agent becomes unavailable
  + Call Recording
    - Always with Pause/Resume (select all)
    - Generate Transcript with Summary and action items

**Help Article Links**

* [Webex Calling Customer Assist](https://help.webex.com/en-us/article/72sb3r/Webex-Calling-Customer-Assist)

**STOP: End of Lab 5**