# Gmail Clone
Welcome to the Gmail Clone project! This project is a replica of the popular email service Gmail, designed to provide users with a similar experience in managing their emails, organizing their inbox, and communicating with others. With the Gmail Clone, users can send and receive emails, organize messages into folders, and utilize various productivity features just like on the original platform.

## Features
1. **Email Management:** Allows users to send, receive, reply to, and forward emails with ease, supporting rich text formatting and attachments.

2. **Inbox Organization:** Enables users to organize emails into folders, labels, or categories for efficient inbox management and prioritization.

3. **Search Functionality:** Provides a powerful search functionality that allows users to search for emails by sender, subject, content, or other criteria.

4. **Filters and Rules:** Supports the creation of filters and rules to automatically categorize, label, or prioritize incoming emails based on predefined criteria.

5. **Email Composition:** Offers a user-friendly email composer with features such as spell check, auto-save, and drafts for composing and editing emails.

6. **Productivity Tools:** Integrates with productivity tools such as calendar, tasks, and reminders to help users manage their schedules and tasks effectively.

## App Setup

Clone the repository
```
git clone https://github.com/RadinaAvramova/gmail-clone.git
```

Now go to https://console.cloud.google.com/

Generate an API KEY.

Add your new API KEY to the script inside **src/main.js**


![Screenshot 2022-12-19 at 14 33 10](https://user-images.githubusercontent.com/108229029/208371968-8a66bbed-d157-4ab3-927f-cc573e6f9aaf.png)

And **backend/index.js**

![Screenshot 2022-12-19 at 14 33 32](https://user-images.githubusercontent.com/108229029/208372044-a867263c-b3aa-4575-ba44-8caa8f2ba8ba.png)

Setup Firebase (firestore)

Add the details to **src/firebase-init.js**

Now run this command to start the project 
```
npm i

npm run serve
```

And to start the backend
```
cd backend

npm i

npm run watch
```

You should be good to go!

## Usage
1. **Sign In or Sign Up:** Sign in to your existing account or sign up for a new account to access your inbox and start managing your emails.

2. **Compose Email:** Click on the compose button to open the email composer, enter recipient(s), subject, message content, and any attachments, and then send the email.

3. **Receive and Read Emails:** View incoming emails in your inbox, click on an email to open and read its contents, and take necessary actions such as replying, forwarding, or archiving.

4. **Organize Inbox:** Organize emails into folders, labels, or categories to keep your inbox clutter-free and easily accessible.

5. **Search and Filter:** Use the search functionality to find specific emails by sender, subject, content, or other criteria, and apply filters or rules to automate inbox management.

6. **Calendar Integration:** View and manage your schedule directly within the Gmail Clone interface, with options to create events, set reminders, and schedule meetings.

## Customization
You can customize the Gmail Clone by modifying aspects such as the user interface design, email templates, inbox organization options, and productivity features. Additionally, you can add new features, integrate with external services, or optimize performance for specific use cases.

# Application Images
<img width="1219" alt="Screenshot 2022-12-19 at 14 42 47" src="https://user-images.githubusercontent.com/108229029/208373071-7517e1cd-05be-4a31-964e-0f391f5ca30f.png">
