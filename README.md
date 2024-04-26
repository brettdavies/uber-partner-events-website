# Uber Partner Events Website
This repository contains screenshots of the Uber Partner Events Website, designed to help Uber operations teams organize and manage events for Uber partner drivers. The platform, written in PHP and integrated with Uber’s Single Sign-On (SSO) for authentication, serves two primary user groups:
1. **Driver-Partner (External Users)**: Uber partners who browse, book, and manage their event attendance.
2. **City Admins**: Administrators who create and manage events.

# Technologies Used
- Backend: PHP 5.6.31, XAMPP
- Authentication: Uber Single Sign-On (SSO)
- Frontend: HTML, CSS, and JavaScript
- Database: MySQL

# Features
## Admin Functionality
Admins use this website to set up and oversee partner events, ensuring a smooth process for engaging drivers. The admin features include:

1. Event Management
   - **Dashboard View**: Admins can view all events listed by title, start date/time, venue, creation and update timestamps, and current status.
     - Screenshots: [Admin Homepage](./admin-mockup/1a%20Homepage.png) & [Country Selector](./admin-mockup/1b%20Homepage%20-%20Country%20&%20City%20Selector.png)
   - **Status Management**: Admins can toggle event statuses (e.g., Active or Inactive) to control visibility for users.
   - **Event Editing**: Options to create or modify events are accessible with fields for:
     - Title, location (country/city), venue, and description.
     - Date and time settings for the event.
     - Restrictions, such as eligibility based on driver status (Active, Onboarding, etc.).
     - Guest allowances and ticket details, including waitlist capacity.
     - Optional upload of invitation lists and featured event settings.
     - Screenshot: [Event Details](./admin-mockup/2%20Event%20-%20Details.png)

2. Attendee Management
   - Admins can monitor attendee statuses, including:
     - **Pending Confirmation**: Attendees awaiting confirmation.
     - **Confirmed**: Approved attendees with reserved seats.
     - **Waitlisted**: Attendees waiting for availability.
     - **Rejected**: Requests denied for the event.
   - Bulk operations, such as approving or rejecting multiple attendees, are supported.
   - Screenshot: [Attendee Management](./Final%20Testing%20-%20Admin%20Attendee%20Mgmt.png)

3. Admin User Management
   - **Admin List View**: Admins can view, edit, and create other city admin accounts, including their:
     - First/last name, email address, country, access level, and creation date.
     - Screenshot: [Admin Management](./admin-mockup/4a%20Admin%20Mgmt.png)
   - **Country Selector**: Admins can switch between countries to manage regional events and teams.
     - Screenshot: [Country Selector](./admin-mockup/4b%20Admin%20Mgmt%20-%20Country%20Selector.png)
   - **Editing Admins**: Admins can add or modify other admin accounts by setting names, emails, country, and roles (e.g., Admin or Superadmin).
     - Screenshot: [Admin Details](./admin-mockup/5%20Admin%20Details.png)

## Driver-Partner (External Users) Functionality
Uber partner drivers use the website to explore events, make reservations, and manage their bookings. Below are the user-facing features based on the screenshots:

1. Event Browsing
   - **Homepage View**:
     - A carousel of featured events.
     - Grid and list view options for all events in the selected city.
     - Category filtering (e.g., Social, Family, Information) to narrow down events.
     - Event cards showing event name, date, and a brief description.
     - Screenshots: [Grid View](./public-mockup/1a%20Homepage%20-%20Icon%20View.png), [List View](./public-mockup/1b%20Homepage%20-%20List%20View.png), [Filtered View](./public-mockup/1c%20Homepage%20-%20Filtered%20Icon%20View.png)
   - **City Selection**: Users can filter events by city using a dropdown menu.

2. Event Details
   - Users can click on an event to view:
     - Event title, description, date, time, and location details.
     - Social sharing buttons to share the event on platforms like Facebook, Twitter, and LinkedIn.
   - **Eligibility Notices**:
     - If logged in, users see whether they are eligible to attend.
     - If not logged in, users are prompted to sign in to view event details.

3. Booking Events
   - Users can reserve tickets for an event by clicking the Book It button.
   - Options to:
     - Add guest tickets.
     - Confirm or cancel their reservations.
   - After booking:
     - Users see a booking confirmation with steps for attendance.
     - Option to add the event to their calendar.

4. My Bookings
   - Users can access a **My Reservations** section to manage their bookings.
   - **View Bookings**: A list of upcoming events the user is booked for, including:
     - Event name, date/time, location, booking status, and guest tickets.
     - Screenshot: [My Bookings](./public-mockup/4a%20My%20Bookings.png)
   - **Edit Booking**:
     - Update the number of guest tickets.
     - Add the event to their calendar.
     - Screenshot: [Edit Booking](./public-mockup/4b%20My%20Bookings%20-%20Change%20num%20Guests%20-%20OPTIONAL.png)
   - **Cancel Booking**:
     - Users can cancel their reservations with a confirmation prompt.
     - Screenshot: [Cancel Booking](./public-mockup/4c%20My%20Bookings%20-%20Cancel%20Booking.png)

# Summary
The Uber Partner Events Website streamlines event organization for Uber’s city teams while empowering drivers to connect through in-person activities. It offers robust functionality for admins to manage events and attendees and for drivers to explore and participate in enriching experiences.