# iGaming Player Wallet & Betting System - Backend Developer Task

## Overview

Build a Player Wallet and Betting System for an online gaming platform that handles player balances, betting operations, and transaction management.

## What's Already Provided

- Basic Express server with MongoDB connection (`server.js`)
- Package.json with required dependencies
- Environment configuration template (`.env.example`)

## Requirements

### Database Models

Create Mongoose schemas for:

- Players (username, email, balance, registration date)
- Bets (player, game, amount, odds, outcome, status)
- Transactions (player, type, amount, description, timestamp)
- Bonus (not required): Games (name, type, current odds, status)

### API Endpoints

Implement RESTful endpoints for:

- Player wallet operations (deposit, withdraw, balance check)
- Betting operations (place bet, cancel bet, view active bets)
- Transaction history and filtering
- Bonus (not required): Game management (create games, update odds, settle results)

### Business Logic

- Wallet balance management with transaction logging
- Betting validation (sufficient balance, game status)
- Odds calculation and payout processing
- Transaction rollback on failed operations

### Validation & Security

- Input validation for all endpoints
- Proper error handling
- Rate limiting for betting operations
- Data sanitization

## Technical Requirements

- Use design patterns appropriately
- Implement proper database relationships
- Handle financial transactions atomically
- Optimize database queries for performance
- Write clean, maintainable code

## Deliverables

- Complete API implementation
- Database models with relationships
- Input validation
- API documentation

## MongoDB login credentials:

We created a mongo db account with a temporary email for you to complete your task.

Inside only a cluster has been created, everything else like user permissions,
connection to nodejs project is to be done by you.

email: tanibep504@camjoint.com
pass: Asd1234567a


## We wish you good luck and happy coding.

## Using AI generated code is not forbidden, although is highly not recommended and will lower your scoring.