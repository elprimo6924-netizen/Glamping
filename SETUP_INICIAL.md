# Setup Instructions for Development Environment

This document outlines the step-by-step setup instructions for configuring your development environment for the Glamping project.

## Prerequisites
Before you start, make sure you have the following installed:
- Node.js (version x.x.x)
- PostgreSQL (version x.x.x)


## Step 1: Install Node.js
1. Go to the [Node.js official website](https://nodejs.org/).
2. Download the installer for your operating system.
3. Run the installer and follow the instructions to complete the installation.
4. Verify the installation by running the following command in your terminal:
   ```bash
   node -v
   ```

## Step 2: Install PostgreSQL
1. Go to the [PostgreSQL official website](https://www.postgresql.org/download/).
2. Choose the installer for your operating system and follow the instructions.
3. Once installed, initialize your database and start the PostgreSQL service.
4. Verify the installation by running:
   ```bash
   psql --version
   ```

## Step 3: Clone the Repository
1. Open your terminal.
2. Clone the repository using the following command:
   ```bash
   git clone https://github.com/yourusername/Glamping.git
   ```
3. Navigate into the project directory:
   ```bash
   cd Glamping
   ```

## Step 4: Install Dependencies
1. In the project directory, run:
   ```bash
   npm install
   ```

## Step 5: Configure Environment Variables
1. Create a `.env` file in the root of the project.
2. Add the following variables to your `.env` file:
   
   ```env
   DATABASE_URL=your_database_url
   NODE_ENV=development
   ```

## Step 6: Run the Project
1. After everything is set up, you can start the project with:
   ```bash
   npm start
   ```
2. Your application should now be running on `http://localhost:3000`.

## Additional Notes
- Make sure to check the project documentation for any environment-specific instructions.
- If you encounter any issues, refer to the README or reach out for help in the project's discussion forum.

Happy Coding!