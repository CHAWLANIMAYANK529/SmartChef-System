
# SmartChef System

## Overview

**SmartChef System** is a Python-based interactive recipe recommendation application designed to assist users in discovering vegetarian recipes based on their preferred cuisine (Indian or Italian) and optionally a main ingredient. This project leverages structured data in Python dictionaries to provide recipe suggestions, including detailed ingredients and step-by-step cooking instructions.

---

## Features

- 🍲 Suggests vegetarian recipes from Indian and Italian cuisines.
- 🥕 Filters recipes by optional main ingredient.
- 📋 Provides detailed recipe instructions with exact ingredient quantities and units.
- 🧠 Built using simple Python data structures like dictionaries and lists.
- 👨‍🍳 Command-line based interaction.

---

## Tech Stack

- **Language**: Python 3.x
- **IDE Used**: Visual Studio Code
- **Design Tool**: Adobe Illustrator (for UI/UX elements)
- **Optional Future Tech**: React.js, Tailwind CSS, Vite (for front-end expansion)

---

## Project Structure

```
SmartChef/
│
├── data/
│   └── indian_vegetarian_recipes.py
│   └── italian_vegetarian_recipes.py
│
├── core/
│   └── suggestion.py
│   └── recipe_details.py
│
├── interface/
│   └── cli.py
│
├── README.md
└── requirements.txt
```

---

## How It Works

1. User selects a cuisine: Indian or Italian.
2. Optionally, user enters a main ingredient.
3. System filters and displays matching recipes.
4. User selects a recipe to view:
   - Ingredient list (with quantity and unit)
   - Step-by-step cooking instructions

---

## Installation

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/smartchef-system.git
   cd smartchef-system
   ```

2. (Optional) Create a virtual environment:
   ```bash
   python -m venv env
   source env/bin/activate   # On Windows: env\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

---

## Usage

Run the CLI interface:
```bash
python cli.py
```

Follow the prompts to:
- Select a cuisine
- Enter a main ingredient (optional)
- View suggested recipes
- Get recipe details

---

## Future Scope

- 🌍 Add more cuisines and dietary filters (e.g., vegan, gluten-free).
- 🧠 Integrate ML-based recommendation algorithms.
- 🖼️ Add GUI with React.js and Tailwind CSS.
- 📱 Mobile app integration for iOS and Android.
- 📊 Nutritional information, user ratings, and reviews.
- 🛒 Shopping list generation.

---

## Contributors

- **Mayank Chawlani** – Developer  
- **Mr. Sarvesh Kumar** – Project Guide

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
