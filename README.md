# Raktadaan: Blood Bank Management System
![developer](https://img.shields.io/badge/Developed%20By%20%3A-Gaurav-red)
---


## Functions

### Admin
- Create Admin account using the following command

py manage.py createsuperuser

vbnet

- After login, the admin can see the units of blood for each blood group available, the number of donors, the number of blood requests, the number of approved requests, and the total units of blood on the dashboard.
- Can view, update, delete donors.
- Can view, update, delete patients.
- Can view donation requests made by donors and can approve or reject them based on the donor's disease.
- If a donation request is approved by the admin, the unit of blood is added to the blood stock of that blood group.
- If a donation request is rejected by the admin, 0 units of blood are added to the stock.
- Can view blood requests made by donors/patients and can approve or reject them.
- If a blood request is approved by the admin, the unit of blood is reduced from the blood stock of that blood group.
- If a blood request is rejected by the admin, 0 units of blood are reduced from the stock.
- Can see the history of blood requests.
- Can update the unit of a particular blood group.

### Donor
- Donors can create an account by providing basic details.
- After login, donors can donate blood, and after approval from the admin, the blood will be added to the blood stock.
- Donors can see their donation history with status (Pending, Approved, Rejected).
- Donors can also request blood from the blood stock.
- Donors can see their blood request history with status.
- Donors can see the number of blood requests made, approved, pending, and rejected by the admin on their dashboard.
> **_NOTE:_**  Donors can donate blood and can also request blood.

### Patient
- Patients can create an account (No approval required by the admin, can log in after signup).
- After login, patients can see the number of blood requests made, approved, pending, and rejected by the admin on their dashboard.
- Patients can request blood of a specific blood group and unit from the blood stock.
- Patients can see their blood request history with status (Pending, Approved, Rejected).

---

## HOW TO RUN THIS PROJECT
- Install Python (Don't forget to tick "Add to Path" while installing Python).
- Download this project zip folder and extract it.
- Move to the project folder in Terminal. Then run the following commands:

python -m pip install -r requirements.txt

py manage.py makemigrations
py manage.py migrate
py manage.py runserver

- Now enter the following URL in your web browser installed on your PC:

http://127.0.0.1:8000/


## Feedback
Any suggestions and feedback are welcome. You can contact me via email or LinkedIn.
