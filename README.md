# Testimonials Grid Section

A beautiful, responsive testimonials grid section showcasing customer reviews with a modern card-based layout. This project demonstrates advanced CSS Grid techniques and responsive design principles.

![Project Preview](./preview.jpg)

## 🚀 Live Demo

- [GitHub Repository](https://github.com/ziaur-rehman786/testimonials-grid-section)
- [Live Site](https://ziaur-rehman786.github.io/testimonials-grid-section/) (if deployed via GitHub Pages)

## 📋 Project Overview

This project is a responsive testimonials grid section that displays customer testimonials in an elegant card-based layout. The design features a dynamic grid system that adapts beautifully from mobile to desktop views, with cards of varying sizes to create visual interest.

## ✨ Features

- **Responsive Design**: Fully responsive layout that works seamlessly on mobile, tablet, and desktop devices
- **CSS Grid Layout**: Advanced grid system with cards spanning multiple columns and rows
- **Modern UI**: Clean, professional design with carefully chosen color schemes
- **Semantic HTML**: Well-structured, accessible markup
- **Optimized Performance**: Lightweight and fast-loading

## 🛠️ Technologies Used

- **HTML5**: Semantic markup for structure
- **CSS3**: 
  - CSS Grid for layout
  - Flexbox for component alignment
  - Custom properties for maintainable styling
  - Media queries for responsiveness
- **Google Fonts**: Barlow Semi Condensed font family

## 🎨 Design Details

### Color Palette
- Primary Purple: `hsl(263, 55%, 52%)`
- Dark Blue: `hsl(219, 29%, 14%)`
- Dark Gray: `hsl(217, 19%, 35%)`
- White: `hsl(0, 0%, 100%)`
- Light Gray Background: `hsl(210, 46%, 95%)`

### Typography
- Font Family: Barlow Semi Condensed
- Font Weights: 500, 600
- Base Font Size: 13px

## 📱 Responsive Breakpoints

- **Mobile**: Single column layout (default)
- **Desktop** (768px+): 4-column grid layout with cards spanning multiple columns/rows

## 🏗️ How I Built This

### 1. Planning & Structure
I started by analyzing the design requirements and planning the HTML structure. I created semantic HTML with proper article elements for each testimonial card, ensuring accessibility and SEO best practices.

### 2. HTML Structure
- Created a main container with a grid layout
- Structured each testimonial as an article with:
  - Header section (profile image, name, verification status)
  - Content section (quote and testimonial text)
  - Background pattern for the first card

### 3. CSS Grid Implementation
I implemented a mobile-first approach:
- **Mobile**: Single column stack layout
- **Desktop**: Complex 4-column grid where:
  - Card 1 (Daniel) spans 2 columns
  - Card 2 (Jonathan) takes 1 column
  - Card 3 (Jeanette) takes 1 column
  - Card 4 (Patrick) spans 2 columns
  - Card 5 (Kira) spans 2 rows vertically

### 4. Styling & Colors
- Applied different background colors to each card based on the design
- Used CSS custom properties for consistent color management
- Implemented proper contrast ratios for accessibility
- Added subtle shadows and border-radius for depth

### 5. Responsive Design
- Used media queries to switch from mobile to desktop layout
- Ensured all text remains readable at all screen sizes
- Maintained proper spacing and padding across breakpoints

## 💡 Key Learnings

1. **CSS Grid Mastery**: Learned to create complex layouts using grid-column and grid-row properties
2. **Responsive Design**: Implemented mobile-first responsive design principles
3. **Semantic HTML**: Used proper HTML5 semantic elements for better structure
4. **Color Theory**: Applied color psychology with different card backgrounds
5. **Typography**: Balanced font sizes and weights for optimal readability

## 📂 Project Structure

```
testimonials-grid-section/
├── index.html          # Main HTML file
├── style.css           # All styles and responsive design
├── images/             # Profile images and assets
│   ├── image-daniel.jpg
│   ├── image-jonathan.jpg
│   ├── image-jeanette.jpg
│   ├── image-patrick.jpg
│   ├── image-kira.jpg
│   └── bg-pattern-quotation.svg
├── design/             # Design reference files
└── README.md          # Project documentation
```

## 🚀 Getting Started

1. Clone the repository:
```bash
git clone https://github.com/ziaur-rehman786/testimonials-grid-section.git
```

2. Open `index.html` in your web browser

3. That's it! No build process or dependencies required.

## 📝 Future Enhancements

- [ ] Add dark mode toggle
- [ ] Implement smooth animations on card hover
- [ ] Add more testimonials with dynamic loading
- [ ] Create a testimonial submission form
- [ ] Add filtering/sorting functionality

## 👨‍💻 Author

**Zia Ur Rehman**

- GitHub: [@ziaur-rehman786](https://github.com/ziaur-rehman786)
- Project Link: [https://github.com/ziaur-rehman786/testimonials-grid-section](https://github.com/ziaur-rehman786/testimonials-grid-section)

## 📄 License

This project is open source and available for learning purposes.

---

**Note**: This project was created to practice and demonstrate CSS Grid, responsive design, and modern web development techniques.
