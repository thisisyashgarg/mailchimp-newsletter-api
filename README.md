# Mailchimp Newsletter API

This repository contains code that creates an Express app that uses the Mailchimp API to batch list members to a specified list. 

### Prerequisites

Before using this code, you will need to have `Node.js` installed on your system.

### Installing

First, install the `Express` package and the `dotenv` package.

```
npm init -y
npm install express dotenv
```

You will also need to install the `body-parser` and `@mailchimp/mailchimp_marketing` packages.

```
npm install body-parser @mailchimp/mailchimp_marketing
```

### Setting up environment variables

You will need to set up environment variables with your desired values. These values will then be stored in a `.env` file.

In the `.env` file, set the following variables:

- `apiKey` - this is your Mailchimp API Key
- `urlPrefix` - this is the URL Prefix for the Mailchimp API
- `listId` - this is your list ID for the list to which you're adding members

### Running the code

Once all the packages have been installed and the environment variables have been set up, you can now run the code.

To start the app, run the command in terminal:

```
node app.js
```

## Screenshots

### 1. Enter your full name and click sign me up
![Alt text](/public/images/input.png?raw=true "Title")

### 2. Congrats, you have subscribed to the newsletter successfully
![Alt text](/public/images/output.png?raw=true "Title")
