# Fintech Bank Application

## Table of Contents
- [Introduction](#introduction)
- [Tech Stack](#tech-stack)
- [Features](#features)
- [Quick Start](#quick-start)
- [Environment Variables](#environment-variables)
- [Running the Project](#running-the-project)

## Introduction
Fintech Bank is a modern financial SaaS platform built with Next.js. It connects multiple bank accounts, displays transactions in real-time, facilitates fund transfers, and helps users manage their finances seamlessly.

## Tech Stack
- Next.js
- TypeScript
- Appwrite
- Plaid
- Dwolla
- React Hook Form
- Zod
- TailwindCSS
- Chart.js
- ShadCN

## Features
- **Authentication**: Secure SSR authentication with validation and authorization.
- **Bank Account Integration**: Link multiple bank accounts via Plaid.
- **Dashboard Overview**: Displays total balance, recent transactions, and spending insights.
- **Bank Management**: View connected bank accounts with balances and details.
- **Transaction History**: Paginated and filterable transaction logs.
- **Real-time Updates**: Changes are reflected instantly across the platform.
- **Funds Transfer**: Secure money transfers via Dwolla.
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices.

## Quick Start
### Prerequisites
Ensure you have the following installed:
- Git
- Node.js
- npm

### Installation
Clone the repository and install dependencies:
```sh
git clone https://github.com/adrianhajdin/banking.git
cd banking
npm install
```

## Environment Variables
Create a `.env` file in the project root and add the following:
```sh
# NEXT.js Configuration
NEXT_PUBLIC_SITE_URL=

# Appwrite Credentials
NEXT_PUBLIC_APPWRITE_ENDPOINT=https://cloud.appwrite.io/v1
NEXT_PUBLIC_APPWRITE_PROJECT=
APPWRITE_DATABASE_ID=
APPWRITE_USER_COLLECTION_ID=
APPWRITE_BANK_COLLECTION_ID=
APPWRITE_TRANSACTION_COLLECTION_ID=
APPWRITE_SECRET=

# Plaid API Keys
PLAID_CLIENT_ID=
PLAID_SECRET=
PLAID_ENV=
PLAID_PRODUCTS=
PLAID_COUNTRY_CODES=

# Dwolla API Keys
DWOLLA_KEY=
DWOLLA_SECRET=
DWOLLA_BASE_URL=https://api-sandbox.dwolla.com
DWOLLA_ENV=sandbox
```
Replace the placeholder values with your actual credentials.

## Running the Project
```sh
npm run dev
```
Open [http://localhost:3000](http://localhost:3000) in your browser.

---
This project is designed for financial technology applications, ensuring security, scalability, and seamless user experience.

