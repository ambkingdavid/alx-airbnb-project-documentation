# 🎯 Use Case Diagram: Airbnb Clone Backend

## 👥 Actors
- **Guest**: A user who books properties
- **Host**: A user who lists properties
- **Admin**: A system administrator
- **Payment Gateway**: External service for processing payments

---

## 📌 Use Cases by Actor

### 🧑 Guest
- Register an account
- Log in / Log out
- Search for properties
- View property details
- Make a booking
- Cancel a booking
- Make a payment
- Leave a review
- Send message to host

### 🧑‍💼 Host
- Register an account
- Log in / Log out
- Create property listing
- Edit property listing
- Delete property listing
- View bookings for their properties
- Respond to guest messages
- Respond to reviews

### 🛡️ Admin
- Manage users (activate/deactivate)
- Manage listings (approve/remove)
- View system analytics
- Handle disputes

### 💳 Payment Gateway
- Process guest payments
- Trigger host payouts
- Handle payment failures

---

## 🖼️ Diagram Layout Tips for Draw.io

1. **Actors**: Place actors on the left and right edges of the canvas.
2. **System Boundary**: Draw a large rectangle labeled “Airbnb Clone Backend”.
3. **Use Cases**: Inside the system boundary, use ovals to represent each use case.
4. **Connections**: Use solid lines to connect actors to their use cases.
5. **Include Relationships**:
   - Use “include” or “extend” arrows where appropriate (e.g., “Make Booking” → “Make Payment”).
   - Group related use cases (e.g., Booking flow, Property management).

---

## ✅ Example Use Case Relationships

- “Make Booking” → includes → “Make Payment”
- “Leave Review” → extends → “Complete Booking”
- “Create Listing” → includes → “Upload Property Images”

---
