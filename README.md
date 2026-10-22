# Kirus shows 🎬

> A super modern, black & white streaming platform with cinematic poster backgrounds

## ✨ Features

- 🎨 **Ultra Modern Design** - Sleek black and white aesthetic
- 🖼️ **Cinematic Backgrounds** - Movie posters as blurred backgrounds
- 🎬 **Full Streaming** - Watch movies and TV shows with multiple sources
- 🔍 **Smart Search** - Real-time search with autocomplete
- 📱 **Fully Responsive** - Perfect on all devices
- 🎯 **Smooth Animations** - Butter-smooth transitions and effects
- 🎞️ **Multiple Players** - Trailer + 2 streaming sources

## 🚀 Quick Start

### Option 1: Direct Open
1. Open `index.html` in your browser
2. Start browsing!

### Option 2: Local Server (Recommended)
```bash
# Python 3
python -m http.server 8000

# Node.js
npx http-server -p 8000

# PHP
php -S localhost:8000
```

Then visit: `http://localhost:8000`

## 📁 File Structure

```
Nexify-watch/
├── index.html      # HTML structure
├── style.css       # Modern black & white styling
├── script.js       # All functionality
└── README.md       # This file
```

## 🎨 Design Highlights

### Color Scheme
- **Primary**: Pure Black (#000000)
- **Secondary**: Deep Black (#0a0a0a)
- **Tertiary**: Dark Gray (#141414)
- **Text**: Pure White (#ffffff)
- **Accents**: White with subtle grays

### Key Features
1. **Grayscale Posters** - All images start in grayscale, color on hover
2. **Blurred Backgrounds** - Poster images as atmospheric backgrounds
3. **Cinematic Hero** - Large hero section with poster overlay
4. **Minimal UI** - Clean, distraction-free interface
5. **Smooth Transitions** - Everything animated beautifully

## 🎯 Pages

### Home
- Hero section with random trending content
- Poster as blurred background
- Horizontal scrolling trending section
- Category filters (All, Movies, TV Shows)

### Trending
- Grid layout of trending content
- Filter by All, Movies, or TV Shows
- Grayscale posters with color on hover

### Popular
- Popular movies and TV shows
- Toggle between Movies and TV Shows
- Clean grid layout

### Movies
- Categories: Now Playing, Popular, Top Rated, Upcoming
- Full movie information
- Stream with 2 different sources

### TV Shows
- Categories: Airing Today, On The Air, Popular, Top Rated
- Episode information
- Stream with 2 different sources

### People
- Popular actors and celebrities
- Profile images
- Known for department

### Details Page
- Full-screen poster background (blurred, grayscale)
- Large poster display
- Complete information
- 3 action buttons:
  - Play Trailer (YouTube)
  - Play Link 1 (vidsrc.cc)
  - Play Link 2 (smashystream)

## 🎬 Streaming Sources

### Trailer
- **YouTube** - Official trailers

### Link 1
- **vidsrc.cc**
- Movies: `https://vidsrc.cc/v2/embed/movie/{ID}`
- TV Shows: `https://vidsrc.cc/v2/embed/tv/{ID}`

### Link 2
- **smashystream**
- All Content: `https://embed.smashystream.com/playere.php?tmdb={ID}`

## 🔍 Search

- Real-time search as you type
- Searches movies, TV shows, and people
- Autocomplete dropdown
- Click result to view details

## 📱 Responsive Design

### Desktop (1920px+)
- Full sidebar navigation
- Large hero sections
- Multi-column grids

### Tablet (768px - 1024px)
- Adjusted layouts
- Optimized spacing
- Touch-friendly

### Mobile (< 768px)
- Hamburger menu
- Collapsible sidebar
- Single column grids
- Optimized for touch

## 🎨 Styling Details

### Grayscale Effect
```css
filter: grayscale(100%);
```
- All posters start in grayscale
- Color appears on hover
- Creates cohesive black & white aesthetic

### Background Blur
```css
filter: grayscale(100%) blur(20px);
opacity: 0.2;
```
- Poster images as backgrounds
- Heavy blur for atmosphere
- Low opacity for readability

### Smooth Transitions
```css
transition: all 0.3s ease;
```
- Everything animated
- Smooth hover effects
- Elegant page transitions

## 🛠️ Customization

### Change Colors
Edit `style.css` `:root` variables:
```css
:root {
  --bg-primary: #000000;
  --text-primary: #ffffff;
  --accent: #ffffff;
}
```

### Adjust Blur
Change background blur amount:
```css
.hero-background {
  filter: grayscale(100%) blur(20px); /* Adjust blur value */
}
```

### Modify Grayscale
Toggle grayscale effect:
```css
.card-poster {
  filter: grayscale(100%); /* Remove for color */
}
```

## 🌐 API

Uses **The Movie Database (TMDB) API**:
- Real-time data
- High-quality images
- Accurate information
- Free to use

## 🎯 Browser Support

- ✅ Chrome/Edge (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Mobile browsers

## 📝 Notes

### Image Quality
- Posters: 500px width
- Backdrops: 780px - Original
- Profiles: 200px width

### Performance
- Lazy loading images
- Optimized API calls
- Smooth scrolling
- Efficient rendering

### Accessibility
- Semantic HTML
- ARIA labels
- Keyboard navigation
- Screen reader friendly

## 🎬 Comparison with Original

### Original THE-ULTIMATE
- Colorful design
- Green/blue accents
- Standard layout

### Nexify Watch
- Black & white aesthetic
- Grayscale posters
- Cinematic backgrounds
- Modern minimalist UI
- Separated files (HTML, CSS, JS)

## 🚀 Future Enhancements

Possible additions:
- [ ] User accounts
- [ ] Watchlist
- [ ] Watch history
- [ ] Favorites
- [ ] Ratings
- [ ] Reviews
- [ ] Recommendations
- [ ] Dark/Light mode toggle
- [ ] More streaming sources


## 💡 Tips

1. **Use Local Server** - Better performance and no CORS issues
2. **Try Both Links** - If one doesn't work, try the other
3. **Hover for Color** - Posters reveal color on hover
4. **Explore Categories** - Each section has multiple filters
5. **Search Everything** - Search works for movies, TV, and people

## 🎉 Enjoy!

Experience movies and TV shows in a stunning black & white interface with cinematic poster backgrounds! 🍿

---

**Nexify Watch** - Where Cinema Meets Modern Design
