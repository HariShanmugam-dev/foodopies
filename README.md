# Foodopies

## 🚀 Project Overview

**Foodopies** is a dynamic recipe finder web application that helps users discover delicious recipes based on their ingredients and preferences. Built with ReactJS and integrated with a public recipe API, Foodopies delivers an interactive user experience with real-time data rendering.

Key Features:

- 🔍 **Search Recipes**: Enter keywords or ingredients to find matching recipes.
- 🌐 **API Integration**: Leverages the Spoonacular Recipe API for rich recipe data.
- ⚛️ **ReactJS Frontend**: Utilizes React components for dynamic UI updates.
- 📱 **Responsive Design**: Optimized for desktop and mobile viewing.
- 📝 **Recipe Details**: View ingredients, instructions, cooking time, and nutritional information.

---

## 📂 Project Structure

```bash
foodopies/
├── public/
│   ├── index.html         # Main HTML template
│   └── assets/            # Static assets (images, icons)
├── src/
│   ├── components/        # Reusable React components
│   ├── pages/             # Page-level components
│   ├── App.js             # Main application component
│   ├── index.js           # Entry point
│   └── styles/            # CSS files
├── .env                   # Environment variables (API keys)
├── package.json           # Project metadata and dependencies
└── README.md              # Project documentation
```

---

## 🛠️ Technologies & Tools

- **ReactJS**: UI library for building interactive user interfaces.
- **JavaScript (ES6+)**: Modern JS features for cleaner code.
- **Spoonacular API**: Provides recipe search, details, and nutrition data.
- **CSS3**: Styling and responsive layouts.
- **Axios**: Promise-based HTTP client for API requests.
- **Git & GitHub**: Version control and collaboration.

---

## 🔧 Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/HariShanmugam-dev/foodopies.git
   cd foodopies
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Create a `.env` file**
   ```env
   REACT_APP_SPOONACULAR_API_KEY=your_api_key_here
   ```
   - Sign up at [Spoonacular](https://spoonacular.com/food-api) to get your API key.

4. **Run the development server**
   ```bash
   npm start
   ```
   - Navigate to `http://localhost:3000` in your browser.

---

## 💡 Usage

- **Search**: Use the search bar to input ingredients or recipe names.
- **Browse Results**: View a list of matching recipes with thumbnails and brief info.
- **View Details**: Click on a recipe to see full details including ingredients, instructions, and nutritional facts.

---

## 🚀 Future Enhancements

- Add user authentication and the ability to save favorite recipes.
- Implement pagination or infinite scroll for large result sets.
- Enhance UI with animations and theming options.
- Add dietary filters (vegan, gluten-free, etc.) for more targeted searches.

---

## 🤝 Contributing

Contributions are welcome! Please follow these steps:
1. Fork the repository
2. Create a new branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Open a Pull Request

---

*Developed by Hari Hara Sudhan Shanmugam*

