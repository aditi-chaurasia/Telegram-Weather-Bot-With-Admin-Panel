# Telegram Weather Bot With Admin Panel🤖

## 📌 Overview

The Telegram Weather Bot is a chatbot built using NestJS, Telegraf.js, and MongoDB that provides real-time weather updates via a Telegram bot. Users can get weather forecasts by sending commands, and admins can manage user access.

## 🚀 Features

- 🌤️ Get real-time weather updates for any location.

- 🛠️ Admin panel to manage users (block/unblock/delete users).

- 📝 Store user details in MongoDB.

- 🌍 Cross-Origin Resource Sharing (CORS) enabled.

📂 Project Structure
Telegram-Weather-Bot
client/
├── src/
│   ├── components/         # Reusable UI components
│   ├── pages/              # Page-level components
│   ├── context/            # Context API for state management
│   ├── services/           # API interaction (Axios)
│   ├── App.tsx             # Main application file
│   ├── main.tsx            # React root entry
├── public/                 # Static assets
├── .env                    # Environment variables
├── package.json            # Dependencies

telegram-bot-project/
├── src/
│   ├── main.ts        # Main entry file
│   ├── app.module.ts  # Main module
│   ├── telegram.bot.ts  # Telegram Bot logic
│   ├── admin-panel/
│   │   ├── user-management/
│   │   │   ├── user-management.service.ts  # User management logic
│   │   ├── app.module.ts  # Admin module
│   ├── config/
│   │   ├── config.module.ts  # Configuration settings
├── package.json
├── .env  # Environment variables
├── README.md  # Project documentation

🛠️ Installation & Setup

## ✨ Prerequisites

- Make sure you have the following installed:

- Node.js (LTS version recommended)

- MongoDB

- NestJS CLI

- Telegram Bot Token

1️.Clone the Repository

git clone https://github.com/your-repo/telegram-weather-bot.git
cd telegram-weather-bot

2️.Install Dependencies

npm install

3.Setup Environment Variables

Create a .env file in the root directory and add the following:

BOT_TOKEN=your_telegram_bot_token
MONGO_URI=mongodb+srv://your_mongodb_uri
API_KEY=your_weather_api_key
PORT=5000

4️.To start the Server and see the result on telegram follow these instructions:
https://www.kapwing.com/videos/67b0e882b51e93fa99c169df


5.To start the Frontend and Backend:
https://www.kapwing.com/videos/67b0ece26d82fb8be196e9a7


The bot will now be running and listening for messages.

## 🤖 Usage

## 🟢 User Commands

- /start - Get a welcome message.

- /subscribe - Get the weather for a specific city.

- cityname - To get information like Temprature,Humidity,Wind Speed.

## 📍For Admin Panel

- Login with email id and it will redirect towards the dashboard

