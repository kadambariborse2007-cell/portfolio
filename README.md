# Kadambari Borse - Professional Portfolio

A production-quality single-page portfolio website for Kadambari Borse, a B.Sc. Computer Science student focused on Web Development and Cybersecurity.

## Features

- **Secure Tech Design**: Modern minimalist design with deep navy background and teal accents
- **Single-Page Scroll**: Smooth navigation between all sections
- **Fully Responsive**: Optimized for 375px, 768px, 1024px, and 1440px+ breakpoints
- **Accessibility**: Semantic HTML, keyboard navigation, focus states, reduced motion support
- **Data-Driven Architecture**: Content separated into structured data files
- **Component-Based**: Reusable React components with proper separation of concerns
- **Verified Content**: All information sourced from CV and verified GitHub repositories

## Design System

- **Primary Background**: #0F1419 (Deep Navy)
- **Light Surface**: #F5F3F0 (Soft Cream)
- **Primary Text**: #F5F3F0
- **Accent**: #00D4AA (Teal/Cyan)
- **Typography**: Inter (with system fallbacks)
- **Spacing**: Consistent design tokens
- **Border Radius**: 8-20px range

## Sections

1. **Navbar** - Sticky navigation with smooth scrolling
2. **Hero** - Introduction with profile placeholder and floating tags
3. **Current Status** - Recent experience highlight
4. **Selected Work** - Verified projects from GitHub
5. **Experience** - Detailed internship experience
6. **Technical Skills** - Categorized skill presentation
7. **Security Knowledge** - Dedicated cybersecurity section
8. **Certifications** - Verified certifications
9. **GitHub Build Log** - Technical GitHub integration
10. **About** - Personal introduction
11. **Currently Exploring** - Learning interests
12. **Contact** - Direct contact links
13. **Footer** - Brand and credits

## Tech Stack

- **React 18** - UI framework
- **Vite 5** - Build tool and dev server
- **Framer Motion** - Animation library
- **CSS** - Custom styling with design tokens

## Local Development

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## Project Structure

```
src/
├── components/          # Reusable React components
│   ├── Navbar.jsx
│   ├── Hero.jsx
│   ├── CurrentStatus.jsx
│   ├── SelectedWork.jsx
│   ├── ProjectCard.jsx
│   ├── Experience.jsx
│   ├── Skills.jsx
│   ├── SecurityKnowledge.jsx
│   ├── Certifications.jsx
│   ├── GithubBuildLog.jsx
│   ├── About.jsx
│   ├── CurrentlyExploring.jsx
│   ├── Contact.jsx
│   └── Footer.jsx
├── data/               # Structured content data
│   ├── projects.js
│   ├── experience.js
│   ├── skills.js
│   └── certifications.js
├── styles/             # Design system
│   ├── designTokens.css
│   └── base.css
├── assets/             # Static assets
├── App.jsx             # Main app component
└── main.jsx            # Entry point
```

## Content Accuracy

All content is verified and sourced from:
- Personal CV information
- GitHub repository inspection
- Actual project evidence

No fabricated information, metrics, or achievements are included.

## Deployment to Vercel

1. Push this repository to GitHub
2. Go to [Vercel](https://vercel.com)
3. Click "Add New Project"
4. Import your GitHub repository
5. Vercel will auto-detect the Vite configuration
6. Click "Deploy"

## Customization

### Profile Photo
Replace the profile placeholder in Hero.jsx by adding your actual photo to `public/images/profile/` and updating the component.

### Project Images
Add actual project screenshots to `public/images/projects/` and update the image paths in `src/data/projects.js`.

### Content Updates
Modify the data files in `src/data/` to update content without touching component logic.

## Performance

- Optimized for fast loading
- Minimal JavaScript overhead
- CSS-based animations where possible
- Lazy-loaded images
- No unnecessary dependencies

## Accessibility

- Semantic HTML structure
- Proper heading hierarchy
- Keyboard navigation support
- Visible focus states
- Screen reader friendly
- Reduced motion support
- Sufficient color contrast
- Touch-friendly targets

## License

This portfolio is built for personal professional use.

---

Built with React + Vite + Passion ☕