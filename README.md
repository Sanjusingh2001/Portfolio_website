# 🚀 Sanjana Singh - Portfolio Website

A modern, responsive portfolio website showcasing Sanjana Singh's skills, experience, projects, and professional journey in software development.

![Portfolio Preview](portfolio/assets/img/portfolio_sample.png)

## ✨ Features

- **Responsive Design** - Works perfectly on all devices
- **Modern UI/UX** - Clean, professional Materialize CSS design
- **Interactive Sections** - Smooth scrolling and animations
- **Contact Form** - Working EmailJS integration for direct communication
- **Professional Layout** - Well-organized sections for easy navigation
- **SEO Optimized** - Meta tags and Google Analytics integration

## 🛠️ Technologies Used

### Frontend
- **HTML5** - Semantic markup and structure
- **CSS3** - Modern styling and responsive design
- **JavaScript** - Interactive functionality and form handling
- **Materialize CSS** - UI framework for modern design
- **Font Awesome** - Professional icons

### Backend & Services
- **EmailJS** - Contact form email service
- **Google Analytics** - Website analytics and tracking
- **Google Tag Manager** - Marketing and analytics management

### Libraries & Dependencies
- **jQuery** - DOM manipulation and event handling
- **Typed.js** - Animated typing effect for hero section
- **Materialize JS** - Component initialization and functionality

## 📱 Sections

### 1. **Hero Section** 🎯
- Professional introduction with animated typing effect
- Social media links (LinkedIn, GitHub)
- Call-to-action buttons

### 2. **About Section** 👩‍💻
- Professional summary and background
- Technical skills overview
- Career objectives

### 3. **Experience Section** 💼
- **Victora Lifts Private Limited** - Full Stack Developer (June 2024 - Present)
- **Dabotics India Pvt. Ltd** - Full Stack Developer Intern (Oct 2024 - Dec 2024)
- **Bharat Intern** - Web Developer Intern (June 2023 - Aug 2023)

### 4. **Projects Section** 🚀
- **Heart Stroke Prediction ML Model** - Machine Learning project
- **Food Delivery App** - React Native mobile application
- **Portfolio Website** - Responsive web development project

### 5. **Skills Section** 🎨
- **Languages**: Python, Java, JavaScript, C, C++, HTML/CSS, Bash
- **Databases**: MySQL, PostgreSQL, MongoDB
- **Libraries**: NumPy, Pandas, OpenCV, Scikit-learn, Matplotlib
- **Frameworks**: Django, Flask, React.js, Node.js, Bootstrap
- **Tools**: Git, Docker, AWS, GCP, Heroku, JIRA

### 6. **Education Section** 🎓
- **GLA University** - Master of Computer Applications (MCA) - 2022-2024
- **A.N College** - Bachelor of Science in Information Technology - 2018-2021
- **Mahila Mahavidhyalaya** - Intermediate - 2016-2018
- **Vivekanand Mission School** - High School - 2015-2016

### 7. **Contact Section** 📞
- Contact information (Phone, Email, GitHub, LinkedIn)
- Working contact form with EmailJS integration
- Success/Error modal notifications

## 🚀 Getting Started

### Prerequisites
- Modern web browser
- Local HTTP server (for development)

### Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/sanjana-portfolio.git
   cd sanjana-portfolio
   ```

2. **Navigate to portfolio directory**
   ```bash
   cd portfolio
   ```

3. **Start local server**
   ```bash
   # Using Python 3
   python3 -m http.server 8000
   
   # Using Python 2
   python -m SimpleHTTPServer 8000
   
   # Using Node.js
   npx http-server -p 8000
   ```

4. **Open in browser**
   ```
   http://localhost:8000
   ```

## 📸 Sample Images

### Profile Picture
![Profile Picture](portfolio/assets/img/snj.jpeg)

### Experience Logos
![Victora Lifts Logo](portfolio/assets/img/victoralogo.jpeg)
![Dabotics Logo](portfolio/assets/img/exp-meditab-logo-500x500.jpg)

### Project Images
![Heart Stroke Prediction](portfolio/assets/img/project-ai-1.jpg)
![Food Delivery App](portfolio/assets/img/food_delivery.jpeg)
![Portfolio Website](portfolio/assets/img/portfolio_sample.png)

### Skills & Technologies
![Python](portfolio/assets/img/python-logo-1-300x300.jpg)
![Django](portfolio/assets/img/django-logo.webp)
![React](portfolio/assets/img/javascript.png)
![Machine Learning](portfolio/assets/img/tensorflow-logo-1.png)

## 🔧 Configuration

### EmailJS Setup
The contact form uses EmailJS for sending emails. Update the following in `index.html`:

```javascript
// Service ID
emailjs.send("service_bughpzs", "template_2l7m82h", {
  // Template variables
  title: formData.subject,
  from_name: formData.name,
  from_email: formData.email,
  subject: formData.subject,
  message: formData.message,
  to_email: "sanjanasingh7631@gmail.com"
});
```

### Google Analytics
Update the tracking ID in `index.html`:
```javascript
gtag('config', 'UA-126939217-2');
```

### Google Tag Manager
Update the container ID:
```javascript
GTM-PGZH8HT
```

## 📱 Responsive Design

The portfolio is fully responsive and optimized for:
- **Desktop** (1200px+)
- **Tablet** (768px - 1199px)
- **Mobile** (320px - 767px)
- **Small Mobile** (< 320px)

## 🎨 Customization

### Colors
- **Primary**: Teal (#009688)
- **Secondary**: Teal Blue (#00bcd4)
- **Accent**: Brown (#795548)
- **Text**: Dark Gray (#263238)

### Fonts
- **Primary**: Materialize CSS default fonts
- **Icons**: Font Awesome 4.3.0

### Styling
- **CSS Framework**: Materialize CSS 0.95.3
- **Custom CSS**: Located in `assets/css/style.css`
- **Responsive**: Mobile-first approach

## 📁 Project Structure

```
sanjana_portfolio/
├── portfolio/
│   ├── assets/
│   │   ├── css/
│   │   │   └── style.css
│   │   ├── img/
│   │   │   ├── snj.jpeg (Profile Picture)
│   │   │   ├── victoralogo.jpeg (Company Logo)
│   │   │   ├── food_delivery.jpeg (Project Image)
│   │   │   ├── portfolio_sample.png (Portfolio Preview)
│   │   │   └── ... (Other Images)
│   │   ├── resume/
│   │   │   └── sanjana_S_resume.pdf
│   │   └── vendor/
│   │       └── typed.js/
│   ├── index.html
│   ├── LICENSE
│   └── robots.txt
├── README.md
└── .DS_Store
```

## 🌟 Key Features

### Interactive Elements
- **Smooth Scrolling** - Navigation between sections
- **Typing Animation** - Dynamic hero section text
- **Hover Effects** - Interactive buttons and cards
- **Modal Popups** - Contact form success/error notifications

### Performance
- **Optimized Images** - Compressed and web-optimized
- **Minified CSS/JS** - Faster loading times
- **Lazy Loading** - Efficient resource management
- **CDN Resources** - Fast external library loading

### Accessibility
- **Semantic HTML** - Proper document structure
- **ARIA Labels** - Screen reader support
- **Keyboard Navigation** - Full keyboard accessibility
- **Color Contrast** - WCAG compliant color schemes

## 📧 Contact Form

The contact form includes:
- **Real-time Validation** - Input field validation
- **EmailJS Integration** - Direct email sending
- **Success/Error Handling** - User feedback
- **Form Reset** - Automatic cleanup after submission

### Form Fields
- **Name** (Required, min 2 characters)
- **Email** (Required, valid email format)
- **Subject** (Required, min 5 characters)
- **Message** (Required, min 10 characters)

## 🔒 Security Features

- **Input Validation** - Client-side form validation
- **XSS Protection** - Sanitized user inputs
- **CSRF Protection** - Form submission security
- **Secure Headers** - HTTP security headers

## 📊 Analytics & Tracking

- **Google Analytics 4** - Website performance metrics
- **Google Tag Manager** - Marketing and analytics
- **Conversion Tracking** - Contact form submissions
- **User Behavior** - Page views and interactions

## 🚀 Deployment

### GitHub Pages
1. Push code to GitHub repository
2. Enable GitHub Pages in repository settings
3. Select source branch (usually `main` or `master`)
4. Access via `https://username.github.io/repository-name`

### Netlify
1. Connect GitHub repository to Netlify
2. Configure build settings
3. Deploy automatically on push
4. Custom domain configuration available

### Vercel
1. Import GitHub repository to Vercel
2. Automatic deployment on push
3. Preview deployments for pull requests
4. Global CDN and edge functions

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](portfolio/LICENSE) file for details.

## 👩‍💻 About the Developer

**Sanjana Singh** is a passionate software developer with expertise in:
- **Backend Development** - Python, Django, Flask
- **Frontend Development** - React.js, HTML5, CSS3, JavaScript
- **Machine Learning** - TensorFlow, PyTorch, Scikit-learn
- **Database Management** - MySQL, PostgreSQL, MongoDB
- **DevOps** - Git, Docker, AWS, GCP

## 📞 Contact Information

- **Phone**: +91-6205159505
- **Email**: sanjanasingh7631@gmail.com
- **LinkedIn**: [Sanjana Singh](https://www.linkedin.com/in/sanjanasinghrajput/)
- **GitHub**: [sanjusingh2001](https://github.com/sanjusingh2001/)
- **Location**: Noida, India

## 🙏 Acknowledgments

- **Materialize CSS** - UI framework and components
- **Font Awesome** - Professional icon library
- **EmailJS** - Contact form email service
- **Typed.js** - Typing animation library
- **Google Fonts** - Typography and fonts

---

**⭐ Star this repository if you find it helpful!**

**🔗 Live Demo**: [Portfolio Website](https://your-portfolio-url.com)

**📧 Questions?** Feel free to reach out via the contact form or email!