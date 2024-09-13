# Poll Voting Web Application

This web application provides an easy-to-use platform for creating and participating in polls. It features two main sections:

- **Admin Panel**: Allows an administrator to create a poll by specifying a question and two possible answers.
- **User Voting Page**: Enables users to vote on the poll and view the results.

The poll data and results are stored in the browser's local storage. After a vote is submitted, users can immediately view the updated poll results.

## Features

- **Poll Creation**: Admins can create a poll by entering a question and two answer options.
- **Voting Interface**: Users can choose one option and submit their vote.
- **Results Display**: Results are shown with a straightforward breakdown of votes for each option after voting.

## How to Use

### Admin Panel (Creating a Poll)

1. Open the `PollCreation.html` file in your web browser.
2. Enter the poll question and the two answer options.
3. Click the "Submit" button to create the poll.
4. The poll will be stored in the browser's local storage, making it available for users to vote on.

### User Voting (Voting and Viewing Results)

1. Open the `Poll.html` file in your web browser.
2. The poll question and the options created in the admin panel will be displayed.
3. Select your preferred answer and click "Submit Vote" to cast your vote.
4. The results, including the vote counts for each option, will be displayed immediately after voting.

## Folder Structure

```plaintext
|-- PollCreation.html  (Admin page for creating a poll)
|-- Poll.html   (User page for voting and viewing results)
