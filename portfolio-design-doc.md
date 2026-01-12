# Portfolio Website Design Document
## Darshit Shah | Personal Portfolio

---

## 📋 Project Overview

**Project:** Personal portfolio website for Darshit Shah  
**Hosting:** GitHub Pages (`darshit.github.io` or similar)  
**Type:** Single-page, responsive, minimal design  
**Tech Stack:** HTML, CSS, JavaScript (vanilla - no frameworks)  
**Target Audience:** Recruiters, hiring managers, and industry professionals in finance, tech, and quantitative fields

---

## 👤 About the Owner

- **Name:** Darshit Shah
- **Current Status:** Undergraduate student at Georgia Institute of Technology
- **Major:** B.S. Mathematics (Concentration: Probability & Statistics)
- **Minor:** Computer Science
- **Expected Graduation:** December 2027
- **GPA:** 4.00
- **Career Interest:** Mathematical applications in the finance industry (quantitative finance, data science, fintech)

---

## 🎨 Design Requirements

### Aesthetic
- **Style:** Minimal, clean, professional
- **Color Scheme:** Suggest a sophisticated, muted palette:
  - Primary: Dark navy (#1a1a2e) or charcoal (#2d2d2d)
  - Accent: Subtle gold (#c9a227) or teal (#4ecdc4) for finance/math vibe
  - Background: Off-white (#fafafa) or very light gray (#f5f5f5)
  - Text: Dark gray (#333333)
- **Typography:** Clean sans-serif fonts (Inter, Roboto, or system fonts)
- **Layout:** Single scrolling page with smooth scroll navigation
- **Animations:** Subtle and purposeful (fade-ins, smooth scrolls) - nothing flashy

### Responsive Design
- Must work seamlessly on:
  - Desktop (1200px+)
  - Tablet (768px - 1199px)
  - Mobile (320px - 767px)

---

## 📑 Site Structure & Sections

### 1. Navigation Bar (Fixed/Sticky)
- Logo/Name on left: "Darshit Shah"
- Nav links on right: About | Skills | Experience | Projects | Education | Contact
- Hamburger menu on mobile
- Smooth scroll to sections on click

### 2. Hero Section
- Large greeting: "Hi, I'm Darshit Shah"
- Tagline/subtitle: "Mathematics Student at Georgia Tech | Aspiring Quantitative Analyst"
- Brief one-liner about passion for mathematical applications in finance
- Call-to-action buttons:
  - "View Resume" (opens PDF in new tab)
  - "Get in Touch" (scrolls to contact)
- Social icons: LinkedIn, GitHub, Email

### 3. About Me Section
- Short professional bio (3-4 sentences)
- Highlight:
  - Georgia Tech Mathematics major with CS minor
  - Probability & Statistics concentration
  - Interest in quantitative finance and mathematical modeling
  - 3x President's List recipient with 4.0 GPA

### 4. Skills Section
Display in clean card or tag format:

**Languages:**
- JavaScript, Python, C++, SQL, Java, HTML/CSS

**Frameworks & Libraries:**
- React, Node.js, Express, Flask, FastAPI, Tailwind CSS, Socket.IO

**Tools & Databases:**
- MongoDB, PostgreSQL, Firebase, Supabase, Docker, Git

**Cloud & Deployment:**
- AWS, Azure, Google Cloud, Vercel

**Core Competencies:**
- Data Structures & Algorithms
- Applied Probability & Statistics
- Linear Algebra
- Discrete Mathematics

### 5. Experience Section
Display in timeline or card format (most recent first):

**Machine Learning Intern | IDC Technologies**  
*May 2025 – August 2025*
- Engineered PostgreSQL schema, reduced query latency by 30%
- Developed Python pipelines and predictive ML model, improving technician utilization by 22%
- Built synthetic data generator, accelerating development by 40%

**STEM Tutor | Georgia State University**  
*August 2025 – December 2025*
- Tutored 50+ students in math (College Algebra to Linear Algebra) and CS
- Facilitated exam review sessions online and in-person
- Focused on conceptual understanding and algorithmic reasoning

**Student Assistant | Georgia State University**  
*September 2024 – May 2025*
- Managed 50+ daily inquiries, reduced appointment conflicts by 30%
- Coordinated 10+ research events, increased interdepartmental collaboration by 35%

### 6. Projects Section
Display as cards with brief descriptions:

**Motion | HackGT XI (Georgia Tech Hackathon)**  
*September 2025*
- AI-powered app automating syllabus parsing and academic calendar generation
- Built with Django, JavaScript, Google Gemini API
- Features: Assignment tracking, PDF storage, FullCalendar integration

*(Note: Section should be expandable for future projects)*

### 7. Education Section
**Georgia Institute of Technology**
- B.S. Mathematics, Minor in Computer Science
- Concentration: Probability & Statistics
- Expected Graduation: December 2027
- GPA: 4.00
- Awards: 3x President's List

**Relevant Coursework:**
- Data Structures and Algorithms
- Systems Level Programming
- Discrete Mathematics
- Linear Algebra
- Applied Probability

**Extracurriculars:**
- CodePath Interview Prep Bootcamp (Feb–May 2025)
- Panther Immersion Program, Robinson College of Business (Apr–Nov 2025)

### 8. Contact Section
- Heading: "Let's Connect" or "Get in Touch"
- Email: darshit@gatech.edu
- Phone: 405-210-7701 (optional - consider privacy)
- LinkedIn: linkedin.com/in/darshit
- GitHub: github.com/darshit
- Optional: Simple contact form (can use Formspree for free)

### 9. Footer
- Copyright: "© 2025 Darshit Shah. All rights reserved."
- Quick social links
- "Built with ❤️" (optional)

---

## 🔧 Technical Implementation Guide

### File Structure
```
darshit.github.io/
├── index.html
├── css/
│   └── styles.css
├── js/
│   └── main.js
├── assets/
│   ├── images/
│   │   └── profile.jpg (optional)
│   └── resume/
│       └── Shah_Darshit_Resume.pdf
├── README.md
└── CNAME (if using custom domain later)
```

### Key Features to Implement

1. **Smooth Scrolling**
   - CSS `scroll-behavior: smooth;`
   - JavaScript for navigation clicks

2. **Responsive Navigation**
   - Flexbox/Grid layout
   - Mobile hamburger menu with JavaScript toggle

3. **Scroll Animations**
   - Intersection Observer API for fade-in effects
   - Keep subtle and professional

4. **Active Navigation Highlighting**
   - Highlight current section in nav as user scrolls

5. **Dark/Light Mode Toggle (Optional)**
   - CSS custom properties for theming
   - localStorage to remember preference

6. **Accessibility**
   - Semantic HTML5 elements
   - ARIA labels where needed
   - Keyboard navigation support
   - Sufficient color contrast

### Performance Considerations
- Optimize images (WebP format if possible)
- Minimize CSS/JS
- Use system fonts or limit web font weights
- Lazy load images below the fold

---

## 🚀 Deployment Instructions (GitHub Pages)

### Step 1: Create Repository
- Repository name MUST be: `darshit.github.io` (replace with actual GitHub username)
- Set repository to public

### Step 2: Push Code
```bash
git init
git add .
git commit -m "Initial portfolio website"
git branch -M main
git remote add origin https://github.com/darshit/darshit.github.io.git
git push -u origin main
```

### Step 3: Enable GitHub Pages
- Go to repository Settings → Pages
- Source: Deploy from branch
- Branch: main, folder: / (root)
- Save and wait for deployment

### Step 4: Access Site
- Site will be live at: `https://darshit.github.io`

---

## 📝 Content to Prepare

The owner should provide:
1. ✅ Resume PDF (provided)
2. ⬜ Professional headshot/photo (optional but recommended)
3. ⬜ Short bio paragraph (2-3 sentences about yourself)
4. ⬜ Any specific wording preferences

---

## 🎯 Development Phases

### Phase 1: Setup & Structure
- [ ] Create GitHub repository
- [ ] Set up file structure
- [ ] Create HTML skeleton with all sections
- [ ] Add semantic HTML content

### Phase 2: Styling
- [ ] Implement CSS reset/normalize
- [ ] Create CSS custom properties (variables)
- [ ] Style each section
- [ ] Implement responsive breakpoints
- [ ] Add hover states and transitions

### Phase 3: Interactivity
- [ ] Smooth scroll navigation
- [ ] Mobile menu toggle
- [ ] Scroll animations
- [ ] Active nav highlighting

### Phase 4: Polish & Deploy
- [ ] Cross-browser testing
- [ ] Mobile testing
- [ ] Performance optimization
- [ ] Deploy to GitHub Pages
- [ ] Test live site

---

## 💡 Future Enhancements (Post-MVP)

- Add more projects as they're completed
- Blog section (if desired later)
- Custom domain
- Analytics integration
- Contact form with backend

---

## 📚 Resources for Claude Code

When implementing, reference:
- MDN Web Docs for HTML/CSS/JS
- Google Fonts for typography
- Heroicons or Feather Icons for icons
- CSS-Tricks for flexbox/grid layouts

---

*This document serves as the complete specification for building Darshit Shah's portfolio website. Claude Code should follow these guidelines to create a professional, minimal, and effective portfolio site.*
