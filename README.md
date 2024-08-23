# 🎧 SpotifyClone

Welcome to **SpotifyClone**! This project is a replica of the Spotify application, built using **React.js** and **Tailwind CSS**.

## 📑 Table of Contents

- [📝 Overview](#-overview)
- [✨ Features](#-features)
- [🛠️ Technologies Used](#-technologies-used)
- [📂 Project Structure](#-project-structure)
- [⚙️ Installation](#-installation)
- [🚀 Usage](#-usage)
- [🤝 Contributing](#-contributing)
- [📬 Contact](#-contact)

## 📝 Overview

**SpotifyClone** is a web application that mimics the core functionalities of Spotify, including music navigation, playback, playlist management, and more.

## ✨ Features

- **🔑 Registration and Login**: Create an account or log in with your credentials.
- **🔍 Music Search**: Search for your favorite artists, albums, and tracks.
- **🎵 Music Playback**: Play, pause, and skip tracks.
- **🎶 Playlists**: Create, edit, and delete playlists.
- **📱 Responsive UI**: Designed to be used on devices of all sizes.

## 🛠️ Technologies Used

- **⚛️ React.js**: JavaScript library for building the user interface.
- **🛠️ Redux**: State management for the application.
- **🌐 React Router**: For navigation between pages.
- **📡 Axios**: For HTTP requests.
- **🎧 Spotify Web API**: For fetching data from Spotify.
- **🎨 Tailwind CSS**: For styling components.
- **💅 Styled Components**: For styling components.
- **📂 assets.js**: For storing track and album information.

## 📂 Project Structure

Here’s an overview of the project structure:


SpotifyClone/
│
├── public/
│ ├── index.html
│ └── ...
│
├── src/
│ ├── components/
│ │ ├── AlbumItem.jsx
│ │ ├── Display.jsx
│ │ ├── DisplayAlbum.jsx
│ │ ├── DisplayHome.jsx
│ │ ├── Navbar.jsx
│ │ ├── Player.jsx
│ │ ├── Sidebar.jsx
│ │ ├── SongItem.jsx
│ │ └── ...
│ │
│ ├── context/
│ │ └── PlayerContext.jsx
│ │
│ ├── assets.js
│ ├── App.js
│ ├── index.js
│ └── ...
│
├── .env
├── package.json
├── README.md
└── ...

## ⚙️ Installation

To run this project locally, follow these steps:

1. Clone the repository

   ```bash
   git clone https://github.com/your-username/SpotifyClone.git

2. Navigate to the project directory
   ```bash
      cd SpotifyClone

3. Install dependencies
    ```bash
    npm install

4. Create a .env file at the root of the project and add your Spotify API keys:
    ```bash
    REACT_APP_SPOTIFY_CLIENT_ID=your_spotify_client_id
    REACT_APP_SPOTIFY_CLIENT_SECRET=your_spotify_client_secret

5. Start the application
    ```bash
      npm start

## 🚀 Usage
Once the application is started, open your browser and go to http://localhost:3000. You can now explore the features of SpotifyClone.

## 🤝 Contributing
Contributions are welcome! To contribute:

1. Fork the project
2. Create a branch for your feature (git checkout -b feature/your-feature-name)
3. Commit your changes (git commit -m 'Add feature')
4. Push to your branch (git push origin feature/your-feature-name)
5. Open a Pull Request


## 📬 Contact

For any questions or suggestions, you can reach me via [LinkedIn](https://www.linkedin.com/in/alahyane-oussama/).

