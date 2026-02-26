# Chat App

## Introduction
This Chat App is designed to be a simple yet powerful messaging platform. It allows users to communicate in real-time, share files, and access various features aimed at enhancing the chat experience.

## Features
- **Real-time Messaging**: Send and receive messages in real-time.
- **User Authentication**: Secure user login and registration using Supabase.
- **File Sharing**: Share images and documents within chat.
- **Group Chats**: Communicate with multiple users in group settings.

## Tech Stack
- **Frontend**: Built with React.js for a dynamic and responsive UI.
- **Backend**: Node.js with Express for handling requests and interacting with the database.
- **Database**: Supabase as our backend as a service, providing easy user management and data persistence.
- **Deployment**: Deployed on Vercel for quick and optimal hosting.

## Getting Started with Supabase
1. **Set Up Supabase**: Create a Supabase project at [supabase.io](https://supabase.io), and set up your database.
2. **API Keys**: Note down your project's API keys from the Supabase dashboard.
3. **Configure Your App**: In your `.env` file, set the following variables:
   - `SUPABASE_URL`: Your project's URL.
   - `SUPABASE_ANON_KEY`: Your project's anon key.
4. **Initialize Supabase**: Use the Supabase client in your app by importing it:
   ```javascript
   import { createClient } from '@supabase/supabase-js';
   const supabase = createClient(SUPABASE_URL, SUPABASE_ANON_KEY);
   ```
5. **User Authentication**: Implement user sign-in and sign-up using Supabase's authentication methods.

## Project Setup
1. **Clone the Repository**: Run the following command in your terminal to clone the project:
   ```bash
   git clone https://github.com/dapurterbaikgo-a11y/chat-app.git
   cd chat-app
   ```
2. **Install Dependencies**: Install the required packages using npm:
   ```bash
   npm install
   ```
3. **Run the Application**: Finally, start the application with:
   ```bash
   npm start
   ```

## Contribution
We welcome contributions to enhance this project. Please follow the standard contribution workflow for pull requests.

## License
This project is licensed under the MIT License. See the LICENSE file for details.