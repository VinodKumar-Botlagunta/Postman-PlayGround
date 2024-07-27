# Postman PlayGround

Welcome to **Postman PlayGround**! This repository contains a beginner-friendly Postman collection that demonstrates basic API operations using GET, POST, and DELETE requests. It’s designed to help you get started with API testing in Postman.

## Overview

This collection provides practical examples of:

- **POST** request to add a book.
- **GET** requests to retrieve book details by author or ID.
- **DELETE** request to remove a book.

## Variables Used

- **Global Variables:**
  - `isbn`: A unique identifier for each book.
  
- **Collection Variables:**
  - `bookID`: Combines a unique `isbn` with an aisle number.
  - `authorName`: Randomly generated name for the author.
  
- **Environment Variables:**
  - `BaseURL`: Base URL for API requests (adjustable for different environments like QA or Prod).
  - Prod URL: https://216.10.245.166
  - QA URL: https://rahulshettyacademy.com

## Getting Started

1. **Clone the Repository:**
   git clone https://github.com/VinodKumar-Botlagunta/Postman-PlayGround.git
