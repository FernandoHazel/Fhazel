# Name of the project

Description of the project

## Table of Contents

- [Requirements](#requirements)
- [Installation](#installation)
- [Configuration](#configuration)
- [Others](#Others)
- [Licence](#Licence)

## Requirements

Ensure that the following tools are installed on your system:

- [Node.js](https://nodejs.org/en/) v10.8.1 or higher  
- [NPM](https://www.npmjs.com/)  
- [Postman](https://www.postman.com/) (optional, for testing API endpoints)

## Installation

Follow the steps below to set up the project locally:

1. Clone the repository:

   ```bash
   git clone https://github.com/FernandoHazel/ReyesBackend.git
   cd ReyesBackendApp

2. Install express and stripe:

   ```bash
   npm i express stripe dotenv body-parser

3. Can install the dependencies like nodemon with -D:

   ```bash
   npm i nodemon -D

4. Use this command to run the project:

   ```bash
   npm run dev

## Configuration
Create an .env file at the root of the project and include the required environment variables.

PORT=3000
STRIPE_SECRET_KEY=your_stripe_key
FIREBASE_API_KEY=your_firebase_key
EMAIL_PROVIDER_KEY=your_email_service_key

Ensure that all keys are valid and that Firebase and email providers are properly configured.

## Others

Check this link of awesome [readmes](https://github.com/matiassingers/awesome-readme)

## Licence

Copyright (c) 2025 Fernando Hazel Ascencio Baumgarten

All rights reserved.

It is prohibited to copy, modify, distribute, or use this code, in whole or in part, without the explicit permission of the author.

