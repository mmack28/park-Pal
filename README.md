# park-Pal
A Parking Management System 

## Overview
The Clemson Parking Application is a Python-based GUI program for managing parking spots across two lots (C1 and C2). Users can log in, create accounts, view available parking spots, and manage their parking allocations using a Tkinter-based interface.

## Features
- **User Management**
  - Login with username and password.
  - Create a new account.
  - Logout functionality.
- **Parking Management**
  - View availability of parking spots.
  - Reserve or vacate parking spots in C1 (200 spots) or C2 (150 spots).
  - Prevents double parking.
- **Grid Visualization**
  - Color-coded parking grid:
    - **Orange**: Available
    - **Purple**: Occupied.
- **Fullscreen Interface**
  - Application starts in fullscreen mode.
  - Exit fullscreen using the `Escape` key.

## How to Use
1. Launch the application by running the Python script.
2. Login or create a new account.
3. Choose between **C1** or **C2** parking lots.
4. Reserve or vacate a parking spot using the grid or input box.

## Prerequisites
- **Python 3.x**
- **Tkinter** (included with most Python installations).

## Application Workflow
- **Login Screen**
  - Enter credentials to log in or create a new account.
- **Start Screen:**
  - Choose between C1 or C2 parking lots.
  - Option to log out or quit the application.
- **Parking Management**
  - View the parking grid.
  - Reserve a spot by entering the parking number.
  - Vacate a reserved spot when leaving.

## Code Structure

- **Constants**
  - P_SPACE_C1 and P_SPACE_C2: Total spots in C1 and C2.
  - dict_of_spaces_c1 and dict_of_spaces_c2: Dictionaries to track parking status.
- **Frames**
  - loginFrame: For login functionality.
  - createAccountFrame: For account creation.
  - startFrame: Main navigation menu.
  - parkFrame and parkFrame2: Grid views for C1 and C2.
- **Key Functions**
  - login: Handles user login.
  - create_account: Creates new user accounts.
  - update_parking_grid: Updates the parking grid visualization.
  - handle_parking_input: Manages spot reservation.
  - leave_spot: Vacates a reserved parking spot.

## Installation
1. Save the script as `parkPal.py`.
2. Open a terminal and run:
   ```bash
   python parkPal.py
