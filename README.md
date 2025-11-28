

 Prerequisites

- Node.js 
- Git

Clone the Repository

```bash
git clone ......
```



 Frontend Setup


cd frontend
npm install
npm run dev


 Admin Panel Setup


cd admin
npm install
npm run dev



API, URL Documentation

Authentication Endpoints

- `POST /api/auth/register` - User registration
- `POST /api/auth/login` - User login
- `GET /api/auth/me` - Get current user
- `POST /api/auth/forgot-password` - Password reset request

 User Management

- `GET /api/users` - Get all users (Admin/Warden)
- `GET /api/users/:id` - Get specific user
- `PUT /api/users/:id` - Update user profile
- `DELETE /api/users/:id` - Delete user (Admin)

 Room Management

- `GET /api/rooms` - Get all rooms
- `POST /api/rooms` - Create room (Admin)
- `PUT /api/rooms/:id` - Update room
- `POST /api/rooms/:id/book` - Book room

Payment System

- `GET /api/payments` - Get payments
- `POST /api/payments` - Create payment
- `POST /api/payments/verify` - Verify Razorpay payment
 Complaint Management

- `GET /api/complaints` - Get complaints
- `POST /api/complaints` - Create complaint
- `PUT /api/complaints/:id` - Update complaint
- `POST /api/complaints/:id/resolve` - Resolve complaint

TEST THÌ BỎ API Ở URL dẫn vào web http://localhost:3000/..... (điền cái cần xem)
/Dashboard
⭐ Rooms:
bash
Copy code
/rooms
⭐ Students:
bash
Copy code
/admin/users
⭐ Complaints:
bash
Copy code
/complaints
⭐ Payments:
bash
Copy code
/payments
⭐ Visitors:
bash
Copy code
/visitors