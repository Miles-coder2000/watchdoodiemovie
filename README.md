# WatchDoodie 2.0 🎬

A modern, feature-rich movie and TV series streaming platform built with React and styled with Tailwind CSS. WatchDoodie provides an intuitive interface for browsing, searching, and streaming movies and TV shows with comprehensive details and multiple viewing options.

![WatchDoodie Logo](public/Doodie.png)

## 🌟 Features

- **Comprehensive Browsing**: Explore trending, popular, and categorized content
- **Advanced Search**: Find movies, TV shows, and people with real-time search
- **Detailed Information**: View comprehensive details including cast, crew, ratings, and reviews
- **Multi-Source Streaming**: Multiple streaming links for enhanced availability
- **Responsive Design**: Seamless experience across desktop and mobile devices
- **Season & Episode Navigation**: Complete TV series browsing with season/episode breakdown
- **Watch Providers**: Integration with streaming platform availability information
- **Person Profiles**: Detailed actor and crew member information and filmographies

## 🛠️ Technologies Used

- **Frontend Framework**: React 18.2.0
- **Build Tool**: Vite
- **Styling**: Tailwind CSS
- **State Management**: Redux Toolkit
- **Routing**: React Router DOM
- **HTTP Client**: Axios
- **Video Player**: React Player
- **Infinite Scroll**: React Infinite Scroll Component
- **Icons**: RemixIcon
- **Analytics**: Vercel Analytics

## 🚀 Quick Start

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn package manager
- TMDB API key ([Get one here](https://www.themoviedb.org/documentation/api))

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Miles-coder200/watchdoodiemovie.git
   cd watchdoodiemovie
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   
   Create a `.env` file in the root directory:
   ```env
   VITE_TMDB_API=your_tmdb_api_key_here
   VITE_BASE_URL=https://api.themoviedb.org/3
   ```

4. **Start the development server**
   ```bash
   npm run dev
   ```

5. **Open your browser**
   
   Navigate to `http://localhost:5173` to view the application.

## 📁 Project Structure

```
watchdoodiemovie/
├── public/
│   ├── Doodie.png          # Application logo
│   ├── 404.jpg             # 404 error image
│   ├── loading.gif         # Loading animation
│   └── noimg.jpg           # Placeholder image
├── src/
│   ├── components/
│   │   ├── store/          # Redux store configuration
│   │   │   ├── actions/    # Redux actions
│   │   │   └── reducers/   # Redux reducers
│   │   ├── templates/      # Reusable UI components
│   │   │   ├── Cards.jsx
│   │   │   ├── HorizontalCards.jsx
│   │   │   ├── Header.jsx
│   │   │   ├── Sidenav.jsx
│   │   │   ├── Topnav.jsx
│   │   │   └── Trailer.jsx
│   │   ├── Home.jsx        # Homepage component
│   │   ├── Movie.jsx       # Movies listing
│   │   ├── MovieDetails.jsx # Movie details page
│   │   ├── Tvshows.jsx     # TV shows listing
│   │   ├── TvDetails.jsx   # TV show details page
│   │   ├── People.jsx      # People/cast listing
│   │   ├── PersonDetails.jsx # Person profile page
│   │   ├── Trending.jsx    # Trending content
│   │   ├── Popular.jsx     # Popular content
│   │   └── Loading.jsx     # Loading component
│   ├── utils/
│   │   └── axios.js        # API configuration
│   ├── App.jsx             # Main app component
│   ├── main.jsx           # Application entry point
│   └── index.css          # Global styles
├── .env                   # Environment variables
├── package.json
├── tailwind.config.js     # Tailwind configuration
└── vite.config.js        # Vite configuration
```

## 🎯 Key Features Breakdown

### 🏠 Homepage
- Dynamic header with trending content
- Categorized content sections
- Responsive navigation

### 🔍 Search & Discovery
- Real-time search across movies, TV shows, and people
- Advanced filtering options
- Infinite scroll pagination

### 🎬 Movie & TV Show Details
- Comprehensive information display
- Multiple streaming options
- Trailer integration
- Cast and crew details
- Similar and recommended content

### 👥 Person Profiles
- Actor/crew member biographies
- Complete filmographies
- Social media links
- Career statistics

### 📱 Responsive Design
- Mobile-first approach
- Optimized layouts for all screen sizes
- Touch-friendly navigation

## 🌐 API Integration

The application integrates with The Movie Database (TMDB) API to fetch:

- Movie and TV show information
- Cast and crew details
- Images and videos
- Ratings and reviews
- Streaming provider information

## 📱 Mobile Optimization

- Custom responsive breakpoints
- Mobile-specific UI adjustments
- Touch-optimized interactions
- Efficient loading for mobile networks

## 🚀 Deployment

### Build for Production

```bash
npm run build
```

### Preview Production Build

```bash
npm run preview
```

The application is configured for deployment on platforms like Vercel, Netlify, or any static hosting service.

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [TMDB](https://www.themoviedb.org/) for providing the comprehensive movie database API
- [React](https://react.dev/) for the amazing frontend framework
- [Tailwind CSS](https://tailwindcss.com/) for the utility-first CSS framework
- All the open-source libraries that made this project possible

## 📞 Support

If you encounter any issues or have questions:

- Create an issue on [GitHub](https://github.com/Miles-coder200/watchdoodiemovie/issues)
- Contact: mileslandersotelogarcia@gmail.com

## 🌟 Show Your Support

If you found this project helpful, please give it a ⭐ on GitHub!

---

**Made with ❤️ by Miles** | [Facebook](https://www.facebook.com/miles.garcia26)
