# Web-development-internship-task-4
# Responsive Web Design using CSS Media Queries

This project converts a static, desktop-only web page into a responsive layout that works well on mobile devices. It uses **CSS Media Queries** to adjust layout, navigation, and font sizes for different screen sizes.

## 📱 Objective
Make an existing webpage mobile-friendly using CSS techniques like:
- Media queries
- Flexbox
- Percentage widths and relative units
- Viewport meta tag

## 🛠 Technologies Used
- HTML5
- CSS3
- Media Queries
- Chrome DevTools

## 💡 What Was Done
1. Created a basic webpage layout using HTML and CSS.
2. Applied a flex layout for desktop view.
3. Added a media query for devices with width ≤ 768px:
   - Navigation menu becomes vertical
   - Columns stack vertically
   - Font sizes and padding adjusted
4. Tested using Chrome DevTools' device toolbar.

## 🔍 Key Concepts
- `@media` rules for responsive behavior
- Mobile-first vs Desktop-first design
- Viewport meta tag to scale content properly
- Flexbox for layout adaptation
- Relative units (`%`, `rem`, `vw`) for flexible scaling

## 🖥 Example Media Query
```css
@media (max-width: 768px) {
  .nav-menu {
    flex-direction: column;
  }
  .container {
    flex-direction: column;
  }
}
