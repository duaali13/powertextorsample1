Provide a detailed description here, distinct from your connector's description, of the value that the connector offers users and a high-level overview of functionality that the connector supports. This description should be no more than one paragraph of eight sentences. 

With the Power Textor connector, send SMS messages to your customers and get push notifications when a text message is received. Build brand loyalty through one-on-one conversations with customers.  Power Textor actions support a range of text message sending options, including on-demand SMS, scheduled SMS, event reminders, and Google Review requests. Each functionality is available for an individual number or a group of numbers. The Power Textor connector also includes a trigger for when a text message is received, which can be used with any other Power Automate actions to enable automated workflows based on incoming text messages.  

## Prerequisites 
Provide information about any prerequisites that are required to use this connector. For example, an account on your website or a paid service plan. 

A Power Textor subscription plan is required to use the connector. Subscribe to a Power Textor plan here: https://powertextor.com/#pricing   

## How to get credentials 
Provide detailed information about how a user can get credentials to use the connector. Where possible, this should be step-by-step instructions with links pointing to relevant parts of your website. 
If your connector doesn't require authentication, this section can be removed. 

Power Textor custom connector uses API key authentication. When creating a connection for the Power Textor custom connector, an API key needs to be provided. This API key can be obtained through the Power Textor website, the steps for which have been outlined in the following section. 

1. Login to Power Textor. 

2. Go to **API Keys** section. 

3. Generate a new API Key by clicking **New** button. 

4. Enter a name to identify your API Key. 

5. Select the period of validity for the API Key. 

6. Click **Save**. 

7. Copy the key displayed in **API Key** field. 
 

## Get started with your connector 

Provide users with a step-by-step process for getting started with your connector. This is where you should highlight common use cases, such as your expected popular triggers and actions, and how they can help in automation scenarios. Include images where possible. 

Authenticate the Power Textor account with Power Apps, to trigger flows for multiple scenarios based on different conditions. First, establish a successful connection with the Power Textor account using the API Keys by following the steps mentioned below: 

Log in to https://make.powerapps.com/ and navigate to the environment in which you will create your flow. Click Flows on the left pane to create a new flow in the environment. 

On the new page, click ‘+ New Flow’ on the command bar and select the type of flow based on the requirement of your business. You can also build a flow using the available templates or create a flow from scratch 

Select Instant Cloud Flow if your requirement includes manually running the flow every time to trigger the action that you will choose in the flow. 

Select Scheduled Cloud Flow to trigger text messages based on the trigger and schedule defined in the flow design. 
 

<img src="https://powertextorstorage.blob.core.windows.net/infomarkdownimages/1.png">
 

Fill in the required details in the pop-up box after choosing the flow type or click ‘Skip’ below. 
 
Graphical user interface, application

Description automatically generated 
 

In the search box, write ‘Power Textor’ and click on the icon when it appears. 

Click the ‘Actions’ tab to choose an Action from the list based on the type of Flow. 
 
A screenshot of a computer

Description automatically generated 

 

Choose the relevant action to complete the flow. There are various types of actions for the different use cases, such as: 

 

Send an instant text message to a contact, group of contacts, or new contact. Select action under the category of 'Send' in the name. Start a new manually triggered flow and in the main form, provide text in the Text Message field and set the Reply Stop To Opt-Out value as preferred.   

Schedule text messages for contacts, groups, and new contacts to automate frequent notifications on specified dates and times, such as sending marketing text messages, invitations, and regular offers to customers. Create a flow, and choose categories based on 'Schedule' messages. In the main form, give the Schedule Date in the required format to schedule text messages for future days. Similarly, provide time in the Schedule Time field in the required format to define the time of the scheduled text message on the set date.  

Send and Schedule Review text messages to acquire reviews from the customers on business and services with the clickable URL as a part of the text message for multiple contacts, groups, and new contacts. Design flow and choose an action type with ‘Review’ in the name from the list of available actions. In the review form, add the Business URL in the Place field, which opens the review page and saves customer feedback. Analyze the customer reviews filtered by organizations on the main Power Textor Review dashboard.  

