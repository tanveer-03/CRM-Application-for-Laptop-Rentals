# CRM-Application-for-Laptop-Rentals

## Project Overview

The **CRM Application for Laptop Rentals** is designed to streamline the process of renting laptops to customers. This application utilizes Salesforce's robust CRM capabilities to enhance customer interactions, optimize store operations, and increase overall efficiency. A key feature is the integration of email communication, enabling effective engagement with potential and existing customers.

## Features and Functionalities

- **Total Laptops Management**: Tracks and manages the inventory of laptops available for rent.
- **Consumer Management**: Manages customer details and their interactions with the rental service.
- **Laptop Booking Process**: Facilitates the booking of laptops and manages the entire booking lifecycle.
- **Billing Process**: Automates billing and payment processes for rentals.
- **User Roles and Profiles**: Defines different levels of access and roles, such as Owner and Agent, within the application.
- **Validation Rules**: Ensures the accuracy and completeness of critical data fields, such as phone number and email.
- **Automation via Flows and Apex**: Automates key processes like laptop distribution using Salesforce Flows and Apex triggers.
- **Reports and Dashboards**: Provides actionable insights through reports and visual data dashboards.

## Demo Video

Watch the demo video of the CRM Application for Laptop Rentals: [https://drive.google.com/file/d/14ZRFEisu0rp9XWaMZt5Cq-aXT11SQdea/view?usp=sharing ] . 

## Installation Instructions

1. **Creating Custom Objects**:
   - Navigate to Setup > Object Manager.
   - Create the following custom objects:
     - Total Laptops
     - Consumer
     - Laptop Booking
     - Billing Process

2. **Creating Tabs**:
   - Navigate to Setup > Tabs.
   - Create new tabs for each custom object created.

3. **Creating a Lightning App Page**:
   - Navigate to App Manager.
   - Create a new Lightning App named "LAPTOP RENTALS" and add relevant navigation items.

4. **Adding Fields to Objects**:
   - Follow standard Salesforce procedures to add required fields to the created objects.

5. **Creating a Validation Rule**:
   - Navigate to Object Manager > Consumer object.
   - Create a validation rule to ensure phone number and email are not blank.

6. **Creating Users**:
   - Navigate to Setup > Users.
   - Create new users with defined roles (Owner and Agent).

7. **Creating a Flow for Laptop Distribution**:
   - Create a Record-Triggered Flow to automate laptop assignments based on booking details.

8. **Developing Apex Code**:
   - Implement the `LaptopBookingHandler` class and `LaptopBooking` trigger for handling business logic and email notifications.

9. **Generating Reports and Dashboards**:
   - Utilize Salesforce reporting tools to create insightful reports and dashboards for analyzing rental metrics.

## Usage

- Access the application through Salesforce using the credentials provided during user creation.
- Navigate through the tabs to manage laptops, consumers, bookings, and billing processes.
- Use the reports and dashboards to gain insights into business performance.
