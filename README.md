# User Management Screen Specification

## Overview
This document provides the user interface specification for the User Management Screen. This screen is used for managing user information in the system.

## Requirements
- Display a list of users with their details.
- Provide the ability to add new users.
- Provide the ability to edit existing users.
- Provide the ability to delete users.
- Provide the ability to hide disabled users.

## User Interface Components

### User List
- The user list is displayed on the left side of the screen.
- Each row in the list represents a user with the following columns:
  - ID
  - User Name
  - Email
  - Enabled (status)
- Each row has icons for editing and deleting the user.

### User Form
- The user form is displayed on the right side of the screen.
- The form is used for adding new users or editing existing users.
- The form contains the following fields:
  - Username
  - Display Name
  - Phone
  - Email
  - User Roles (with a dropdown selection)
  - Enabled (with a checkbox)

## Page Behavior
- When the page is loaded, all users are displayed in the user list.
- When the "New User" button is clicked, the user form is cleared.
- When the "Edit" icon is clicked in a user row, the user's information is loaded into the user form.
- When the "Delete" icon is clicked in a user row, the user is removed from the list.
- When the "Save User" button is clicked in the user form, the user's information is saved.
- When the "Hide Disabled Users" button is clicked, users with the "Enabled" status set to false are hidden from the user list.

