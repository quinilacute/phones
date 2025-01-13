# Project ReadMe

## Overview
This project implements a responsive webpage with modern design principles, focusing on accessibility, aesthetics, and performance. It uses HTML, CSS, and custom styles to ensure a seamless experience across devices.

## Features
1. **Global Styles**
   - Custom CSS variables for consistency.
   - Responsive layout adapting to mobile, tablet, and desktop screens.

2. **Header**
   - Includes a logo, navigation menu, and a hamburger menu for mobile view.
   - Navigation adapts based on screen size.

3. **Hero Section**
   - Centralized heading with a call-to-action button.
   - Background image with full viewport coverage.

4. **Content Sections**
   - Multiple sections styled for readability and visual hierarchy.
   - Flexbox and grid layouts for dynamic alignment and spacing.

5. **Footer**
   - Contains a logo, social icons, and copyright information.
   - Responsive design with flexbox adjustments for various screen sizes.

6. **Responsive Design**
   - Media queries to handle breakpoints for mobile, tablet, and desktop views.

7. **Custom Fonts**
   - Integration of the 'HolbertonIcon' custom font.

8. **Interactive Elements**
   - Hover effects for links and buttons.
   - Highlighted focus styles for form inputs.

## Code Highlights
- **CSS Variables**: Define reusable properties such as colors, dimensions, and opacity.
  ```css
  :root {
      --max-content-width: 1000px;
      --link-hover-color: #FF6565;
      --button-hover-opacity: 0.9;
  }
  ```

- **Custom Font**:
  ```css
  @font-face {
      font-family: 'HolbertonIcon';
      src: url('/fonts/holberton_school-icon.woff2') format('woff2'),
           url('/fonts/holberton_school-icon.woff') format('woff'),
           url('/fonts/holberton_school-icon.ttf') format('truetype');
      font-weight: normal;
      font-style: normal;
  }
  ```

- **Responsive Media Queries**:
  ```css
  @media (max-width: 768px) {
      header .nav-menu {
          display: none;
          flex-direction: column;
          position: absolute;
          top: 60px;
          left: 0;
          width: 70%;
          background: none;
          padding: 20px;
          z-index: 1000;
      }
  }
  ```

## File Structure
```
project-root/
├── index.html
├── styles/
│   ├── global.css
│   ├── header.css
│   ├── hero.css
│   ├── footer.css
├── images/
│   ├── headphones_hero_1.jpg
│   ├── headphones_hero_2.jpg
├── fonts/
│   ├── holberton_school-icon.woff2
│   ├── holberton_school-icon.woff
│   ├── holberton_school-icon.ttf
└── README.md
```

## How to Run
1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```

2. Open the `index.html` file in your browser to view the project.

## Contributions
Feel free to submit issues or pull requests for improvements.
## Contributions
Feel free to submit issues or pull requests for improvements.

## License
This project is licensed under the MIT License.

