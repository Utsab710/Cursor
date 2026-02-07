# Cursor Website Clone

A recreation of the Cursor.com homepage, built with HTML and CSS to practice frontend development and design implementation.

## 📌 Demo

- **Screenshots:**
  ![alt text](demo.png)
---

## 🎨 Sections Recreated

This project recreates the following sections from the Cursor homepage:

### 1. **Navigation Bar**
- Fixed position header with logo and navigation links
- Sign In and Download buttons
- Responsive navigation menu

### 2. **Hero Section (Intro)**
- Main headline with tagline
- Download CTA button
- Layered background images with overlay effect

### 3. **Trusted Organizations**
- Company logos grid display
- Features logos from Stripe, OpenAI, Linear, Datadog, Nvidia, Figma, Ramp, and Adobe

### 4. **Features Sections**
- **Feature 1**: Agent AI capabilities with left-aligned text and right-aligned image
- **Feature 2**: Autocomplete functionality with reversed layout (image left, text right)
- **Feature 3**: Ecosystem integration showcase

### 5. **Testimonials Grid**
- 6-card testimonial grid layout
- Quotes from industry leaders including:
  - Diana Hu (Y Combinator)
  - shadcn (Creator of shadcn/ui)
  - Andrej Karpathy (Eureka Labs)
  - Patrick Collison (Stripe)
  - ThePrimeagen
  - Greg Brockman (OpenAI)

### 6. **Stay on the Frontier Section**
- Three-column flex layout
- Cards showcasing AI models, codebase understanding, and enterprise solutions

### 7. **Changelog**
- Version updates display
- Release dates and feature descriptions
- CTA link to full changelog

### 8. **Join Us Section**
- Team recruitment area
- Company mission statement
- Team photo

### 9. **Recent Highlights**
- Blog post preview grid
- Product and research announcements
- Date stamps and categories

### 10. **Download CTA**
- Final call-to-action section
- Prominent download button

### 11. **Footer**
- Multi-column footer navigation
- Links organized by category (Product, Resources, Company, Legal, Connect)
- Copyright and SOC 2 certification notice

---

## 🎨 Colors Used

The design uses a dark, professional color scheme:

```css
:root {
  --accent-color: #1b1913;      /* Dark brown - secondary background */
  --main-color: #14120b;        /* Very dark brown - primary background */
  --cta-color: #f54e00;         /* Orange - call-to-action buttons and links */
  --cta-hover-color: #f54e00bf; /* Orange with transparency - hover states */
}
```

### Color Breakdown:
- **Primary Background**: `#14120b` (Very dark brown/black)
- **Secondary Background**: `#1b1913` (Dark brown - used for cards and sections)
- **Text Color**: `#ffffff` (White for primary text)
- **Secondary Text**: `#d8d5d5` (Light gray for footer and secondary content)
- **Muted Text**: `#9f9f9f` (Gray for dates and metadata)
- **Accent/CTA**: `#f54e00` (Bright orange for buttons and links)
- **Button Secondary**: `#edecec` (Off-white for download buttons)
- **Borders**: `#2b2923` (Dark gray for subtle borders)
- **Hover States**: `#282518`, `#746f6f` (Slight variations for interactive elements)

---

## 🔤 Fonts Used

The project uses custom web fonts that match Cursor's brand identity:

### Font Families:

1. **Cursor-bold** (`CursorGothic_Bold-s.p.95169710.woff2`)
   - Used for: Logo, main headings
   - Weight: Bold

2. **Cursor-Regular** (`CursorGothic_Regular-s.p.a361088d.woff2`)
   - Used for: Body text, paragraphs, most UI elements
   - Weight: Regular

3. **Cursor-Navbar** (`BerkeleyMono_Regular.p.e4888174.woff2`)
   - Used for: Navigation menu items
   - Style: Monospace regular

4. **Regular** (`regular.woff2`)
   - Used for: Additional text elements
   - Weight: Regular

### Font Implementation:

```css
@font-face {
  font-family: "Cursor-bold";
  src: url(fonts/CursorGothic_Bold-s.p.95169710.woff2);
}

@font-face {
  font-family: "Cursor-Navbar";
  src: url(fonts/BerkeleyMono_Regular.p.e4888174.woff2);
}

@font-face {
  font-family: "Cursor-Regular";
  src: url(fonts/CursorGothic_Regular-s.p.a361088d.woff2);
}
```

---

## 📁 Project Structure

```
cursor-clone/
├── index.html
├── style.css
├── fonts/
│   ├── CursorGothic_Bold-s.p.95169710.woff2
│   ├── CursorGothic_Regular-s.p.a361088d.woff2
│   ├── BerkeleyMono_Regular.p.e4888174.woff2
│   └── regular.woff2
├── Images/
│   ├── diana-hu-avatar.webp
│   ├── shadcn-avatar.webp
│   ├── andrej-karpathy-avatar.webp
│   ├── patrick-collison-avatar.webp
│   ├── theprimeagen-avatar.webp
│   ├── greg-brockman-avatar.webp
│   ├── AI-modal.png
│   ├── AI-modal2.png
│   ├── AI-modal3.png
│   └── homepage-team-photo.webp
├── public/
│   └── Icon.jpeg
├── image.png
├── image2.png
├── next.png
├── askCursor.png
└── README.md
```

---

## 🚀 Features Implemented

- ✅ Responsive grid layouts
- ✅ Fixed navigation header
- ✅ Custom typography with web fonts
- ✅ Hover effects and transitions
- ✅ Multi-column testimonial grid
- ✅ Flexbox and CSS Grid layouts
- ✅ Layered image positioning
- ✅ Dark theme design system
- ✅ Semantic HTML structure
- ✅ Organized footer navigation

---

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Custom styling with modern features
  - CSS Grid
  - Flexbox
  - Custom properties (CSS variables)
  - @font-face for web fonts

---

## 📝 Notes

- This is a static recreation for educational purposes
- External images are loaded from Cursor's CDN
- Font files should be placed in a `/fonts` directory
- The design is optimized for desktop viewing

---

## 📄 License

This project is created for educational purposes only. All rights to the original design belong to Cursor/Anysphere Inc.

---

## 🔗 Original Website

Visit the original website: [cursor.com](https://cursor.com)
