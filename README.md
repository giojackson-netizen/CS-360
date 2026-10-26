# CS 360 – Mobile Architecture and Programming
**Giovanni Jackson**  
**Project: GCJ Weight Tracker**

## App Requirements and Goals

My app, GCJ Weight Tracker, was designed to help users record their daily weight and follow their progress toward a goal. The idea was to provide a simple way to track weight without having to navigate through features that were not needed. The requirements included account creation and login, a database for storing information, a grid displaying weight entries, and the ability to add, update, and delete records. The app also needed to request permission for SMS goal notifications while allowing users to continue using the main features if they denied permission.

This project connected with my own interest in fitness and tracking progress. I wanted the design to make it easy for someone to enter their information, review previous entries, and understand how they were progressing.

## Screens, Features, and User-Centered Design

The design called for a login and account creation screen, a weight-history dashboard, controls for adding and editing entries, and a way to set a goal weight. The notification permission flow also needed to explain why SMS access was being requested.

I kept users in mind by focusing on clear labels, straightforward navigation, and keeping related information together. Having weight records organized in a grid helps users review their history, while clearly labeled actions make it easier to understand how to manage entries. The strength of this design is that it focuses on the main task without making the user go through unnecessary steps.

## Approach to Coding

My approach was to break the app into smaller responsibilities instead of trying to handle everything at once. The interface, input validation, database operations, and notification permissions each needed attention. Clear names and focused sections of code make it easier to understand how those parts connect and where a problem may be coming from.

This is an approach I can continue using in future projects, including the biomedical equipment tracker I have been exploring. Working in a hospital has shown me the importance of organized information and dependable systems. Breaking a program into manageable parts makes it easier to troubleshoot and improve as requirements change.

## Testing and Functionality

[Describe the tests you actually completed, the device or emulator you used, and what happened. Include any issues you found and corrected.]

Testing is important because an app can look correct while still having problems with how it handles information. Important checks for this project include invalid login information, missing or invalid weight entries, adding and changing records, and whether saved information remains available after reopening the app. Permission testing is also important because declining SMS access should not prevent someone from using the weight-tracking features.

## Challenges and Problem Solving

[Describe one challenge you actually encountered, what you changed to address it, and the result.]

A major design consideration was balancing a simple interface with the different responsibilities behind it. Account information, weight records, goals, and permissions all have to work together without making the app confusing. This project helped me think more carefully about the connection between what users see and what the program needs to do behind the scenes.

## Skills and Experience Demonstrated

The component I would highlight is the organization of the weight-tracking interface. Turning the requirements into a focused layout gave me an opportunity to think about what information users need and how they should move through the app.

My hospital experience has helped me understand how much clear information and practical workflows matter. I brought that same thinking into this project by focusing on making records easy to understand and actions easy to identify. This work also helped me connect my computer science studies with my interest in building useful tools for fitness and biomedical equipment management.
