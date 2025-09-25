# KWASU Lost & Found System

A comprehensive lost and found system for KWASU with Telegram bot, WhatsApp bot, and web portal integration.

## Features

- **Telegram Bot**: Report lost/found items and search via Telegram
- **WhatsApp Bot**: Report lost/found items and search via WhatsApp
- **Web Portal**: Full-featured website for reporting and searching items
- **Unified Database**: All platforms share the same Firebase database
- **Real-time Updates**: Reports appear instantly across all platforms
- **Smart Matching**: Automatically suggests matching found items when reporting lost items

## Tech Stack

- **Backend**: Node.js, Express, Firebase
- **Frontend**: HTML, CSS, JavaScript, Bootstrap
- **Bots**: Telegram Bot API, Twilio WhatsApp API
- **Database**: Firebase Realtime Database
- **Hosting**: Render

## Setup Instructions

### Prerequisites

1. Node.js (v18 or higher)
2. Firebase account
3. Telegram Bot Token
4. Twilio account (for WhatsApp)
5. Render account (for hosting)

### Installation

1. Clone this repository
2. Install dependencies:
   ```bash
   cd backend
   npm install