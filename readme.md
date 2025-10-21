# ChatGPT Movie App

A step-by-step guide to building a ChatGPT movie app using Gadget and The Movie Database (TMDB) API.

## 📚 Documentation & Resources

- **Official Documentation**: [docs.gadget.dev - Building ChatGPT Apps](https://docs.gadget.dev)
- **Step-by-Step Tutorial**: [Building a ChatGPT Movie App with the OpenAI Apps SDK](https://dev.to/gadgetdev/building-a-chatgpt-movie-app-with-the-openai-apps-sdk-eab)
- **TMDB API Documentation**: [developer.themoviedb.org](https://developer.themoviedb.org/reference/getting-started)

## 🚀 Getting Started

### 1. Initial Setup

1. Visit [docs.gadget.dev](https://docs.gadget.dev) → Building ChatGPT Apps
2. Fork the template on Gadget
3. Set your app name

### 2. Configure ChatGPT App

1. Take the live app URL from gadget.dev
2. Go to ChatGPT → Settings
3. Navigate to **App and connectors**
4. Click **Create**
5. Fill in the required information:
   - **Name**: Your app name
   - **URL/MCP**: Your Gadget app URL
   - **Authentication**: OAuth

### 3. Backend Setup

#### Add Watchlist Model

- Go to **API → Models**
- Add a watchlist model

#### Create TMDB Helper

- Create a helper file: `api/tmdb.ts`
- This file will handle calls to the TMDB server

#### Environment Variables

1. Go to [gadget.app](https://gadget.app) → Settings
2. Navigate to **Environment variables**
3. Add: `TMDB_API_KEY`

## 🎬 Usage

After completing all the setup steps:

1. Go to ChatGPT
2. Click the **+** icon on the left sidebar
3. Select your tool
4. Give your prompt to interact with the movie app

## 📖 Additional Resources

For the complete implementation flow, refer to the detailed blog post: [Building a ChatGPT Movie App with the OpenAI Apps SDK](https://dev.to/gadgetdev/building-a-chatgpt-movie-app-with-the-openai-apps-sdk-eab)

## 🔧 Tech Stack

- **Backend**: Gadget
- **API**: The Movie Database (TMDB)
- **Frontend**: ChatGPT Apps SDK
- **Authentication**: OAuth
