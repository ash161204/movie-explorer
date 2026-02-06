# 🎬 Movie Explorer

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

**Movie Explorer** is a modern, responsive web application that allows users to discover, search, and view detailed information about movies. Built with **React** and **Vite**, it leverages the **TMDB API** to provide real-time data on trending films, ratings, and cast details.

This project demonstrates proficiency in modern frontend development, including client-side routing, asynchronous data fetching, and responsive UI design.

---

## 🚀 Features

- **🔍 Dynamic Search:** Real-time movie search functionality by title.
- **🔥 Trending & Popular:** Automatically fetches and displays trending movies upon loading.
- **📱 Fully Responsive:** Optimized layout for desktop, tablet, and mobile devices.
- **⚡ High Performance:** Powered by Vite for lightning-fast HMR (Hot Module Replacement) and optimized builds.
- **🧭 Client-Side Routing:** Seamless navigation without page reloads using React Router.

---

## 🛠️ Tech Stack

| Domain | Technologies |
| :--- | :--- |
| **Frontend** | React (Hooks, Functional Components) |
| **Build Tool** | Vite |
| **Styling** | CSS Modules / Tailwind CSS |
| **Routing** | React Router DOM |
| **API** | The Movie Database (TMDB) API |
| **Deployment** | Render |

---

## 📂 Project Structure

```text
movie-explorer/
├── public/              # Static assets (favicons, manifest)
├── src/
│   ├── components/      # Reusable UI components (MovieCard, Navbar)
│   ├── pages/           # Page views (Home, MovieDetails, SearchResults)
│   ├── services/        # API service functions (fetch calls)
│   ├── styles/          # Global styles and theme variables
│   ├── App.jsx          # Main application component & routing logic
│   └── main.jsx         # Entry point (DOM rendering)
├── .env                 # Environment variables (API Key)
├── package.json         # Dependencies and scripts
└── vite.config.js       # Vite configuration
🏁 Getting Started
Follow these instructions to set up the project locally.

1. Prerequisites
Ensure you have Node.js (v14 or higher) and npm installed.

2. Clone the Repository
Bash
git clone [https://github.com/ash161204/movie-explorer.git](https://github.com/ash161204/movie-explorer.git)
cd movie-explorer
3. Install Dependencies
Bash
npm install
4. Environment Configuration
Create a .env file in the root directory to store your API key.

Code snippet
VITE_API_KEY=your_tmdb_api_key_here
Note: You can get a free API key by registering at The Movie Database (TMDB).

5. Run the Application
Start the development server:

Bash
npm run dev
Open your browser and navigate to http://localhost:5173.

🚀 Deployment
This project is optimized for deployment on platforms like Vercel, Netlify, or Render.

Build for Production:

Bash
npm run build
The output will be in the dist/ folder, ready to be served by any static host.

🤝 Contributing
Contributions are welcome! If you have suggestions for improvements or bug fixes:

Fork the repository.

Create a new branch (git checkout -b feature-name).

Commit your changes.

Push to the branch and open a Pull Request.

📄 License
This project is open-source and available under the MIT License.

👤 Author
Ash - GitHub: @ash161204

LinkedIn: [Ashish Medithe](https://www.linkedin.com/in/ashish-medithe-904634231/) 

Built with ❤️ using React & Vite
