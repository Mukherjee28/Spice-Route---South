Spice Route – South

A smart personalized South Indian cuisine recommendation platform with dynamic cart functionality. The system tailors dish recommendations based on user taste preferences and allows users to order food with a smart cart system.


---

✨ Features

🔐 User registration & login with encryption

🍽️ Personalized dish recommendations

🛒 Dynamic shopping cart with live updates

📧 Email notification on sign-up

📱 Fully responsive UI

🌶️ South Indian food category-based filtering

🗄️ MongoDB-backed persistent user & order data



---

🏗️ Tech Stack

Layer	Technology

Frontend	HTML, CSS, JavaScript
Backend	Node.js + Express.js
Database	MongoDB + Mongoose
Auth	bcrypt + express-session
Email	Nodemailer (Gmail SMTP)
Logic	Preference-based recommendation system



---

📂 Folder Structure

spice-route-south/
│── server.js
│── package.json
│── public/
│   ├── index.html
│   ├── style.css
│   └── script.js
│── models/
│   └── User.js
│── routes/
│   └── auth.js
│── database/
│   └── config.js
│── README.md


---

⚙️ Installation & Setup

1️⃣ Install dependencies

npm install

2️⃣ Configure MongoDB & environment variables

Add .env:

MONGO_URI=your_connection_string
SESSION_SECRET=your_secret
EMAIL_ID=your_email@gmail.com
EMAIL_PASS=your_app_password

3️⃣ Start server

node server.js


---

👩‍🍳 Recommendation Logic

✔️ User selects food preferences
✔️ System stores preference profile
✔️ Menu items matched by category & taste profile
✔️ Suggested dishes appear in UI

---

🚀 Future Enhancements

AI-based food taste prediction

Delivery partner integration

UPI payment gateway

Voice-based dish search



---

👤 Credits

Developed as a full-stack project showcasing
recommendation systems + web development + database programming
