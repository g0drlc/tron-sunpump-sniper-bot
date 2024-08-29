# TRON Sniper
![Screenshot_4](https://github.com/user-attachments/assets/253342fc-65cf-426f-bf7e-7c7c10b2ecc6)

This bot is designed to help you snipe and trade newly launched or migrated tokens in sunPump on the TRON blockchain. It's highly configurable and easy to set up.

## Features

- **Automated Token Sniping**: Monitor specific token contracts and automatically execute trades as soon as a liquidity pair is established on SunSwap.
- **Automated Newly Launched Token Sniping**: Monitor specific token contracts and automatically execute trades as soon as new token is launched on SunPump.
- **Effortless Trading**: Simplify buying and selling tokens on the TRON network with automated trade execution.
- **Automated Buying and Selling: Automatically buying and selling tokens.
- **Telegram Integration**: Control and monitor the bot directly from your Telegram account with an intuitive interface.
- **Secure Data Storage with MongoDB**: Store user data securely using MongoDB, ensuring privacy and reliability.

## Telegram Sniper bot

![Screenshot_6](https://github.com/user-attachments/assets/7b8478b9-2cfb-417d-9cce-7d7a2f771233)


## Getting Started

### Prerequisites

Make sure you have the following installed on your machine:

- Node.js (v16 or higher)
- npm or yarn
- [MongoDB](https://www.mongodb.com/docs/manual/administration/install-community/)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/g0drlc/tron-sniper.git
   cd tron-sniper
   ```

2. Install the dependencies:

   ```bash
   npm install
   # or
   yarn install
   ```

3. Ensure your MongoDB server is running. You can start it with the following command:

   ```bash
   mongod
   ```

4. Open the `.env` file in the root directory of your project and modify it with your specific configuration.

5. Start the bot:

   ```bash
   npm start
   # or
   yarn start
   ```

The bot will now start and connect to Telegram, MongoDB, and the TRON network.

### Available Commands

- `/start`: Initializes the bot and provides a welcome message.
- `/wallets`: Displays all wallets associated with your account.
- `/positions`: Shows your current token positions.
- `/pendingsnipes`: Lists all your pending sniping operations.

### Contacts

[@g0drlc](https://t.me/g0drlc)
[telegram sniper bot](https://t.me/g0drlc_tron_bot)
