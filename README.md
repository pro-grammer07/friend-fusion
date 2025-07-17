#  FriendFusion — A Social Media App built using MERN stack

**FriendFusion** is a modern social media web app built with the **MERN** stack. It tackles the problems of algorithmic bias, privacy intrusion, and lack of transparency seen in traditional platforms. Our goal? Create a space where users can interact freely, securely, and fairly — without manipulation.

> Designed with fairness, privacy, and user control at its core.

---


## 🛠️ Tech Stack

| Layer       | Technology                         |
|------------|-------------------------------------|
| Frontend   | React.js, Redux, Tailwind CSS       |
| Backend    | Node.js, Express.js                 |
| Database   | MongoDB + Mongoose                  |
| Auth       | JWT, bcrypt, Nodemailer             |
| Tools      | Axios, ThunderClient, UUID          |

---

## ✨ Features

### 🔐 Secure Authentication
- Email verification
- Password reset via secure tokens
- JWT-based login and protected routes

### 👥 Friend System
- Send/accept/reject friend requests
- Friend suggestions based on shared interests

### 📝 Social Feed
- Create posts with text/images
- Like, comment, and reply to posts
- Personalized feed from friends and connections

### 🎨 UI Customization
- Light and dark mode toggle
- Tailored settings for theme, notifications, and privacy


---

## 🔁 API Highlights

### Authentication Routes
- `POST /auth/register` – Create a new user account  
- `POST /auth/login` – Authenticate user and return JWT  
- `POST /auth/reset` – Handle password reset flow

### User Routes
- `GET /users/profile` – Fetch user profile  
- `GET /users/friends` – Friend request system  
- `GET /users/search` – Search for users

### Post Routes
- `GET /posts/feed` – Fetch personalized feed  
- `POST /posts/create` – Create new post  
- `POST /posts/interaction` – Like, comment, reply

---

## 📸 Screenshots

<img width="975" height="488" alt="image" src="https://github.com/user-attachments/assets/9b17dded-dc0c-4401-8a22-6d3700d7f6a4" />

