# College Extracurricular Website

A comprehensive web platform showcasing college extracurricular activities, competitions, clubs, and events across various departments and disciplines.

## 🌟 Features

### CampusLife Portal (index.html)
- **Home**: Hero section with engaging statistics and call-to-action buttons
- **Events & Calendar**: Upcoming events with dates, times, and registration options
- **Student Clubs**: Filterable club directory across technical, cultural, sports, and literary categories
- **Sports & Fitness**: Tournament schedules, team rankings, and facility information
- **Achievements**: Showcase of student accomplishments and recognition
- **Workshops**: Skill development sessions with expert instructors
- **Responsive Design**: Mobile-friendly interface with smooth animations

### Engineering Competition Portal (main.html)
- **Competition Hub**: Featured technical competitions with prize information
- **Department Activities**: Department-specific highlights and participation stats
- **Quick Stats Dashboard**: Real-time statistics on competitions and participants
- **Upcoming Deadlines**: Important registration and submission dates
- **Interactive UI**: Modern design with gradient backgrounds and hover effects

## 🛠️ Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Styling**: Custom CSS with modern design patterns
- **Icons**: Font Awesome 6.0.0
- **Fonts**: Google Fonts (Poppins)
- **Backend**: Node.js with Express.js (ready for implementation)
- **Responsive**: Mobile-first design with CSS Grid and Flexbox

## 📁 Project Structure

```
college-extracurricular-website/
├── index.html          # Main CampusLife portal
├── main.html           # Engineering Competition portal
├── styles.css          # Comprehensive styling for index.html
├── README.md          # Project documentation
```

## 🚀 Getting Started

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/college-extracurricular-website.git
   cd college-extracurricular-website
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server** (when backend is implemented)
   ```bash
   npm start
   ```

4. **Open in browser**
   Navigate to `http://localhost:3000` to view the website

### Quick Start (Static Files)
Simply open `index.html` or `main.html` in any modern web browser to view the static version.

## 🎨 Design Features

### Visual Design
- **Color Scheme**: Professional purple/blue gradients with accent colors
- **Typography**: Poppins font family for modern, readable text
- **Animations**: Smooth hover effects and fade-in animations
- **Icons**: Font Awesome icons for intuitive navigation

### Responsive Layout
- **Mobile**: Single-column layout with hamburger menu
- **Tablet**: Optimized grid layouts
- **Desktop**: Full-featured multi-column designs

### Interactive Elements
- Smooth scrolling navigation
- Modal dialogs for registrations
- Filterable content sections
- Animated statistics and cards

## 📊 Sections Overview

### CampusLife (index.html)
- **Hero**: Welcome section with key statistics (50+ clubs, 200+ events, 5000+ students)
- **Events**: Calendar view with upcoming cultural, tech, and holiday events
- **Clubs**: Categorized clubs with member counts and achievement badges
- **Sports**: Tournament schedules, team rankings, and facility information
- **Achievements**: Student and team accomplishments with spotlight features
- **Workshops**: Professional development opportunities

### Competition Portal (main.html)
- **Featured Competitions**: Highlighted technical challenges with prize information
- **Department Activities**: Engineering department-specific content
- **Quick Stats**: Live statistics on participation and events
- **Sidebar**: Important deadlines and quick links

## 🔧 Customization

### Adding New Clubs
Edit the clubs section in `index.html`:
```html
<div class="club-card" data-category="technical">
    <div class="club-icon"><i class="fas fa-icon-name"></i></div>
    <h3>Club Name</h3>
    <p>Club description</p>
    <div class="club-stats">
        <span><i class="fas fa-users"></i> X Members</span>
        <span><i class="fas fa-trophy"></i> Y Wins</span>
    </div>
    <button class="btn-join">Join Club</button>
</div>
```

### Modifying Events
Update events in the events grid:
```html
<div class="event-card">
    <div class="event-date">
        <span class="day">DD</span>
        <span class="month">MMM</span>
    </div>
    <div class="event-info">
        <h3>Event Name</h3>
        <p><i class="fas fa-clock"></i> Time</p>
        <p><i class="fas fa-map-marker-alt"></i> Location</p>
        <button class="btn-register">Register Now</button>
    </div>
</div>
```

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📈 Performance

- Optimized images with responsive sizing
- Minimal external dependencies
- Efficient CSS with modern layout techniques
- Fast loading times with optimized assets

## 🤝 Contributing

We welcome contributions to enhance the college extracurricular platform!

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

### Development Guidelines
- Follow existing code style and structure
- Test responsiveness across devices
- Ensure accessibility standards
- Update documentation for new features

## 🐛 Known Issues

- Backend server.js file not yet implemented (Express.js setup required)
- Some placeholder content needs real data integration
- Mobile menu functionality requires JavaScript enhancement

## 📝 Todo List

- [ ] Implement Express.js backend server
- [ ] Add database integration for dynamic content
- [ ] Create user authentication system
- [ ] Build admin dashboard for content management
- [ ] Add real-time notifications
- [ ] Implement search functionality
- [ ] Add social media integration
- [ ] Create mobile app version

## 📞 Support

For support or questions about this project:
- Email: your-email@college.edu
- Issue Tracker: GitHub Issues page

## 📄 License

This project is licensed under the ISC License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Font Awesome for icons
- Google Fonts for typography
- Unsplash for placeholder images
- Modern CSS techniques and design patterns

---

**Note**: This is a frontend demonstration project. Backend functionality and database integration are planned for future development.
