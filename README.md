Raktadaan: Blood Bank Management System
Overview

Raktadaan is a comprehensive web application developed using Django, aimed at streamlining blood donation activities, donor and patient management, and administrative tasks within blood banks or healthcare facilities.
Features

    User Roles: Raktadaan supports three user roles:
        Donor: Individuals interested in donating blood can register, view their donation history, and update their profile information.
        Patient: Patients in need of blood can search for donors based on blood type and availability.
        Admin: Administrators have full access to system features, including managing donors, patients, blood inventory, and user accounts.

    Donor Management: Donors can register, update their contact details, view donation history, and receive notifications about upcoming donation events.

    Patient Management: Patients can search for blood donors based on specific criteria such as blood type, location, and availability. They can also request blood donations and track donation statuses.

    Blood Inventory Management: Admins can manage the blood inventory, including adding new donations, updating availability status, and monitoring expiration dates.

    Appointment Scheduling: Donors can schedule appointments for blood donations, and admins can manage and track donation appointments.

    Notifications: Donors and patients receive notifications about donation events, appointment reminders, and updates on donation requests.

Installation

    Clone the repository:

    bash

git clone https://github.com/your/repository.git

Install dependencies:

pip install -r requirements.txt

Run migrations:

python manage.py migrate

Start the development server:

    python manage.py runserver

    Access the application at http://localhost:8000 in your web browser.



Usage

    User Registration/Login: Users can register for a new account or log in with existing credentials based on their role (donor, patient, or admin).
    Donor Actions: Donors can do donate blood request, view donation history as well as request blood donationa and track both status.
    Patient Actions: Patients can request blood donations, and track donation statuses.
    Admin Actions: Admins can manage users, blood inventory, donation appointments,system settings and manage blood unit.
