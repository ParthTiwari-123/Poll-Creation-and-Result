# Poll Voting Web Application

This is a static poll voting web application with two main components: 
1. **Admin Panel** (where an admin can create a poll)
2. **User Voting Page** (where users can participate in the poll by voting).

The results are stored in the browser's local storage, and users can see the results of the poll after they cast their vote.

## Features

- **Poll Creation**: Admins can create a poll with a question and two answer options.
- **Voting System**: Users can select one of the options and submit their vote.
- **Results Display**: Once the vote is submitted, the results are shown with a simple vote count for each option.

## How to Use

### Admin Panel (Create a Poll)
1. Open the `admin.html` file in a web browser.
2. Enter the poll question and two possible answer options.
3. Click on **Submit** to create the poll. 
4. The poll data will be saved in the browser's local storage, and users can now vote on this poll.

### User Voting (Participate in the Poll)
1. Open the `user.html` file in a web browser.
2. The poll question and options created in the admin panel will be displayed.
3. Select an option and click **Submit Vote**.
4. The results will be displayed showing the vote count for each option.

## Folder Structure

```plaintext
|-- PollCreation.html  (Admin page for creating a poll)
|-- Poll.html   (User page for voting and viewing results)
