## Requirements & Setup Instructions

- Node version 20
- [Turso account](https://turso.tech/)

## Turso Setup

### **Step 1: Set Up Turso Database**

1. **Create a [Turso Account](https://turso.tech/)**: Sign up and create a new account on Turso if you haven't done so already.
2. **Obtain Database URL and Auth Token**:
   - Navigate to the Turso dashboard.
   - Set up a new database instance and retrieve the database URL and the authorization token.

### **Step 2: Configure Environment**

Create a **`.env`** file in the root directory of your cloned repository. Add the following lines to the file:

```bash
TURSO_CONNECTION_URL=""
TURSO_AUTH_TOKEN=""
```

Add your Turso URL and Auth token here.

### **Step 3: Initialize the Database**

Run the following command in your terminal to push the initial schema to your Turso database:

```bash
npm run db:push
```

This step ensures that your local development environment is synchronized with your database schema, setting the stage for development.

## Running the Application

```bash
yarn install
yarn dev
```
