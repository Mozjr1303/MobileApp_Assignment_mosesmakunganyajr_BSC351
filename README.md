**Alchemy Connect** is a smart platform and local events using passion into community action.tform that connects volunteers with Built with modern web technologies 

- **User Authentication**: Secure login and registration system with JWT tokens
- **Dual User Roles**: 
  - Volunteers can discover and join opportunities
  - Organizations can post and manage events
- **Real-time Recommendations**: Personalized event suggestions based on user interests
- **Responsive Design**: Beautiful, modern UI that works seamlessly on mobile and web
- **Native Android App**: Full Android application built with Capacitor

---

## 🛠️ Technology Stack

### Frontend
- **React 19.2.0** - Modern UI library
- **TypeScript** - Type-safe development
- **Vite** - Fast build tool and dev server
- **Lucide React** - Beautiful icon library

### Backend
- **Node.js & Express** - RESTful API server
- **JWT** - Secure authentication
- **bcrypt** - Password hashing
- **Express Validator** - Input validation
- **Helmet** - Security middleware
- **CORS** - Cross-origin resource sharing




- **Android SDK** - Native Android features

---

## 📸 Screenshots

### Web Application
![Login Screen](./screenshots/login.png)
*Secure authentication with modern UI design*

![Dashboard](./screenshots/dashboard.png)
*AI-powered volunteer opportunities dashboard*

![Event Details](./screenshots/event-details.png)
*Detailed event information and registration*

### Android Application
![Android Home](./screenshots/android-home.png)
*Native Android experience*

![Android Events](./screenshots/android-events.png)
*Browse events on mobile*

---

## 🚀 Installation & Setup

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn
- Android Studio (for Android development)
- Java JDK 17 or higher

### Web Application Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/MobileApp_Assignment_YourName_BSC351.git
   cd MobileApp_Assignment_YourName_BSC351
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   
   Create a `.env.local` file in the root directory:
   ```env
  

4. **Run the development server**
   ```bash
   npm run dev
   ```
   
   The app will be available at `http://localhost:3000`

5. **Run the backend server** (in a separate terminal)
   ```bash
   npm run backend
   ```
   
   Backend API will run on `http://localhost:3001`

### Android Application Setup

1. **Build the web application**
   ```bash
   npm run build
   ```

2
   ```

4. **Build and Run**
   - In Android Studio, click the "Run" button or press Shift+F10
   - Select your target device (emulator or physical device)
   - Wait for the build to complete and the app to launch

---

## 📁 Project Structure

```
alchemy-connect/
├── android/                    # Android native project
│   ├── app/
│   │   ├── src/
│   │   │   └── main/
│   │   │       ├── AndroidManifest.xml
│   │   │       ├── java/
│   │   │       └── res/
│   │   └── build.gradle
│   ├── build.gradle
│   └── settings.gradle
├── backend/                    # Backend API server
│   └── server.js              # Express server with authentication
├── components/                 # React components
│   ├── AuthForm.tsx           # Login/Register component
│   ├── Dashboard.tsx          # Main dashboard
│   ├── EventCard.tsx          # Event display component
│   └── ...
├── services/                   # API services
│   ├── api.ts                 # API client
│   └── gemini.ts              # AI integration
├── assets/                     # Static assets
├── App.tsx                     # Main application component
├── index.tsx                   # Application entry point
├── constants.ts                # App constants and configuration
├── types.ts                    # TypeScript type definitions
├── capacitor.config.ts         # Capacitor configuration
├── vite.config.ts             # Vite configuration
└── package.json               # Dependencies and scripts
```

---

## 🔑 Key Components

### Authentication System
- Secure user registration and login
- Password hashing with bcrypt
- JWT token-based authentication
- Role-based access control (Volunteer/Organization)



### Event Management
- Create and manage volunteer opportunities
- Browse available events
- Filter by category, location, and date
- Real-time updates

---

## 🎨 Design Features

- **Modern UI/UX**: Clean, intuitive interface with smooth animations
- **Responsive Design**: Optimized for all screen sizes
- **Dark Mode Ready**: Eye-friendly color scheme
- **Accessibility**: WCAG compliant design principles
- **Performance**: Optimized loading and rendering

---

## 🔒 Security Features

- Password hashing with bcrypt
- JWT token authentication
- Input validation and sanitization
- Rate limiting on API endpoints
- Helmet.js security headers
- CORS protection

---

## 📱 Android Features

- Native Android application
- Smooth performance
- Offline capability (planned)
- Push notifications (planned)
- Native device integration

---

## 🧪 Testing

### Run Tests
```bash
npm test
```

### Build for Production
```bash
npm run build
```

### Preview Production Build
```bash
npm run preview
```

---

## 📝 API Endpoints

### Authentication
- `POST /api/auth/register` - Register new user
- `POST /api/auth/login` - User login

### Events
- `GET /api/events` - Get all events
- `POST /api/events` - Create new event (Organization only)
- `GET /api/events/:id` - Get event details
- `PUT /api/events/:id` - Update event (Organization only)
- `DELETE /api/events/:id` - Delete event (Organization only)

### Recommendations
- `POST /api/recommendations` - Get AI-powered recommendations

---

## 🤝 Contributing

This is an academic project for BSC-351 Mobile Application Development. 

---

## 👨‍💻 Developer Information

- **Student Name**: [MOSES MAKUNGANYA JR]
- **Course**: BSC-351 DS 02 - Mobile Application Development - SEM-VI
- **Assignment**: Mobile App Assignment
- **Institution**: [DMI UNIVERSITY MANGOCHI]
- **Year**: 2025

---

## 📄 License

This project is created for educational purposes as part of the BSC-351 course.



## 📞 Contact

For questions or feedback about this project:
- Email: [mosesmakunganyajr@gmail.com]
- GitHub: [Your GitHub Profile]

---

## 🔮 Future Enhancements

- [ ] Push notifications for new opportunities
- [ ] Offline mode support
- [ ] Social sharing features
- [ ] Advanced filtering and search
- [ ] User profiles and achievements
- [ ] In-app messaging
- [ ] Calendar integration
- [ ] Location-based recommendations

---


