**Sea Turtle Nestling Alert System** 
============
**Spreadsheet User Guide**
---


The Sea Turtle Nestling Alert System (STNAS) collects and processes data from a sea turtle nest to send notifications about the nest to a list of contacts.
You can update the contact list, track notifications and view the raw data within your STNAS spreadsheet on Google Drive.

### **Accessing the STNAS spreadsheet**

Before the system's installation, you will receive an email with an invitation to edit an STNAS spreadsheet. Click 'Open in Sheets' to open the spreadsheet and save it to your personal Google Drive. You will now be able to access the spreadsheet at anytime from your Google Drive homepage.

### **Viewing and updating the contact list**

To view and update the contact list that will receive notifications, navigate to the Contacts tab at the bottom of the spreadsheet.

#### Adding someone to the contact list

Adding someone to the contact list will allow them to receive any future notifications. It will not give them access to past notifications.

The STNAS sends notifications by text message or email. If someone wants to receive both text message and email notifications, they will need two separate entries on the list.

To add someone to the contact list, add a new row to the spreadsheet and fill in the appropriate information. Table 1 contains descriptions of each column in the contact list and instructions on how to fill them in.

*Table 1.*
| Column | Description | Format |
| ---    | ---         | ---    |
| **First Name** | The first name of the new contact. | Enter the name using any combination of upper or lower case letters and spaces. |
|**Last Name**| The last name of the new contact.| Enter the name using any combination of upper or lower case letters and spaces. |
| **Method** | How the new contact will receive notifications. Available methods are text message or email.</ul> | <ul><li> Text message notifications: enter *'text'*. <li>Email notifications: enter *'email'*.</ul> |
|**Address or Number**| The phone number *or* email address of the new contact.| <ul> <li>Text message notifications: enter the 10-digit phone number to receive texts, following the ###-###-#### format.  <li> Email notifications: enter the email address with no spaces. </ul>|
| **Carrier**| The phone carrier corresponding to the phone number entered in the **Address or Number** column. <ul> <li>(Note: STNAS only supports phone numbers registered with AT&T, Sprint, TMobile, and Verizon Wireless.) </ul> | <ul> <li> Text message notifications: enter the phone carrier for the phone number under **Address or Number**. <li> Email notifications: leave the cell blank.  </ul> |
|**Nest ID**| The unique, 6-digit ID number assigned to the nest being monitored. | Enter the 6-digit number with no spaces. |


#### Removing someone from the contact list
Removing a user from the contact list will stop the user from receiving new notifications. They can be added back to the list at anytime to continue receiving notifications. 

To remove someone from the contact list, simply delete the entire row containing their contact information. 

#### Testing notifications sent to new contacts
Test notifications are automatically generated and sent when a new entry is added to the contact list. A test notification is sent out via the delivery method indicated in the new entry and is only sent to the new contact, not the whole list. If a new contact does not receive a notification within 10 minutes of their complete information being added, delete that contact's entire row, refresh the browser and add the information again. 

### **Tracking notifications**
The spreadsheet logs each notification that is sent out. 
You can view these notifications by navigating to the Notifications tab. The most recent notification is displayed at the top. Table 2 contains descriptions of each column of the Notifications tab.

*Table 2.*
| Column | Description 
| --- |--- 
| **Time Sent** | The date and time that the notification was sent out. 
|**Nest ID**| The unique, 6-digit ID number assigned to the nest being monitored.
| **Type** | The type of notification being sent out. <ul> <li> *hatching* indicates that the nest is hatching. <li> *security* indicates that the system is being tampered with. <li> *MCU* indicates that the temperature or humidity conditions in the device may damage the micro-controller unit (MCU). </ul> 
|**Time Since Activation**| The amount of time that passed between the system's activation and the notification being sent.
| **Temperature**| The temperature sensor reading in the device that triggered the *MCU* notification. <ul><li> Only *MCU* notifications will have data in this column.
|**Humidity**| The humidity sensor reading in the device that triggered the *MCU* notification. <ul><li> Only *MCU* notifications will have data in this column. 

### **Viewing raw data**
You can access the system's raw data by navigating to the Raw Data tab at the bottom of the spreadsheet. The most recent data is listed at the top. Table 3 contains descriptions of each column of the Raw Data tab.

*Table 3.*
| Column | Description 
| --- |--- 
| **Time Recorded** | The date and time that the data entry was recorded.
|**Nest ID**| The unique, 6-digit ID number assigned to the nest being monitored.
|**Time Since Activation**| The amount of time that passed between the system's activation and the data entry being recorded.
| **Nest Temperature**| The temperature readings collected inside the nest.
|**Nest Humidity**| The humidity readings collected inside the nest.
| **Control Temperature**| The temperature readings collected by the control sensor outside of the nest.
|**Control Humidity**| The humidity readings collected by the control sensor outside of the nest. 
