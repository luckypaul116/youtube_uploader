# YouTube Uploader

This project is a YouTube video uploader application that allows users to upload videos directly to their YouTube channels from their local system. The application is built using Node.js and integrates with the YouTube Data API v3.

## Features

- Upload videos to YouTube
- Manage video metadata (title, description)
- View uploaded videos and their details
- Edit and update video information
- Delete videos from YouTube

## Setup

1. Clone the repository:
   ```sh
   git clone https://github.com/luckypaul116/youtube_up.git
   cd youtube_up
   
2. Install dependencies:
npm install

3. Create a .env file with the following content:

MONGO_URI=mongodb://localhost:27017/youtubeUploader
CLIENT_ID=your_google_client_id
CLIENT_SECRET=your_google_client_secret
REDIRECT_URL=your_google_redirect_url
ACCESS_TOKEN=your_google_access_token
REFRESH_TOKEN=your_google_refresh_token

4. Start the server:
npm start

Usage

Open your browser and go to http://localhost:3000.
Enter your YouTube API credentials.
Use the interface to upload, edit, and manage your YouTube videos.

License
This project is licensed under the MIT License. See the LICENSE file for details.
