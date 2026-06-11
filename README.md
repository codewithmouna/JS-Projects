# JavaScript Mini-Projects Collection

A repository of interactive web applications built using HTML5, CSS3, and Vanilla JavaScript. These projects demonstrate core web development concepts such as DOM manipulation, API integration, and local data persistence.

## Table of Contents

- [Projects Overview](#projects-overview)
  - [Features Comparison](#features-comparison)
  - [1. Movie Search App](#1-movie-search-app-moviesearchinghtml)
  - [2. Advanced Age Calculator](#2-advanced-age-calculator-agecalculatorhtml)
  - [3. Advanced BMI Calculator](#3-advanced-bmi-calculator-bmicalculatorhtml)
  - [4. Advanced Tip Calculator](#4-advanced-tip-calculator-tipcalculatorhtml)
  - [5. Digital Clock](#5-digital-clock-digitalclockhtml)
  - [6. Random Color Changer](#6-random-color-changer-colorchangerhtml)
  - [7. Counter App](#7-counter-app-counterapphtml)
- [How to Use](#how-to-use)
- [Technologies Used](#technologies-used)

## Projects Overview

### Features Comparison

| Project Name     | API Integration | Local Storage | User Input | Advanced Math | Theme Toggle | Data Export |
| :--------------- | :-------------: | :-----------: | :--------: | :-----------: | :----------: | :---------: |
| Movie Search App |       ✅        |      ✅       |     ✅     |      ❌       |      ❌      |     ✅      |
| Age Calculator   |       ❌        |      ✅       |     ✅     |      ✅       |      ✅      |     ❌      |
| BMI Calculator   |       ❌        |      ❌       |     ✅     |      ✅       |      ❌      |     ❌      |
| Tip Calculator   |       ❌        |      ❌       |     ✅     |      ✅       |      ✅      |     ❌      |
| Digital Clock    |       ❌        |      ❌       |     ❌     |      ❌       |      ❌      |     ❌      |
| Color Changer    |       ❌        |      ❌       |     ❌     |      ❌       |      ❌      |     ❌      |
| Counter App      |       ❌        |      ❌       |     ❌     |      ❌       |      ❌      |     ❌      |

### 1. Movie Search App (`MovieSearching.html`)

A feature-rich movie discovery application integrated with the OMDb API.

- **Key Features:** Real-time search with debouncing, type filtering (Movies/Series), Watchlist management, and detailed movie information via modals.
- **Data Handling:** Supports exporting and importing your watchlist as JSON files.

### 2. Advanced Age Calculator (`Agecalculator.html`)

A precise tool to calculate age and astronomical details based on a date of birth.

- **Key Features:** Breakdown of age in years/months/days, Western and Chinese Zodiac identification, and a "Life Progress" visualization.
- **UI:** Includes a dark mode toggle and persistent data using LocalStorage.

### 3. Advanced BMI Calculator (`BMIcalculator.html`)

A health utility to calculate Body Mass Index (BMI).

- **Key Features:** Provides BMI value, health category classification (Underweight to Obese), and calculates the ideal weight range based on height.

### 4. Advanced Tip Calculator (`tipCalculator.html`)

A utility for splitting bills and calculating gratuity.

- **Key Features:** Handles custom tip percentages, GST/Tax calculations, and calculates the final amount to be paid per person.

### 5. Digital Clock (`DigitalClock.html`)

A minimalist real-time clock and date display.

- **Key Features:** Dynamic updates every second, featuring a clean dark-themed UI and localized date formatting.

### 6. Random Color Changer (`ColorChanger.html`)

An interactive tool to explore random color palettes.

- **Key Features:** Generates random hex codes on click and applies them to the page background.

<!-- Add your Color Changer screenshot/GIF here -->

![Color Changer Preview](assets/previews/color-changer.gif)

### 7. Counter App (`CounterApp.html`)

A fundamental project demonstrating basic state management.

- **Key Features:** Increment, decrement, and reset functionality with live UI updates.

## How to Use

<!-- Add your Counter App screenshot/GIF here -->

![Counter App Preview](assets/previews/counter-app.png)

1. **Prerequisites:** To use the Movie Search App, ensure you have an active OMDb API key (configured in the script).
2. **Running Locally:** Simply open any of the `.html` files in a modern web browser.

## Technologies Used

- **Frontend:** HTML5, CSS3 (Flexbox & CSS Grid)
- **Scripting:** Vanilla JavaScript (ES6+)
- **APIs:** Fetch API (OMDb)
- **Storage:** Browser LocalStorage API

---

_This collection was built as part of a JavaScript learning journey._
