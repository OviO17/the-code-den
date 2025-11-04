#  The Code Den

Welcome to **The Code Den**, a cozy, developer-inspired café website created as part of **Code Institute’s Portfolio Project 1**.  
It combines two essentials for every coder — **coffee and community**. The site provides a warm and functional space where users can explore the café’s menu, learn about the story behind The Code Den, and easily get in touch.

---

##  Table of Contents

1. [Project Goals](#project-goals)
2. [User Experience (UX)](#user-experience-ux)
3. [Features](#features)
4. [Future Enhancements](#future-enhancements)
5. [Design Choices](#design-choices)
6. [Technologies Used](#technologies-used)
7. [Testing](#testing)
8. [Bugs and Fixes](#bugs-and-fixes)
9. [Deployment](#deployment)
10. [Credits](#credits)

---

##  Project Goals

- To design and build a fully responsive café website using **HTML and CSS** only.  
- To clearly communicate the site’s purpose (a café for coders).  
- To demonstrate clean, semantic HTML and maintainable CSS.  
- To create a consistent design with accessibility and usability in mind.

---

## User Experience (UX)

### Target Audience
- Developers and students looking for a comfortable place to work and relax.  
- Coffee lovers who appreciate a creative café theme.  
- Local visitors curious about the café menu or looking to get in touch.

### User Stories
- As a **visitor**, I want to understand what the café offers right away.  
- As a **customer**, I want to browse the menu easily.  
- As a **visitor**, I want to send a quick message via the contact form.  
- As a **mobile user**, I want simple navigation that works well on smaller screens.

---

##  Features

### **1. Home Page (index.html)**
- Hero section with tagline and call-to-action buttons.  
- Featured menu items with hover lift and links to the full menu.  
- Responsive header and burger menu on mobile.

### **2. About Page (about.html)**
- Clear explanation of the café’s background and vision.  
- Wide hero image banner for a welcoming introduction.

### **3. Menu Page (menu.html)**
- Categorized drinks and pastries with creative, coding-themed names.  
- Fully responsive layout for desktop, tablet, and mobile.

### **4. Contact Page (contact.html)**
- Simple contact form for visitors to reach out.  
- “Send Message” button changes to “Message Sent” when clicked.  
- Longer text area for ease of typing.  
- Footer remains fixed at bottom of the page.

### **5. Footer**
- Social media links (Instagram, Facebook, and X/Twitter) using Font Awesome icons.  
- Smooth hover scaling and consistent style across all pages.

---

##  Future Enhancements

- Add JavaScript form validation or animations.  
- Introduce an interactive gallery or live “Coffee of the Day.”  
- Add location map and opening hours.  
- Include a blog or events section.

---

##  Design Choices

- **Color palette:** Warm tones inspired by coffee (brown, cream, gold).  
- **Typography:** “Poppins” for modern readability.  
- **Imagery:** Optimized `.webp` hero and featured images.  
- **Layout:** Flexbox and grid for simple, clean responsiveness.  
- **Favicon:** Coffee cup icon for a polished look.

---

##  Technologies Used

- **HTML5** – Semantic and accessible structure.  
- **CSS3** – Responsive design with flexbox and media queries.  
- **Font Awesome** – For social icons.  
- **Git & GitHub** – Version control and hosting.  
- **GitHub Pages** – For live deployment.

---

## 🧪 Testing

### Manual Testing

| Feature | Expected Result | Outcome | Pass |
|----------|----------------|----------|------|
| Navigation links | Navigate correctly to each page | Works as expected | |
| Burger menu | Opens and closes on mobile | Works smoothly |  |
| Hero image | Resizes correctly on all devices | Fully responsive | |
| Contact button | Changes text when clicked | Works perfectly | |
| Footer | Consistent on every page | Displays correctly |  |

### Responsive Testing
- Tested on **Chrome DevTools** across iPhone, iPad, and desktop sizes. 
- Tested on  **W3c** html & css no errors
- Verified on **Chrome**, **Edge**, and **Firefox** browsers.  
- **Lighthouse:** Mid performance, Strong accessibility, and mobile usability.

---

##  Bugs and Fixes

| Issue | Cause | Fix |
|-------|--------|-----|
| Footer not at bottom | Missing layout height | Added min-height and spacing fixes |
| Burger menu missing on About | Incorrect header markup | Unified header across all pages |
| Featured section spacing | Too large image-to-text gap | Adjusted `gap` and margins |

 All known issues have been resolved and retested.

---

##  Deployment

This site was deployed via **GitHub Pages** directly from the repository.  

### Deployment Steps
1. Go to the [GitHub repository](https://github.com/OviO17/the-code-den).  
2. Click on **Settings** → **Pages**.  
3. Under *Branch*, select `main` and `/ (root)`.  
4. Click **Save**.  
5. Wait for GitHub Pages to publish the live link.

🔗 **Live Site:** [https://ovio17.github.io/the-code-den](https://ovio17.github.io/the-code-den)

### To Clone This Repository
You can clone the project locally using:
```bash
git clone https://github.com/OviO17/the-code-den.git
 Credits
Developer: Ovie Agbofodoh

Images: Pexels and Unsplash

Icons: Font Awesome

Inspiration: Code Institute’s Love Running and Coffee House projects.

