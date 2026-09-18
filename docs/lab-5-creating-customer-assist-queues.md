# Lab 5: Creating Customer Assist Queues

In this lab, you will learn how to create and configure Customer Assist call queues.

### Callers to the Reservation number should be placed on hold until an agent is available.

*Services > Customer Assist > Queues > Add Queue*

Create a Customer Assist Call Queue

* Location: PalmoraResort
* Name: Reservation Queue
* Number: Assign an available number
* Extension 201
* Enable: Allow agents to use call queue number as caller ID
* Number of calls in queue: 15
* External caller ID phone number: Direct Line
* Routing: Priority Based – Longest Idle
* Screen pop: Enabled
  + URL:https://www.webex.com
  + Label:webexpage
* Overflow Settings:
  + Transfer to phone number: Extension 600 PR\_VmailGroup
  + Enable overflow after 60 seconds
* Welcome Message:
  + Welcome Message is mandatory: Enabled
    - Custom Greeting: Announcement files
    - Level: Organization
    - Select: Welcome reservation (from previous lab)
  + Comfort Message: Enabled
  + Time between comfort message: 15 seconds
* Hold Music: Enabled
* Agents:
  + Enable: Allow agents on active calls to take additional calls.
  + Enable: Allow agents to join or unjoin the queue.
  + Anita Perez, Taylor Bard, Eric Steele, Kellie Melby

### Reservation Queue has additional settings.

*Services > Customer Assist > Queues > Reservation Queue > Queue Policies*

Select Reservation Queue to configure additional features.

* Queue Policies - Night Service
  + Enable Night Service:
  + Transfer to Phone number: Extension 600 (VmailGroup)
  + Business Hours: Open Hours schedule
* Queue Policies - Stranded Calls
  + Night Service: selected
* Call Recording
  + Always with Pause/Resume (select all)
  + Generate Transcript with Summary and action items

### Create a Customer Assist queue for the Guest Services

*Services > Customer Assist > Queues > Add Queue*

Create a Customer Assist Call Queue for the Guest Services

* Location: PalmoraResort
* Name: GuestServices Queue
* Enable: Allow agents to use call queue number as caller ID
* Extension 202
* Number of calls in queue: 15
* External caller ID phone number: Location number
* Routing: Priority Based – Longest Idle
* Welcome Message:
  + Welcome Message is mandatory: Enabled
    - Custom Greeting: Announcement files
    - Level: Organization
    - Select: Greetings Guest Services (from previous lab)
  + Comfort Message: Enabled
  + Time between comfort message: 15 seconds
* Hold Music: Enabled
* Agents:
  + Enable: Allow agents on active calls to take additional calls.
  + Enable: Allow agents to join or unjoin the queue.
  + Anita Perez, Stefan Mauk, Rebekah Barretta, Kellie Melby

### Guest Services Queue has additional settings.

*Services > Customer Assist > Queues > GuestServices Queue*

Select GuestSerices Queue to configure additional features.

* Bounced Calls
  + Bounce calls after set number of rings: 6 rings
  + Enable Bounce if agent becomes unavailable
* Queue Policies - Stranded Calls
  + Night Service: selected
* Call Recording
  + Always with Pause/Resume (select all)
  + Generate Transcript with Summary and action items

| Help articles | | |
| --- | --- | --- |
| [Webex Calling Customer Assist](https://help.webex.com/en-us/article/72sb3r/Webex-Calling-Customer-Assist) |  |  |

STOP: End of Lab 5

Raise your hand and leave it raised in the Webex Meeting. Wait for further instruction.  
![](assets/docx-image-012.png)
