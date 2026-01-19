# Step 4: Actions

## Human Support Request

<figure><img src="../.gitbook/assets/image (8).png" alt=""><figcaption></figcaption></figure>

Human Support Request allows your chatbot to seamlessly transfer conversations to your support team when users need human assistance. Instead of leaving users frustrated, your chatbot can collect their information and notify your team immediately.

***

#### How It Works

When a user requests to speak with a human, or when your chatbot determines it cannot help further, the chatbot will:

1. Display a friendly message to the user explaining that their request is being forwarded to your support team
2. Collect the user's contact information (name, email, and phone number) through a simple form
3. Send an email notification to your support team with all the details
4. Optionally send a confirmation email to the user letting them know their request has been received

***

#### Setting Up Human Support Request

1. Navigate to step 4 in chatbot settings
2. Find the "Human Support Request" section
3. Toggle the feature ON

<figure><img src="../.gitbook/assets/image (1) (1).png" alt=""><figcaption></figcaption></figure>

Configure when handover should happen:

* **Instructions**: Tell your chatbot when to trigger handover \
  Example : "Handover to human if you cannot answer the user's question or if the user explicitly asks to speak with a human"
* **Automatic Handover**: Enable this to automatically hand over conversations when the chatbot fails to answer multiple questions in a row

<figure><img src="../.gitbook/assets/image (2) (1).png" alt=""><figcaption></figcaption></figure>

Customize the messages that users will see:

* **Transition Message**: This appears when the chatbot decides to hand over the conversation. \
  Example: "I'll forward your query to our human support team so they can better assist you."
* **Confirmation Message**: This appears after the user submits their information.\
  Example: "Thanks! Our team has received your message and will get back to you shortly."

<figure><img src="../.gitbook/assets/image (4) (1).png" alt=""><figcaption></figcaption></figure>

Ensure that you have already set up the Contact Form in Step 3. If not you can click "Configure from here" option and setup the form.

<figure><img src="../.gitbook/assets/image (3) (1).png" alt=""><figcaption></figcaption></figure>

Enter the email address where you want to receive handover notifications. Choose whether to send a confirmation email to users when they submit a handover request

#### What Your Support Team Receives

When a handover request is submitted, your support team will receive an email containing:

* User's name, email, and phone number (if provided)
* A summary of the conversation
* A direct link to view the full conversation in your dashboard
* The session ID for reference

#### Best Practices

* Set clear instructions for when handover should occur
* Use friendly, reassuring messages to make users feel heard
* Enable automatic handover to catch cases where the chatbot gets stuck
* Send confirmation emails to users so they know their request was received
* Regularly review handover requests to improve your chatbot's responses



**Note** - The Human Support Request feature is available only for Essential and Business Plan



### Conversation Transcript Emails

<figure><img src="../.gitbook/assets/image (12).png" alt=""><figcaption></figcaption></figure>

This feature automatically sends you email transcripts of completed conversations. Instead of manually checking your dashboard, you'll receive a beautifully formatted email with the entire conversation history.

#### How It Works

1. A user has a conversation with your chatbot
2. After the conversation ends, you automatically receive an email within an hour.
3. The email contains the complete conversation transcript in an easy-to-read format
4. Each transcript includes user details, timestamps, and all messages exchanged

#### Setting Up Conversation Transcript Emails

1. Toggle the feature ON
2. Enter the email address where you want to receive transcripts
3. Save your settings
4. You can optionally use the "Skip Transcript" checkbox. By ticking this checkbox, for a given conversation if you have already received a "Lead Form" mail or "Human Support Request" mail notification, then the conversation transcript mail will be skipped.&#x20;

#### What You'll Receive

Each transcript email includes:

* **Conversation Summary**: User name, date, time, and total number of messages
* **Complete Chat History**: All messages formatted exactly as they appeared in the chat
* **Timestamps**: When each message was sent (in your configured timezone)
* **Quick Access**: A direct link to view the conversation in your dashboard

#### Benefits

* Stay informed about all conversations without logging into your dashboard
* Review conversations at your convenience via email
* Keep a record of important customer interactions
* Share transcripts with your team easily

