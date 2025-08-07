# Najmun Jahan - Portfolio Website

A modern, responsive portfolio website built with ASP.NET Core MVC showcasing the skills, projects, and experience of Najmun Jahan, an ASP.NET Developer.

## 🚀 Features

- **Modern Design**: Clean, professional design with smooth animations
- **Responsive Layout**: Fully responsive design that works on all devices
- **Interactive Elements**: Smooth scrolling, hover effects, and animations
- **Professional Sections**: 
  - Hero section with call-to-action buttons
  - About section with personal information
  - Skills section with categorized technical skills
  - Experience timeline
  - Project showcase with technology tags
  - Education history
  - Contact information with social links

## 🛠️ Technologies Used

- **Backend**: ASP.NET Core 8.0, C#
- **Frontend**: HTML5, CSS3, JavaScript
- **Framework**: Bootstrap 5.3.0
- **Icons**: Font Awesome 6.4.0
- **Animations**: AOS (Animate On Scroll)
- **Fonts**: Google Fonts (Poppins)

## 📋 Prerequisites

- .NET 8.0 SDK or later
- Visual Studio 2022 or VS Code
- Web browser

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone <repository-url>
cd Portfolio-Website
```

### 2. Run the Application
```bash
dotnet run
```

### 3. Open in Browser
Navigate to `https://localhost:7000` or `http://localhost:5000`

## 📁 Project Structure

```
Portfolio-Website/
├── Controllers/
│   └── HomeController.cs
├── Models/
│   └── ErrorViewModel.cs
├── Views/
│   ├── Home/
│   │   └── Index.cshtml
│   └── Shared/
│       └── _Layout.cshtml
├── wwwroot/
│   ├── css/
│   │   └── site.css
│   └── js/
│       └── site.js
├── Program.cs
└── Portfolio-Website.csproj
```

## 🎨 Customization

### Personal Information
Update the following files with your information:
- `Views/Home/Index.cshtml` - Main content
- `Views/Shared/_Layout.cshtml` - Meta tags and title
- `wwwroot/css/site.css` - Colors and styling

### Profile Image
Replace the placeholder image in the About section with your actual profile photo:
```html
<img src="path/to/your/image.jpg" alt="Your Name" class="profile-image">
```

### Project Images
Replace placeholder images in the Projects section with actual project screenshots:
```html
<img src="path/to/project-image.jpg" alt="Project Name" class="project-image">
```

## 🌟 Key Features

### Navigation
- Fixed navigation bar with smooth scrolling
- Active section highlighting
- Mobile-responsive hamburger menu

### Animations
- AOS (Animate On Scroll) for section reveals
- Typing effect for hero title
- Hover effects on cards and buttons
- Smooth transitions throughout

### Responsive Design
- Mobile-first approach
- Flexible grid layouts
- Optimized for all screen sizes

### Performance
- Optimized CSS and JavaScript
- Minimal external dependencies
- Fast loading times

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 🔧 Configuration

### Development
The application runs in development mode by default. Configuration can be found in:
- `appsettings.json` - General settings
- `appsettings.Development.json` - Development-specific settings

### Production
For production deployment:
1. Set environment to Production
2. Configure HTTPS
3. Optimize static files
4. Set up proper hosting

## 📄 License

This project is created for Najmun Jahan's personal portfolio. Feel free to use as a template for your own portfolio.

## 👤 Contact

**Najmun Jahan**
- Email: najmunjahan35@gmail.com
- Phone: +880 1718 624 335
- GitHub: [najmunjahan](https://github.com/najmunjahan)
- LinkedIn: [najmun-jahan](https://www.linkedin.com/in/najmun-jahan/)
- Location: Dhaka, Bangladesh

## 🙏 Acknowledgments

- Bootstrap for the responsive framework
- Font Awesome for icons
- AOS library for scroll animations
- Google Fonts for typography

---

**Built with ❤️ using ASP.NET Core**
