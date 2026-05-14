
 SOQL :

SOQL (Salesforce Object Query Language) is used to retrieve data from Salesforce objects.
It is similar to SQL but works with objects instead of tables.

Example:

* Retrieve all Accounts
* Get Contacts related to an Account

---
Apex Trigger:

An Apex Trigger is code that automatically executes when a record is created, updated, deleted, or restored in Salesforce.

Triggers help automate business logic based on data changes.

---

🔄 Flow vs Trigger

| Feature     | Flow                         | Apex Trigger                |
| ----------- | ---------------------------- | --------------------------- |
| Type        | Declarative (No Code)        | Programmatic (Code)         |
| Complexity  | Simple                       | Complex                     |
| Maintenance | Easy                         | Requires developer          |
| Use Case    | Email alerts, simple updates | Complex logic, integrations |

---

 🔁 Before vs After Trigger

| Type           | Use Case                                                   |
| -------------- | ---------------------------------------------------------- |
| Before Trigger | Update/validate data before saving                         |
| After Trigger  | Perform actions after record is saved (email, integration) |

---

 Trigger Use Cases (College System)

1. After student registration → Send welcome email
2. After course is full → Notify faculty
3. After attendance drops below 75% → Send warning
4. After fee payment → Update student status
5. After result published → Notify students

---

Query Examples (English)

* Find all students in Course A
* Find all courses handled by Faculty X
* Find students with attendance below 75%
* Find students who did not pay fees
* Find top scoring students

---

 Reflection :

### Why do enterprise systems need event-driven behavior?

Enterprise systems must react automatically to data changes to ensure real-time processing, reduce manual work, and improve efficiency.

### Why systems react automatically?

Because:

* Saves time
* Reduces errors
* Improves user experience
* Enables real-time automation

---
<img width="1418" height="715" alt="Screenshot 2026-05-14 at 5 36 58 PM" src="https://github.com/user-attachments/assets/cae9fe89-90ed-4ffc-afc1-156c82d127b9" />
<img width="1416" height="723" alt="Screenshot 2026-05-14 at 5 18 14 PM" src="https://github.com/user-attachments/assets/6620d7cd-6f9d-43e5-a1b2-440e2b0e74c0" />