Send and schedule Event Reminders for event registrants for upcoming events, and offers, and set the frequency of the reminders. Choose the action with ‘Event Reminder’ in it to configure text messages for contacts, groups, and new contact. In the main form, input the Event date to send reminders for, give a numeric value as the number of days before the given Event date for sending reminders on. Similarly, provide reminder time in the required format when the reminder text should be sent at.   

## Known issues and limitations 
If your connector has any known issues and limitations, include a detailed description of them here. This information should be as robust as possible so users have plenty of information should they run into problems. If any workarounds are known, include them here. 

None 

## Common errors and remedies 
Highlight any errors that might commonly occur when using the connector (such as HTTP status code errors), and what the user should do to resolve the error. 

 

 

 

 

## FAQ 
Provide a breakdown of frequently asked questions and their respective answers here. This can cover FAQs about interacting with the underlying service or about the connector itself. 

How to trigger a text message in Power Automate based on a condition 

Log in to https://make.powerapps.com/ and navigate to the environment in which you will create your flow. Click Flows on the left pane to create a new flow in the environment. 

On the new page, click ‘+ New Flow’ on the command bar and select the type of flow based on the requirement of your business. You can also build a flow using the available templates or create a flow from scratch 

Select Instant Cloud Flow if your requirement includes manually running the flow every time to trigger the action that you will choose in the flow. 

Select Scheduled Cloud Flow to trigger text messages based on the trigger and schedule defined in the flow design. 
 

Graphical user interface, application, Teams

Description automatically generated 
 

Fill in the required details in the pop-up box after choosing the flow type or click ‘Skip’ below. 
 
Graphical user interface, application

Description automatically generated 
 

In the search box, write ‘Power Textor’ and click on the icon when it appears. 

Click the ‘Actions’ tab to choose an Action from the list based on the type of Flow. 
 
A screenshot of a computer

Description automatically generated 
 

In the next step of the flow, provide the Connection Name that could be relevant to the flow that you are creating. Copy the API Key from the Power Textor account and paste it in the API Key field to establish a connection with Power Textor.  
Graphical user interface, application

Description automatically generated 
 

Click the ‘Create’ button. The button connects your Power Apps instance with the Power Textor account to load in your contacts and groups, for using them in the flow. 

Fill in the required fields for the chosen action. Each action contains a different set of fields based on the type of action selected. The fields with their description are mentioned below. 

To: This is a field to select Power Textor Contacts/Groups to send a text message to. 

Add Contacts: Select the Power Textor Contact names from the drop-down to add them to the new Group. 

Text Message: Provide the text message that you want to send.  

Group Name: Give a name to the Group that you are creating using Power Textor contacts. 

Scheduled Date: Provide the date at which you want to schedule the text message. Use the format MM/DD/YY 

Scheduled Time (UTC): Provide the UTC converted time at which you want to schedule the text message. Use the time format HH: MM.  

Reply STOP To Opt-Out: This is an optional field, setting the value ‘Yes’ will send ‘Reply STOP to Opt-out in the end of the text message. So the recipient can reply ‘STOP’ to the text which will discontinue sending the text messages to the contact’s number. They can resume the service by sending ‘START’ again. 

Place: Select a place that you have saved in the Power Textor account. 

Contact Number: The field is available when a new contact is created in Power Textor using the Power Textor connector. Provide the contact number of the contact. 

Contact Name: The field is available when a new contact is created in Power Textor using the Power Textor connector. Provide the name of the contact. 

 

How to Trigger an Action in Power Automate from a Received Text Message 

The Power Textor connector gives you the capability to trigger notifications when a text message is received. With the following steps, you can trigger various actions by configuring automated flows using the Power Textor trigger.  

Log in to https://make.powerapps.com/ and navigate to the environment in which you will create your flow. Click Flows on the left pane to create a new flow in the environment. 

On the new page, click ‘+ New Flow’ on the command bar and select ‘Automated Cloud Flow’. You can also build a flow using the available templates or create a flow from scratch  

The automated flow automatically triggers an action based on the conditions applied. This flow type does not require manual effort. 
 

Graphical user interface, application, Teams

Description automatically generated 

 

Provide the name of flow and click ‘Create’ button or click ‘Skip’ to add details later. 
Graphical user interface, application

