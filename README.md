# Aurelium Landing Page

[Live Demo](https://progritit.github.io/TOP-Landing-Page-Project/)

<img width="1919" height="934" alt="Aurelium Landing Page preview" src="https://github.com/user-attachments/assets/4be397f2-ffa2-4e5c-a7d6-49b7de018db7" />

A premium luxury interior design landing page built with HTML and CSS.

This project was developed as part of **The Odin Project** curriculum and later refined into a portfolio-oriented landing page focused on visual hierarchy, clean layout structure, luxury branding, and responsive front-end presentation.

---

## Preview

The page showcases:

* A modern hero section
* Elegant navigation layout
* Luxury interior imagery
* Information cards with custom images
* Testimonial section
* Call-to-action banner
* Footer

---

## Built With

* HTML5
* CSS3
* Flexbox
* CSS variables
* Google Fonts
* Git and GitHub
* GitHub Pages

---

## Features

### Layout & UI

* Semantic HTML structure
* Responsive layout foundations
* Flexbox-based sections
* Consistent spacing system
* Reusable CSS structure
* Clean visual hierarchy

### Design

* Fictional luxury interior design brand
* Neutral warm color palette
* Modern typography hierarchy
* Rounded image cards
* Elegant call-to-action section
* Portfolio-focused visual presentation

### Image Handling

* Responsive image containers
* `object-fit: cover` image scaling
* Rounded image clipping with `overflow: hidden`
* Relative asset paths for GitHub Pages compatibility

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

The objective was to transform a foundational landing page exercise into a more refined portfolio piece capable of:

* Demonstrating HTML and CSS fundamentals
* Applying visual hierarchy and spacing principles
* Simulating a real-world client landing page
* Presenting a stronger brand direction
* Improving overall portfolio quality

---

## Key Learning Outcomes

This project helped reinforce:

* Semantic HTML structure
* CSS organization and maintainability
* Flexbox layout techniques
* Image scaling and cropping
* Typography hierarchy
* UI spacing and alignment
* Debugging layout overflow issues
* Managing relative paths for deployment
* Building a more polished visual identity from a basic project brief

---

## Challenges Solved

### Hero Image Overflow

A large hero image initially broke the layout and covered the navigation.

### Solution

* Constrained the image container dimensions
* Applied image scaling and overflow control

```css
object-fit: cover;
overflow: hidden;
```

---

### Card Images Overflowing Containers

Images originally rendered outside the card boxes.

### Solution

* Nested `<img>` tags inside `.card-box`
* Applied consistent sizing and cropping rules

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

* Replaced absolute local file paths with relative paths
* Renamed files for cleaner portability
* Corrected the project asset structure for GitHub Pages compatibility

Example:

```html
<!-- Incorrect -->
<img src="/home/user/project/images/example.png">

<!-- Correct -->
<img src="Images/example.png">
```

---

## Development Workflow

This project was built through a hands-on learning process using HTML and CSS.

AI tools were used as learning and productivity assistants for brainstorming, visual direction, debugging support, and documentation refinement. The final code was reviewed, adapted, tested, and integrated manually, with a focus on understanding the structure, styling decisions, and layout behavior behind the implementation.

This workflow reflects a modern approach to learning web development: using available tools strategically while staying responsible for the final result.

---

## Future Improvements

Potential future enhancements:

* Improve mobile responsiveness
* Add CSS animations and hover effects
* Add a fully responsive navigation menu
* Improve accessibility checks
* Optimize image performance
* Add a custom favicon
* Refine the design system with more reusable classes

---

## Author

**Clebson Costa**

Front-end development student focused on:

* Clean UI implementation
* Responsive layouts
* HTML and CSS fundamentals
* Modern front-end practices
* Portfolio-quality projects

---

## Acknowledgements

* The Odin Project
* Google Fonts
* ChatGPT for learning support, debugging assistance, and documentation refinement
* Google Gemini for visual direction exploration

---

## License

This project is open-source and available for educational and portfolio purposes.
