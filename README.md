# Champions Maung – Flutter Frontend

This repository contains the **Flutter frontend application** for **Champions Maung**, a football betting platform using **Myanmar-style odds**.  
The application communicates with a Laravel-based backend API and provides the user-facing betting experience.

---

## Overview

- Flutter mobile application for football betting
- Designed to work with a Laravel backend
- Supports Myanmar-style odds
- Secure token-based authentication
- User-focused betting and wallet management
- Production-ready application currently in use

---

## Authentication

- User authentication is handled via access tokens issued by the backend
- Tokens are attached to API requests for secured endpoints
- Session handling is managed within the application

---

## User Scope

The Flutter application is designed primarily for **Users**, who can:

- View football matches and odds
- Place **single** and **accumulator** bets
- View betting history
- View wallet balance
- Deposit and withdraw units
- View transaction history
- View match results
- Read company announcements

Higher-level roles (Agent and above) are managed at the backend level and are not intended to place bets through this application.

---

## Core Features

### Betting
- Single match betting
- Accumulator (multiple matches) betting
- Myanmar-style odds display
- Bet submission and status tracking

### Wallet
- Wallet balance display
- Deposit unit requests
- Withdrawal unit requests
- Transaction history tracking

### Matches & Results
- Match listing and odds display
- Match result updates
- Settled bet outcomes

### Announcements
- Company announcement listing for users

---

## API Communication

- RESTful API integration with backend system
- Token-based request authorization
- Error handling and response validation implemented at application level

---

## Project Status

This frontend application is **already implemented and actively used** with its backend system.

---

## License

Developed by **Thwin Htoo Aung and Ye Yint Kyaw**.

This project is **open source** and available for anyone who wants to learn, use, or extend it.  
Feel free to explore the codebase, collaborate, and ask questions if there is anything you do not understand about the project.
