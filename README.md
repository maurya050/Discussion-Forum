# Discussion Forum WebApp

A **Reddit-like** discussion forum WebApp built using **Next.js**. Users can create topics, add multiple questions under each topic, and engage in real-time discussions with comment-based chats for each question.

## Features

- **User Authentication**: Secure user authentication using OAuth providers.
- **Create Topic**: Users can create new topics for discussion.
- **Add Questions**: Each topic can have multiple questions where users can share their thoughts.
- **Comment Section**: Users can comment and discuss each question in real time, fostering community discussion.
- **Responsive UI**: Optimized for mobile, tablet, and desktop devices.
- **User Profiles**: View profiles, discussion history, and user-specific activity.
- **Upvote/Downvote**: Interactive voting on topics, questions, and comments.
- **Notifications**: Get notifications for new comments on the user’s topics or questions.
- **Admin Panel**: Manage topics and monitor discussions.

## Tech Stack

- **Frontend**: Next.js, React.js, Tailwind CSS
- **Backend**: Next.js API routes for backend logic
- **Database**: MongoDB (for storing topics, questions, comments, and user data)
- **Authentication**: NextAuth.js or OAuth with Google/Facebook
- **State Management**: React Context API or Redux
- **Real-time Chat**: Socket.IO or Firebase Realtime Database

## Getting Started

To run this project locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/discussion-forum-webapp.git
   cd discussion-forum-webapp
