# EC2 Backend App Deployment Script
This Script Does following:

✅ Installs Node.js using NVM (customizable version).

📦 Installs npm, yarn (if selected), and PM2 globally.

🔄 Clones a Git repository (supports private and public repos).

🌱 Installs project dependencies (npm or yarn).

📁 Automatically creates a basic .env file.

🚀 Starts the app using PM2 with a custom name.

💾 Saves the PM2 process list for automatic restarts.

🌐 (Optional) Configures Nginx as a reverse proxy for your domain.

🔐 (Optional) Issues a free SSL certificate using Certbot + Let's Encrypt.

⚠️ Handles errors gracefully and reports which step failed.