Description automatically generated 
 

Connect to the Power Textor account using the API Keys. Once the successful connection is made, you will see a display message in the dialogue box: No additional information is needed for this step. You will be able to use the outputs in subsequent steps. 
 

Graphical user interface, application, Teams

Description automatically generated 

 

Now configure additional steps to trigger notifications when a text message is received in Power Textor. Design logic-based conditions and associate actions to it that will be triggered when a text message will be received.  
 

There are a few triggers as shown below that can be used for triggering notifications when a text message is received in Power Textor. 

Send Mobile Notifications  

Trigger email notifications  

Send a message on Teams 

Update a row in Excel Online  

You can also use actions to perform certain operations when triggered, such as Add members in Teams, Create a chat in Teams, Create task, Create item etc. 

Graphical user interface, text, application

Description automatically generated 

How to connect your Power Textor account to Microsoft Power Automate 

 

Connect your Power Textor with Microsoft Power Automate to create text messaging flows for multiple contacts and groups. With simple steps, integrate the Power Textor connector to design automated workflows and eliminate the manual effort of sending text messages to contacts and groups. The multi-purpose tool allows you to schedule messages for a larger number of recipients existing in different time zones with the ability to set the scheduled time of the text messages.  

To connect your Power Apps with the Power Textor you only require the Power Textor API Key to establish the connection with your flow in Power Apps. 

Generate API Key in Power Textor:  

The API Key is the main component that recognizes your Power Textor account in Power Apps. To provide the API Key, navigate to https://powertextor.com/ using your Power Textor username and password and follow the steps mentioned below. 

Click API Key on the left pane. On the new page, click the ‘+New’ button on the top right area of the page. From here you can generate an API Key and define its validity to use it in your workflows in Power Automate. 
 
Graphical user interface, application

Description automatically generated 
Graphical user interface, text, application

Description automatically generated 
 

On the New API Key form, provide the name of the API Key. You can define the name based on the purpose you are creating it for, so it will be easier to distinguish between the API Keys when you have multiple flows running across. In the Validity field, select the validity duration from the given options to define the validity of the API Key.  

NOTE: Make sure that you apply the validity according to the flows as the expired API Keys fails to authenticate with the Power Textor data. 
 

Graphical user interface, application, email

Description automatically generated 
 

Click ‘Save’ on the form. The page refreshes and the system generate the API Key for you. On the refreshed page, you can see the new API Key with the Creation Date and the Validity period. You can also modify the validity period by enabling the edit option available. Click the ‘Edit’ button, and change the selection made, click ‘Save’.  

You can create as many KPI Keys as you want for different purposes and set different validity of each one.  

Use the API Key in the workflow: 

To use this API Key for using the Power Textor Contacts and Groups in Power Apps, log in to https://make.powerapps.com/  and navigate to the environment in which you will create your flow. Make sure you choose the right environment; this will allow you to use the table data that exists in the selected environment in your flow. 

Copy the API Key from the Power Textor  

log in to PowerApps and choose the environment to create a flow. Select the type of flow according to your business need. 

Use the Power Textor connector – for creating a new connection, provide a unique ‘Connection Name’. Paste the copied key in the ‘API Key’ field and click the ‘Create’ button. 

 

Graphical user interface, application

Description automatically generated 

 

Graphical user interface

Description automatically generated 

 

The create button successfully syncs the Power Textor Contacts and Groups with Power Apps. Now you can use the list of Power Textor actions in your workflows to trigger, send and schedule text messages. 
 

Graphical user interface, application

Description automatically generated 
 

NOTE: There is only a one-time need to create the connection with your Power Textor database. You can add more connections by clicking ‘Add New Connection’ for using different API Keys, but do not have to re-establish the connection for the same every time.  

Graphical user interface, text, application

Description automatically generated 
 

 
To delete a connection, navigate to the Power Apps > Data on the left pane > Click it to expand subcategories > Click Connections > Select the connection you want to remove > Click on the ellipsis > Select delete and provide confirmation in the dialogue box. This action is irreversible.  

Graphical user interface, text, application

Description automatically generated 

 

Graphical user interface, application

Description automatically generated 

 