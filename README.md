# Zoya Overseas LLC - Corporate Website

A clean, minimalist, and responsive corporate website built for **Zoya Overseas LLC**, a B2B wholesale trading company.

## Features
- **Modern Minimalist Design**: White and light-grey theme with deep purple accents.
- **Fully Responsive**: Adapts seamlessly to mobile, tablet, and desktop screens.
- **Interactive UI**: Scroll-reveal animations, staggered grid entrances, and elegant hover effects.
- **Admin Dashboard**: Simulates backend form processing by storing contact inquiries locally in the browser's `localStorage` for easy viewing in a dedicated dashboard.
- **Pure Front-End Architecture**: Zero dependencies. Built purely with HTML5, CSS3, and Vanilla JavaScript.

## File Structure
```
zoya Plastic/
├── index.html          # Homepage
├── products.html       # Products catalog & logistics
├── team.html           # Leadership team & philosophy
├── contact.html        # Contact form & location map
├── admin.html          # Local storage admin dashboard
├── css/
│   ├── common.css      # Shared variables, typography, navbar, footer
│   ├── index.css       
│   ├── products.css    
│   ├── team.css        
│   ├── contact.css     
│   └── admin.css       
└── js/
    ├── common.js       # Shared logic (mobile menu, scroll animations)
    ├── contact.js      # Form submission logic (saves to localStorage)
    └── admin.js        # Dashboard logic (reads from localStorage)
```

## Deployment
This project is explicitly configured to deploy seamlessly to **Netlify** from a **GitHub** repository.

1. **GitHub**: Push these files to a new GitHub repository.
2. **Netlify**: Log into Netlify, click "Add new site" -> "Import an existing project", and connect your GitHub repository.
3. The included `netlify.toml` automatically configures the correct publishing directory and sets up basic security headers. No build command is required.
