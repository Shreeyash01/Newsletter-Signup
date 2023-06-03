# Newsletter Signup

Welcome to my newsletter signup page project! This project is a web application built using Node.js and Express.js frameworks. It allows users to sign up for a newsletter by providing their email address, which is then stored on the MailChimp server.

## Installation

To run the newsletter signup page locally on your machine, follow these steps:

1. Clone the repository:

```
git clone https://github.com/Shreeyash01/Newsletter-Signup.git
```

2. Navigate to the project directory:

```
cd Newsletter-Signup
```

3. Install the required dependencies:

```
npm install
```

4. Set up the MailChimp API credentials:

   - Create a MailChimp account if you don't have one already.
   - Generate an API key in your MailChimp account.
   - Create a new audience/list in MailChimp where the user data will be stored.
   - Copy your API key and audience ID.
   - Create a `.env` file in the project root directory and add the following:

     ```
     MAILCHIMP_API_KEY=your-mailchimp-api-key
     MAILCHIMP_AUDIENCE_ID=your-mailchimp-audience-id
     ```

5. Start the server:

```
node app.js
```

6. Open your web browser and navigate to `http://localhost:3000` to access the newsletter signup page.

## Usage

1. On the homepage, enter your email address in the provided input field.
2. Click on the "Sign Up" button to submit your email address.
3. The server will send the email address to the MailChimp server and store it in the configured audience/list.
4. You will receive a confirmation message indicating that you have successfully signed up for the newsletter.

## Technologies Used

- Node.js
- Express.js
