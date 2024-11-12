

# MiniSocial - Mini Twitter DApp

MiniSocial is a decentralized social media application similar to Twitter, built on Ethereum's blockchain. It allows users to connect their wallet, post updates, like/dislike posts, and view an activity feed. Users can also edit or delete their own posts.

## Features

- **Connect to Wallet**: Login with MetaMask to interact with the MiniSocial platform.
- **Change User**: Switch accounts to view posts and interact as different users.
- **Activity Feed**: View a feed of posts from all users.
- **Add Post**: Create a post with the logged-in user's address.
- **Like/Dislike**: Interact with posts by liking or disliking them.
- **Like/Dislike Count**: Display the count of likes and dislikes on each post.
- **Post Date**: Show the date each post was created.
- **Edit Post**: Edit posts and display the last modified date (only the post creator can edit their own posts).

## Screenshots

### 1. Interface Overview
![Interface Overview]([[image-path]/Screenshot%20from%202024-11-12%2022-52-12.png))

### 2. Activity Feed with Posts
![Activity Feed]([image-path]/Screenshot%20from%202024-11-12%2023-22-36.png)

### 3. MetaMask Wallet Interaction
![MetaMask Wallet Interaction]([image-path]/Screenshot%20from%202024-11-12%2023-22-45.png)

### 4. Transaction Confirmation
![Transaction Confirmation]([image-path]/Screenshot%20from%202024-11-12%2023-23-11.png)

### 5. Updated Post Feed
![Updated Post Feed]([image-path]/Screenshot%20from%202024-11-12%2023-23-18.png)

## Getting Started

### Prerequisites

- **MetaMask**: Install MetaMask extension on your browser.
- **Node.js**: Ensure Node.js and npm are installed.
- **Ethereum Test Network**: Use Sepolia or any Ethereum test network.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/minisocial.git
   ```
2. Install dependencies:
   ```bash
   cd minisocial
   npm install
   ```

3. Update the contract address and ABI in `MiniSocial.js` with your deployed contract details.

### Running the Application

1. Start the application:
   ```bash
   npm start
   ```
2. Open MetaMask and connect to Sepolia or another test network.
3. Access the app at `http://localhost:3000`.

## Contract ABI and Interaction

The `MiniSocial` smart contract includes functions for posting, editing, liking, and deleting posts. Here’s a summary of the primary methods:

- **publishPost**: Publish a new post.
- **editPost**: Edit an existing post.
- **likePost**: Like or dislike a post.
- **getPost**: Retrieve post details, including likes and dislikes.
- **getTotalPosts**: Get the total number of posts.

## Usage

- **Post Creation**: Enter a message and click "Post" to publish.
- **Edit Post**: Click the edit icon on your post to modify it.
- **Like/Dislike**: Use the heart and thumbs down icons to interact with posts.
- **Notifications**: Notifications appear when new posts are created or interactions occur.
