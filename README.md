# GitPost Test

This repository is used to test GitPost AI.

## About

GitPost AI is an AI-powered developer assistant that automatically generates professional LinkedIn posts and tweets whenever code is pushed to a GitHub repository.

The application uses GitHub Webhooks to detect push events, fetches repository information and commit details, and leverages an LLM to generate engaging social media content.

## Features

- GitHub OAuth Authentication
- Automatic Repository Synchronization
- GitHub Webhook Integration
- Fetch Repository README
- Analyze Commit Diffs
- AI-powered Content Generation
- MongoDB Storage
- Real-time Dashboard Updates using Socket.IO

## Tech Stack

### Backend

- Node.js
- Express.js
- MongoDB
- Mongoose
- Socket.IO
- GitHub REST API
- OpenAI API

### Frontend

- React
- Vite
- Tailwind CSS

## Workflow

1. User logs in with GitHub.
2. Repositories are synchronized.
3. GitHub sends a webhook after every push.
4. Backend fetches the README and commit diff.
5. AI generates a professional social media post.
6. Generated posts are stored in MongoDB.
7. Dashboard updates in real time.

## Purpose

This repository exists only for testing GitHub webhooks and validating the GitPost AI automation pipeline.