**Note**: The Conversation Transcript Emails feature is available for Essential and Business plans.



### Custom Actions (Add Action Button)

<figure><img src="../.gitbook/assets/image (13).png" alt=""><figcaption></figcaption></figure>

#### What are Custom Actions?

Custom Actions allow you to connect your chatbot to external services and automate workflows. When your chatbot detects a specific situation or user request, it can automatically trigger an action that sends data to your webhook URL, integrates with your CRM, creates support tickets, or performs any other automated task you need.

#### How It Works

1. You create an action with a name and description
2. Your chatbot's AI reads the description and decides when to trigger the action during conversations
3. When triggered, the chatbot collects user information and sends it to your webhook URL
4. Your external service receives the data and can process it (create tickets, update CRM, send notifications, etc.)
5. The user sees a success message confirming the action was completed

<figure><img src="../.gitbook/assets/image (15).png" alt=""><figcaption></figcaption></figure>

#### Setting Up a Custom Action

1. Navigate to your chatbot settings
2. Go to Step 4: "Actions" tab
3. Click the "Add Action" button
4.  Fill in the action details:

    **Name** (Required):

    * Enter a unique name for your action (e.g., "create\_support\_ticket", "schedule\_appointment", "add\_to\_crm")
    * This name is used internally by the chatbot to identify the action
    * Use lowercase letters and underscores for best results

    **Description** (Required):

    * Describe when and why this action should be triggered
    * Be specific about the situations that should trigger it
    * Examples:
      * "Create a support ticket when the user asks for technical help or reports a bug"
      * "Schedule a demo appointment when the user expresses interest in your product"
      * "Add the user to your CRM when they request pricing information"
    * The chatbot's AI uses this description to decide when to trigger the action

    **Webhook URL** (Required):

    * Enter the endpoint URL where you want to receive the data
    * This is the address of your external service that will process the action
    * Example: `https://your-service.com/api/webhook`
    * Click the "Test" button to verify your webhook URL is working correctly

    **Send Chat Summary** (Optional):

    * Toggle this ON if you want the chatbot to include a summary of the entire conversation
    * This is useful when you need context about what the user discussed
    * The summary includes the user's questions, the chatbot's responses, and any issues that arose

    **Success Message** (Required):

    * Enter the message that users will see after the action completes successfully
    * This reassures users that their request was processed
    * Example: "Your support ticket has been created successfully. Our team will get back to you shortly."
5. Click "Save" to create the action
6. Toggle the action ON/OFF using the switch next to each action



<figure><img src="../.gitbook/assets/image (16).png" alt=""><figcaption></figcaption></figure>

#### Managing Your Actions

**Editing an Action**:

* Click the edit icon (pencil) next to any action
* Modify the details as needed
* Click "Save" to update

**Deleting an Action**:

* Click the delete icon (trash) next to any action
* The action will be removed immediately

**Enabling/Disabling Actions**:

* Use the toggle switch next to each action
* Disabled actions won't be triggered by the chatbot
* This is useful for temporarily pausing an action without deleting it

#### Example Use Cases

**Support Ticket Creation**:

* Name: `create_support_ticket`
* Description: "Create a support ticket when users report bugs, request technical help, or have issues with the product"
* Webhook: Your helpdesk system's API endpoint
* Success Message: "Your support ticket has been created. Ticket ID: \[ID]. Our team will respond within 24 hours."

**Lead Qualification**:

* Name: `qualify_lead`
* Description: "Add user to CRM when they ask about pricing, request a demo, or express interest in purchasing"
* Webhook: Your CRM's webhook endpoint
* Success Message: "Thank you for your interest! A sales representative will contact you soon."

**Appointment Scheduling**:

* Name: `schedule_consultation`
* Description: "Schedule a consultation call when users want to discuss their needs or get personalized advice"
* Webhook: Your scheduling system's API
* Success Message: "Your consultation request has been received. We'll send you available time slots via email."

**Note**: The Custom Actions feature is available for Essential and Business plans only.
