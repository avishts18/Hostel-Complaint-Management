# Hostel Complaint Management

A Gradio-powered hostel complaint management system built with Python and MySQL. This repository provides a web interface for students to register complaints, view their own cases, and for admins to manage complaint status updates with email automation.

## Features

- Student registration and login
- Complaint registration with:
  - Priority
  - Category
  - Subcategory
  - Complaint type
  - Description
  - File attachment
  - Room number
  - Student name
  - Hostel block
- Complaint tracking via user dashboard
- Admin dashboard with:
  - Full complaint list
  - Case selection
  - Auto-filled complaint details
  - Status updates
  - Email notification automation
- Secure password hashing
- MySQL database persistence
- Gradio UI for easy browser-based interaction

## System Requirements

- Python 3.10 or newer
- MySQL server
- `pip` package manager
- Windows / Linux / macOS

## Python Dependencies

Install the required packages:

```bash
pip install gradio mysql-connector-python pandas pyautogui
