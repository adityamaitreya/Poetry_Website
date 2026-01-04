# Poetry By Shivanshu 📖✨

A beautiful and interactive poetry website showcasing the works of poet Shivanshu Tripathi. This project features Hindi poetry across various themes including devotional (भक्ति), love (प्रेम), emotional (भावनात्मक), and separation (विरह).

## 🌟 Features

- **Responsive Design**: Fully responsive layout that works seamlessly on desktop, tablet, and mobile devices
- **Category Filtering**: Browse poems by different categories (भक्ति, प्रेम, भावनात्मक, विरह)
- **Quote of the Day**: Inspirational poetry quote displayed on the home page
- **Smooth Navigation**: Easy-to-use navigation with smooth scrolling between sections
- **Poet Profile**: Dedicated section to learn about the poet Shivanshu Tripathi
- **Clean UI**: Modern and elegant design focused on readability and user experience

## 🚀 Live Demo

[View Live Website](#) *(Add your deployment link here)*

## 📂 Project Structure

```
Poetry_Website/
│
├── index.html          # Main HTML file
├── styles.css          # Styling and layout
├── scripts.js          # JavaScript functionality
├── poet.png            # Poet's profile image
└── README.md           # Project documentation
```

## 🛠️ Technologies Used

- **HTML5**: Semantic markup for content structure
- **CSS3**: Styling with modern CSS features
- **JavaScript**: Interactive filtering and navigation
- **Pure Vanilla JS**: No frameworks or libraries required

## 📋 Prerequisites

No special prerequisites needed! This is a static website that runs in any modern web browser.

## 🔧 Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/poetry-website.git
   ```

2. **Navigate to the project directory**
   ```bash
   cd poetry-website
   ```

3. **Open in browser**
   - Simply open `index.html` in your web browser
   - Or use a local server (recommended):
     ```bash
     # Using Python
     python -m http.server 8000
     
     # Using Node.js
     npx serve
     ```

4. **Visit** `http://localhost:8000` in your browser

## 💻 Usage

### Navigation
- Click on navigation links (Home, Poems, Poet) to jump to different sections
- Use category buttons to filter poems by theme

### Adding New Poems
To add a new poem, edit `index.html` and add a new article element:

```html
<article data-category="YourCategory">
  <h3>Title - Your Poem Title <br>
      Description - Your poem description
  </h3>
  <p><strong>Category:</strong> YourCategory | <strong>By:</strong> Poet Name</p>
  <p>Your poem content here...</p>
</article>
```

## 📱 Responsive Design

The website is fully responsive and optimized for:
- 📱 Mobile devices (< 768px)
- 📱 Tablets (768px - 1024px)
- 💻 Desktop screens (> 1024px)

## 🎨 Customization

### Colors
Edit the CSS variables in `styles.css` to customize the color scheme:
```css
:root {
  --primary-color: your-color;
  --secondary-color: your-color;
  --background-color: your-color;
}
```

### Fonts
Change fonts by modifying the `font-family` properties in `styles.css`

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/YourFeature`)
3. Make your changes
4. Commit your changes (`git commit -m 'Add some feature'`)
5. Push to the branch (`git push origin feature/YourFeature`)
6. Open a Pull Request

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Authors

- **Aditya Maitreya** - *Developer* - [GitHub Profile](#)
- **Shivanshu Tripathi** - *Poet* - Featured poetry content

## 🙏 Acknowledgments

- Thanks to Shivanshu Tripathi for sharing beautiful poetry
- Inspired by the rich tradition of Hindi literature
- Built with passion for poetry and web development

## 📧 Contact

For questions or suggestions, please reach out:
- Email: adityamaitreya10@gmail.com
- GitHub: [@yourusername](https://github.com/adityamaitreya)

---

⭐ If you like this project, please give it a star on GitHub!

**Made with ❤️ by Aditya Maitreya**
