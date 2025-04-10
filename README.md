Contact Management System

Overview

A Python desktop application that provides a comprehensive solution for managing contacts. Built with Tkinter and SQLite, this Contact Management System offers a user-friendly interface for storing, retrieving, updating, and deleting contact information with ease.

Features

Contact Management

Add New Contacts - Store complete contact details including name, gender, age, address, and phone number

View Contacts - Display all contacts in a sortable, scrollable table view

Update Contacts - Edit existing contact information through a dedicated form

Delete Contacts - Remove contacts with confirmation dialogue

Double-Click Selection - Access contact details by double-clicking on any entry

Database Integration

SQLite Database - Local database storage for persistent data management

Automatic Table Creation - Database structure created automatically on first run

Sorted Display - Contacts displayed alphabetically by last name

User Interface

Clean Design - Intuitive layout with clear visual separation between functions

Form Validation - Required field checking to ensure data integrity

Confirmation Dialogs - Prevention of accidental deletions

Responsive Layout - Properly sized and positioned on all screens

Requirements

Python 3.x
SQLite3
Tkinter (usually included with Python installation)

Installation

# Navigate to the project directory
cd contact-management-system

# Run the application
python contact_management.py

Usage

Upon launching the application, you'll see the main window with a table displaying existing contacts (if any) and control buttons.
Adding a Contact

Click the "+ ADD NEW" button on the left side

Fill in the required fields (First Name, Last Name, Gender, Age, Address, Contact Number)

Click "Save"

Updating a Contact

Double-click on the contact you wish to edit

Modify the information in the update form

Click "Update"

Deleting a Contact

Select the contact you wish to delete by clicking on it

Click the "DELETE" button on the right side

Confirm deletion when prompted

Data Structure

The application uses a SQLite database with a single table structure containing:

mem_id: Primary key, auto-increment

firstname: Contact's first name

lastname: Contact's last name

gender: Contact's gender (Male/Female)

age: Contact's age

address: Contact's address

contact: Contact's phone number

Future Enhancements

Search functionality

Contact categories/grouping

Import/export capabilities

Additional contact fields (email, social media, etc.)

Dark mode theme

Contact image support
