# Superme Discord Bot

A comprehensive Discord bot for the Superme server with advanced features.

## Features

- 🎫 **Ticket System** - Create and manage support tickets
- 🏪 **XP Shop** - Buy roles with earned XP
- ⚖️ **Moderation** - Warnings, mutes, and spam protection  
- 🎉 **Giveaways** - Run server giveaways
- 📊 **Staff Applications** - Handle staff recruitment
- 🎤 **Voice XP** - Earn XP for being in voice channels
- 📝 **Logging** - Comprehensive server activity logs

## Discord Bot Requirements

Before deploying, make sure to enable these **Privileged Gateway Intents** in your Discord application settings:

1. Go to [Discord Developer Portal](https://discord.com/developers/applications)
2. Select your bot application
3. Go to "Bot" section
4. Enable these intents:
   - ✅ **MESSAGE CONTENT INTENT**
   - ✅ **SERVER MEMBERS INTENT** (if using member-related features)

## Environment Variables

Set these environment variables in your hosting platform:

- `TOKEN` - Your Discord bot token
- `staffRoleId` - Role ID for staff members
- `highStaffRoleId` - Role ID for high staff members
- `PORT` - Port for health checks (default: 3000)

## Deploy to Render

1. Connect this repository to Render
2. Set environment variables
3. Use Node.js runtime
4. Start command: `npm start`

## Local Development

1. Install dependencies: `npm install`
2. Create `.env` file with your tokens
3. Start bot: `npm start`