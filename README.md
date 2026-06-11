# React Developer Portfolio

A modern, responsive developer portfolio website built with React and Tailwind CSS. Showcase your projects, skills, services, and testimonials with an elegant dark theme and smooth animations.

![Language: JavaScript](https://img.shields.io/badge/Language-JavaScript%2097.3%25-blue)
![Styling: CSS](https://img.shields.io/badge/Styling-CSS%202.3%25-blue)
![Markup: HTML](https://img.shields.io/badge/Markup-HTML%200.4%25-blue)
![Status: Active](https://img.shields.io/badge/Status-Active-brightgreen)

## 🌟 Features

- **Responsive Design**: Fully responsive layout that looks great on all devices (mobile, tablet, desktop)
- **Dark Theme**: Modern dark mode interface with accent colors for better visual appeal
- **Smooth Animations**: Fade-in animations and hover effects for enhanced user experience
- **Project Showcase**: Beautiful carousel to display your projects with filtering by category
- **Skills Display**: Organized skill categories with proficiency levels and progress indicators
- **Services Section**: Highlight the services you offer with interactive cards
- **Testimonials**: Showcase client testimonials with ratings
- **Contact Section**: Easy-to-use contact form for potential clients
- **Performance Optimized**: Built with Vite for fast build times and optimal performance

## 📋 Project Structure

```
react-dev-portfolio/
├── src/
│   ├── components/
│   │   ├── layout/
│   │   │   ├── Navbar.jsx
│   │   │   └── Footer.jsx
│   │   ├── sections/
│   │   │   ├── Hero.jsx
│   │   │   ├── About.jsx
│   │   │   ├── Skills.jsx
│   │   │   ├── Projects.jsx
│   │   │   ├── Services.jsx
│   │   │   ├── Testimonials.jsx
│   │   │   └── Contact.jsx
│   │   └── common/
│   │       ├── FadeIn.jsx
│   │       └── ProjectCard.jsx
│   ├── data/
│   │   ├── projects.js
│   │   ├── services.js
│   │   ├── testimonials.js
│   │   └── skills.js
│   ├── styles/
│   │   └── globals.css
│   ├── App.jsx
│   └── main.jsx
├── public/
│   └── images/
│       ├── projects/
│       └── testimonials/
├── index.html
├── package.json
├── vite.config.js
├── tailwind.config.js
└── README.md
```

## 🚀 Quick Start

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/it22318466/react-dev-portfolio.git
cd react-dev-portfolio
```

2. **Install dependencies**
```bash
npm install
```

3. **Start the development server**
```bash
npm run dev
```

The portfolio will be available at `http://localhost:5173`

## 🛠️ Available Scripts

- **`npm run dev`** - Start development server with hot reload
- **`npm run build`** - Build for production
- **`npm run lint`** - Run ESLint to check code quality
- **`npm run preview`** - Preview production build locally

## 🎨 Technologies Used

### Frontend Framework
- **React** (19.2.4) - Modern JavaScript library for building UIs
- **Vite** (8.0.1) - Next-generation build tool for faster development

### Styling
- **Tailwind CSS** (4.2.2) - Utility-first CSS framework
- **Tailwind CSS Vite Plugin** (4.2.2) - Vite integration for Tailwind
- **CSS** - Custom styling (2.3%)

### UI Components & Icons
- **Lucide React** (1.7.0) - Beautiful, consistent icon library
- **React Icons** (5.6.0) - Popular icon sets for React

### Development Tools
- **ESLint** (9.39.4) - Code quality and style enforcement
- **@vitejs/plugin-react** (6.0.1) - Vite plugin for React
- **TypeScript** - Type safety for React components

## 📝 Customization

### Update Your Information

1. **Hero Section** - Edit your name and headline in `src/components/sections/Hero.jsx`

2. **About Section** - Update your bio and information in `src/components/sections/About.jsx`

3. **Projects** - Modify `src/data/projects.js`:
```javascript
export const projects = [
  {
    id: 1,
    title: "Your Project Name",
    description: "Project description",
    image: "/images/projects/project1.png",
    category: "Category",
    technologies: ["React", "Node.js"],
    metrics: "Achievement metric",
    demoUrl: "https://your-project-demo.com",
    githubUrl: "https://github.com/your-repo"
  },
  // Add more projects...
];
```

4. **Skills** - Update `src/data/skills.js` with your technical skills and proficiency levels

5. **Services** - Customize `src/data/services.js` to highlight your services

6. **Testimonials** - Add client testimonials in `src/data/testimonials.js`

### Styling Customization

Edit `tailwind.config.js` to customize:
- Color scheme and primary color
- Typography
- Spacing and sizing
- Custom animations

## 📦 Dependencies

### Main Dependencies
```json
{
  "@tailwindcss/vite": "^4.2.2",
  "lucide-react": "^1.7.0",
  "react": "^19.2.4",
  "react-dom": "^19.2.4",
  "react-icons": "^5.6.0",
  "tailwindcss": "^4.2.2"
}
```

### Dev Dependencies
```json
{
  "@eslint/js": "^9.39.4",
  "@types/react": "^19.2.14",
  "@types/react-dom": "^19.2.3",
  "@vitejs/plugin-react": "^6.0.1",
  "eslint": "^9.39.4",
  "eslint-plugin-react-hooks": "^7.0.1",
  "eslint-plugin-react-refresh": "^0.5.2",
  "globals": "^17.4.0",
  "vite": "^8.0.1"
}
```

## 🚀 Deployment

### Deploy to Vercel

1. Push your code to GitHub
2. Connect your repository to Vercel
3. Vercel will automatically detect Vite and deploy your project

### Deploy to Netlify

1. Build your project: `npm run build`
2. Connect your GitHub repository to Netlify
3. Set build command: `npm run build`
4. Set publish directory: `dist`

### Deploy to GitHub Pages

Update `vite.config.js`:
```javascript
export default {
  base: '/react-dev-portfolio/',
}
```

Then deploy:
```bash
npm run build
npm install gh-pages --save-dev
npx gh-pages -d dist
```

## 📱 Responsive Breakpoints

- **Mobile**: < 640px
- **Tablet**: 640px - 1024px
- **Desktop**: > 1024px

## 🎯 Key Sections

### Hero Section
Eye-catching introduction with your name, title, and call-to-action buttons

### About Section
Tell your story and highlight your professional background

### Skills Section
Display your technical skills organized by category with proficiency levels

### Projects Section
Showcase your best work with filtering capabilities by project category

### Services Section
Highlight the services you provide with descriptive cards

### Testimonials Section
Display client feedback and success stories with ratings

### Contact Section
Allow visitors to get in touch with you

### Footer
Professional footer with social links and copyright information

## ✨ Performance Features

- **Code Splitting**: Optimized chunk loading with Vite
- **Lazy Loading**: Images and components load as needed
- **CSS Optimization**: Tailwind purges unused styles in production
- **Fast Refresh**: Instant updates during development

## 🐛 Troubleshooting

### Development Server Won't Start
```bash
# Clear node_modules and reinstall
rm -rf node_modules package-lock.json
npm install
npm run dev
```

### Build Fails
```bash
# Check for linting errors
npm run lint

# Fix linting issues
npx eslint . --fix
```

### Styles Not Loading
- Ensure Tailwind CSS is properly configured
- Check that `globals.css` is imported in `main.jsx`
- Rebuild the project: `npm run build`

## 📄 License

This project is available for personal and commercial use. Feel free to use it as a template for your own portfolio.

## 🤝 Contributing

This is a personal portfolio project. Feel free to fork and customize it for your needs!

## 📞 Support

For questions or issues, please open an issue on GitHub or contact the repository owner.

## 🔗 Live Demo

View the live portfolio: [https://timetoprogram.com/projects](https://timetoprogram.com/projects)

---

**Made with ❤️ using React & Tailwind CSS**
