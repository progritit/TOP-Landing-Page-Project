# TOP-Landing-Page-Project
# Aurelium Landing Page

A premium luxury interior design landing page built with pure HTML and CSS.

This project was developed as part of **The Odin Project** curriculum and later transformed into a high-end portfolio piece focused on luxury branding, clean layouts, and responsive frontend design principles.

---

## Preview

The page showcases:
- A modern hero section
- Elegant navigation layout
- Luxury interior imagery
- Information cards with custom images
- Testimonial section
- Call-to-action banner
- Footer

---

## Built With

- HTML5
- CSS3
- Flexbox
- Google Fonts (Roboto)

---

## Features

### Layout & UI
- Semantic HTML structure
- Responsive flexbox layouts
- Consistent spacing system
- Reusable CSS utility structure
- CSS variables for color management

### Design
- Luxury-inspired visual identity
- Neutral warm color palette
- Rounded image cards
- Modern typography hierarchy
- Elegant CTA section

### Image Handling
- Responsive image containers
- `object-fit: cover` image scaling
- Rounded image clipping with `overflow: hidden`

---

## Project Structure

```plaintext
TOP-Landing-Page-Project/
│
├── index.html
├── styles.css
├── README.md
│
└── Images/
    ├── residential-interior.png
    ├── boutique-hospitality.png
    ├── material-curation.png
    └── architectural-harmony.png
```

---

## Design Concept

This version of the project was redesigned around a fictional luxury interior design studio named **Aurelium**.

The objective was to create a visually refined landing page capable of:
- Demonstrating frontend fundamentals
- Showcasing visual hierarchy
- Simulating a real-world client project
- Elevating portfolio presentation quality

---

## Key Learning Outcomes

This project helped reinforce:
- Semantic HTML structure
- CSS organization and maintainability
- Flexbox layouts
- Image scaling techniques
- Typography systems
- UI spacing and alignment
- Portfolio-oriented visual design
- Debugging image overflow and layout issues

---

## Challenges Solved

### Hero Image Overflow

A large hero image initially broke the layout and covered the navigation.

### Solution

- Constrained the image container dimensions
- Applied:

```css
object-fit: cover;
overflow: hidden;
```

---

### Card Images Overflowing Containers

Images originally rendered outside the card boxes.

### Solution

- Nested `<img>` tags inside `.card-box`
- Applied:

```css
.card-box img {
    width: 100%;
    height: 100%;
    object-fit: cover;
}
```

---

### GitHub Pages Deployment Issues

The project initially failed to render images correctly after deployment.

### Solution

- Replaced absolute local file paths with relative paths
- Renamed files for cleaner portability
- Corrected project asset structure for GitHub Pages compatibility

Example:

```html
<!-- Incorrect -->
<img src="/home/user/project/images/example.png">

<!-- Correct -->
<img src="Images/example.png">
```

---

## AI-Assisted Workflow

This project was developed using a modern AI-assisted workflow.

### Tools Used

#### ChatGPT
Assisted with:
- Code structure guidance
- CSS debugging
- Layout troubleshooting
- Frontend best practices
- UI/UX improvement suggestions
- README drafting
- Portfolio content ideation

#### Google Gemini
Assisted with:
- Luxury interior image generation
- Visual inspiration
- Creative direction exploration

### Development Approach

AI tools were used as collaborative assistants throughout the project, while all implementation decisions, integration, customization, debugging, and final design direction were handled manually.

This workflow reflects modern frontend development practices where AI accelerates iteration, problem-solving, and creative exploration.

---

## Future Improvements

Potential future enhancements:
- Mobile responsiveness
- CSS animations and hover effects
- Dark/light theme toggle
- Fully responsive navigation menu
- Accessibility improvements
- Performance optimization
- Deployment with GitHub Pages custom domain

---

## Author

**Clebson Costa**

Frontend development student focused on:
- Clean UI implementation
- Responsive layouts
- Modern frontend practices
- Portfolio-quality projects

---

## Acknowledgements

- The Odin Project
- Google Fonts
- ChatGPT for development support and debugging assistance
- Google Gemini for luxury visual generation and creative inspiration

---

## License

This project is open-source and available for educational and portfolio purposes.
