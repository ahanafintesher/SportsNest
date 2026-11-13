# 🏟️ SportNest

**Find & Book Sports Facilities Near You**

> Discover premium sports venues, check real-time availability, and secure your slot — all in one place. No calls, no hassle.

---

### Description

SportsNest is a full-stack sports facility booking platform where users can discover sports facilities, check availability, and book their preferred time slots. Facility owners can add and manage their facilities, track bookings, and manage their listings through a dedicated dashboard. The platform features role-based authentication, Google sign-in, and a booking system designed to prevent duplicate slot reservations.

## 🌐 Live URL

🔗 [https://sports-nest-ten.vercel.app](https://sports-nest-ten.vercel.app)

---

## 📁 GitHub Repository

🔗 [https://github.com/ahanafintesher/Assignment-09-SportsNest](https://github.com/ahanafintesher/Assignment-09-SportsNest)

---

## 📸 Screenshots

<img width="1917" height="898" alt="image" src="https://github.com/user-attachments/assets/65d1980a-5b3e-49be-bf11-6c1d7441539b" />



---

## 🎯 Purpose

SportNest is a modern sports facility booking platform that allows users to:
- Browse and discover premium sports venues
- Check real-time availability of courts and fields
- Book their desired slot instantly — without any phone calls or hassle

---

## ✨ Features

- 🏠 **Home Page** — Engaging landing page with hero section and key stats
- 🏟️ **All Facilities** — Browse all available sports facilities
- 📅 **My Bookings** — View and manage your personal bookings
- ➕ **Add Facility** — Add new sports facilities to the platform
- ⚙️ **Manage My Facilities** — Edit or remove your listed facilities
- 🔐 **Authentication** — Secure login/signup with Better Auth
- 📊 **Stats** — 200+ Facilities, 50K+ Bookings, 15+ Sports, 4.9★ Rating

---


## 🛠️ Technology Stack

### Frontend
| Technology | Purpose |
|---|---|
| Next.js 16 | Full-stack React Framework |
| React 19 | UI Development |
| JavaScript (ES6+) | Programming Language |
| Tailwind CSS 4 | Styling |
| HeroUI 3 | UI Components |
| Framer Motion | Animations & Transitions |
| Lucide React | Icons |
| React Icons | Icon Library |
| React Hot Toast | Toast Notifications |

### Backend & Database
| Technology | Purpose |
|---|---|
| Next.js API Routes | Backend API Development |
| MongoDB | NoSQL Database |
| MongoDB Driver | Database Integration |
| Better Auth | Authentication |
| Better Auth Mongo Adapter | MongoDB Authentication Integration |

### Development Tools
| Technology | Purpose |
|---|---|
| ESLint 9 | Code Linting |
| Babel React Compiler | React Performance Optimization |
| npm | Package Management |
| Git & GitHub | Version Control |

### Deployment
| Technology | Purpose |
|---|---|
| Vercel | Hosting & Deployment |


## 📦 NPM Packages Used

### Dependencies

| Package | Version | Purpose |
|---|---|---|
| `next` | 16.2.6 | React framework for production |
| `react` | 19.2.4 | UI library |
| `react-dom` | 19.2.4 | React DOM rendering |
| `better-auth` | ^1.6.11 | Authentication library |
| `@better-auth/mongo-adapter` | ^1.6.11 | MongoDB adapter for Better Auth |
| `@heroui/react` | ^3.0.5 | UI component library |
| `@heroui/styles` | ^3.0.5 | HeroUI styles |
| `@heroui/system` | ^2.4.28 | HeroUI system utilities |
| `mongodb` | ^7.2.0 | MongoDB database driver |
| `framer-motion` | ^12.38.0 | Animations and transitions |
| `lucide-react` | ^1.16.0 | Icon library |
| `react-hot-toast` | ^2.6.0 | Toast notifications |
| `react-icons` | ^5.6.0 | Popular icon packs |

### Dev Dependencies

| Package | Version | Purpose |
|---|---|---|
| `tailwindcss` | ^4 | Utility-first CSS framework |
| `@tailwindcss/postcss` | ^4 | Tailwind PostCSS plugin |
| `eslint` | ^9 | Code linting |
| `eslint-config-next` | 16.2.6 | Next.js ESLint config |
| `@gravity-ui/icons` | ^2.18.0 | Gravity UI icons |
| `babel-plugin-react-compiler` | 1.0.0 | React compiler Babel plugin |

---

## 🚀 Getting Started

### Prerequisites

- Node.js (v18+)
- MongoDB database

### Installation

```bash
# Clone the repository
git clone https://github.com/ahanafintesher/Assignment-09-SportsNest.git

# Navigate to the project directory
cd Assignment-09-SportsNest

# Install dependencies
npm install

# Run the development server
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## 🛠️ Built With

- **Next.js** — Full-stack React framework
- **HeroUI** — Modern UI components
- **Tailwind CSS** — Styling
- **Better Auth** — Authentication
- **MongoDB** — Database
- **Framer Motion** — Animations
- **Vercel** — Deployment

---


## 🚧 Challenges Faced During Development

While developing SportsNest, I faced several challenges:

- Implementing real-time sports facility availability and booking functionality.
- Preventing users from booking the same time slot simultaneously.
- Managing user and facility owner roles with proper access control.
- Integrating secure authentication with Google Sign-In.
- Building a responsive and user-friendly interface for different screen sizes.
- Managing booking data and maintaining consistency between facilities and bookings.

## 🛠️ Why I Chose These Technologies

| Technology | Why I Used It |
|------------|---------------|
| Next.js | To build a fast, SEO-friendly, full-stack React application. |
| React.js | To create reusable and interactive UI components. |
| MongoDB | To store users, facilities, and booking information flexibly. |
| Better Auth | To implement secure authentication and Google Sign-In. |
| HeroUI | To build modern and reusable UI components. |
| Tailwind CSS | To create responsive layouts efficiently. |
| Framer Motion | To add smooth animations and transitions. |
| Lucide React | To maintain consistent and clean icons. |
| React Hot Toast | To display user-friendly success and error notifications. |
| Vercel | To deploy the application and make it accessible online. |

## 💡 Challenges Solved

- **Duplicate Booking Prevention:** Implemented server-side validation to prevent multiple users from booking the same facility and time slot.
- **Real-Time Availability:** Developed availability-checking functionality so users can see which time slots are available before booking.
- **Role-Based Access Control:** Separated User and Owner permissions to ensure users can only access authorized features.
- **Facility Management:** Enabled facility owners to add, update, and remove their listed facilities.
- **Booking Management:** Implemented functionality for users to view and manage their bookings.
- **Secure Authentication:** Integrated Better Auth with Google Sign-In for a secure authentication experience.
- **Data Consistency:** Added booking validation to maintain accurate facility availability and prevent conflicting reservations.


## 👤 Author

**Ahanaf Intesher**

---

> ⭐ If you like this project, give it a star on GitHub!
