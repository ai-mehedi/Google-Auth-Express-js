# Google OAuth 2.0 Authentication with Node.js and Passport.js

This project demonstrates a simple Node.js application that enables users to log in with their Google accounts using Passport.js.

## Features

- Leverages Google OAuth 2.0 for secure user authentication
- Provides a login route for Google authentication
- Redirects to a profile page upon successful authentication
- Allows users to log out

## Prerequisites

- Node.js and npm (or yarn) installed on your system
- A Google Cloud Platform project with a configured Google OAuth 2.0 Client ID and Secret ([Google Workspace Guide](https://developers.google.com/workspace/guides/create-credentials))

## Installation

1. Clone this repository or download the code.

2. Navigate to the project directory in your terminal.

3. Install the required dependencies:

   ```bash
   npm install express passport express-session passport-google-oauth20
