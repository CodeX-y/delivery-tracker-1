# Delivery Tracker 1

## Overview

The Delivery Tracker 1 project is a CRUD (Create, Read, Update, Delete) application built using Ruby on Rails. It allows users to track deliveries they are expecting, manage their status (waiting on or received), and interact with a simple user interface.

## Features

- **User Authentication**: Users can sign up, sign in, and manage their accounts.
- **Delivery Management**: Users can add new deliveries with descriptions and expected arrival dates.
- **Status Tracking**: Deliveries are categorized into "Waiting on" and "Received" sections based on their status.
- **CRUD Functionality**: Users can create, read, update, and delete delivery entries.
- **Sample Data**: A rake task (`rake sample_data`) is available to populate the development database with initial sample data.

## Implementation Details

- **Models**:
  - `User`: Managed by Devise for authentication.
  - `Delivery`: Stores details about each delivery, including its status and associated user.

- **Routes**:
  - Authentication routes: `/users/sign_up`, `/users/sign_in`, `/users/sign_out`.
  - Main functionality: CRUD operations for deliveries.

- **Views**:
  - Customized views for sign up, sign in, and delivery management.
  - Organized sections for "Waiting on" and "Received" deliveries.

- **Database Schema**:
  - `users` table: Stores user credentials.
  - `deliveries` table: Stores delivery details linked to users.

Target: https://delivery-tracker-1.matchthetarget.com
