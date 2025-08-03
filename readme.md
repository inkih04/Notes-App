# 📝 Notes App

A modern and collaborative web application for notes and notebooks management, built with React (frontend) and Django (backend). Allows creating, editing, and sharing notebooks collaboratively in real-time.

## 🌐 Live Demo

**🚀 Web Application:** [https://notes-app-frontend-yv8o.vercel.app/](https://notes-app-frontend-yv8o.vercel.app/)

**⚠️ Performance Note**
The application is deployed using **free tiers** of Vercel (frontend) and Render (backend), so:
- 🐌 **First access**: May take up to **1 minute** to load when there hasn't been recent activity
- ⏱️ **Performance**: Speed may be lower than optimal due to free plan limitations
- 😴 **Hibernation**: The backend on Render goes into hibernation mode after periods of inactivity

---

## ✨ Main Features

- 📚 **Notebook Management**: Create and organize your notebooks intuitively
- 📝 **Notes Editor**: Edit your notes with a clean and modern interface
- 👥 **Real-Time Collaboration**: Share notebooks and work simultaneously with other users
- 📱 **Responsive Design**: Optimized for both desktop and mobile devices
- 🔐 **Google Authentication**: Secure and simple login
- 🎨 **Modern Interface**: Attractive and functional design
- 🔄 **RESTful API**: Robust backend with JWT and OAuth2

---

## 🛠️ Technologies Used

### Frontend
- **React** - JavaScript library for building user interfaces
- **Vite** - Fast and modern build tool
- **Google OAuth** - Secure authentication
- **Responsive CSS** - Adaptable design for all devices

### Backend
- **Django** - Python web framework
- **Django REST Framework** - RESTful API
- **Google OAuth 2.0** - Authentication
- **JWT** - Access and refresh tokens
- **SQLite/PostgreSQL** - Database

---

## 📁 Project Repositories

### 🎨 Frontend (React + Vite)
**Repository:** [Notes-App-Frontend](https://github.com/inkih04/Notes-App-Frontend)
- Modern and responsive user interface
- State management with React hooks
- Backend API integration
- Real-time collaboration

### ⚙️ Backend (Django + DRF)
**Repository:** [Notes-App-Backend](https://github.com/inkih04/Notes-App-Backend)
- Complete RESTful API
- OAuth2 and JWT authentication
- CRUD operations for notes and notebooks
- CORS configuration for frontend

**🌐 Production API:** [https://notes-app-backend-37a9.onrender.com/](https://notes-app-backend-37a9.onrender.com/)

---

## 🚀 Installation and Setup

### Prerequisites
- Node.js (version 14 or higher)
- Python 3.10+
- Git

### Frontend
```bash
git clone https://github.com/inkih04/Notes-App-Frontend.git
cd Notes-App-Frontend
npm install
./run-dev.sh
```

### Backend
```bash
git clone https://github.com/inkih04/Notes-App-Backend.git
cd Notes-App-Backend
./run-localDev.sh
```

For detailed installation instructions, check the specific README files in each repository.

---

## 📸 Screenshots

<!-- Space reserved for your web photos -->

### 🖥️ Desktop View
![](https://github.com/inkih04/Notes-App/blob/main/notes/Notebook.png)
![](https://github.com/inkih04/Notes-App/blob/main/notes/notes.png)
![](https://github.com/inkih04/Notes-App/blob/main/notes/CreateNote.png)


### 📱 Mobile View
<img src="https://github.com/inkih04/Notes-App/blob/main/notes/LoginM.jpg" width="360" height="400">
<img src="https://github.com/inkih04/Notes-App/blob/main/notes/NotebooksM.jpg" width="360" height="400">
<img src="https://github.com/inkih04/Notes-App/blob/main/notes/SidebarM.jpg" width="360" height="400">
<img src="https://github.com/inkih04/Notes-App/blob/main/notes/NotesM.jpg" width="360" height="400">
<img src="https://github.com/inkih04/Notes-App/blob/main/notes/NewNoteM.jpg" width="360" height="400">


### 👥 Collaboration
![](https://github.com/inkih04/Notes-App/blob/main/notes/share.png)

### 📝 Notes Editor
![](https://github.com/inkih04/Notes-App/blob/main/notes/edit.png)

---

## 📱 Compatibility

The application is fully optimized for:
- 💻 **Desktop**: Complete experience with all functionalities
- 📱 **Mobile**: Interface adapted for touch screens
- 📊 **Tablet**: Hybrid design that takes advantage of available space

---

## 🏗️ System Architecture

```
Notes App
├── Frontend (React + Vite)
│   ├── User interface
│   ├── State management
│   └── API communication
│
└── Backend (Django + DRF)
    ├── RESTful API
    ├── OAuth2/JWT authentication
    └── Database
```

---

## 🤝 Collaboration and Contributions

Contributions are welcome! To contribute:

1. Fork the corresponding repository
2. Create a branch for your feature (`git checkout -b feature/new-functionality`)
3. Make your changes and commit (`git commit -am 'Add new functionality'`)
4. Push to the branch (`git push origin feature/new-functionality`)
5. Open a Pull Request

**Note:** Active development is done on the `dev` branch of both repositories.

---

## 🙋‍♂️ Support

If you have any questions or encounter any issues, feel free to open an issue in the corresponding repository.

---

## 🧑‍💻 Author

**Developed with ❤️ by [@inkih04](https://github.com/inkih04)**

---

**Like the project? ⭐ Give it a star on GitHub!**
