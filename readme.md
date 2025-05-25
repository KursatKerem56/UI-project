# Durumcu KAMİ Website Project

## Group Members

- Kürşat Kerem Çevlik - B231202053 - Author of the readme file / Bug fixer / Owner of the github repo
- Mustafa Yiğit Çoçgun - B231202012 - Maker of the slide / Bug fixer
- Alper Yıldırım - B231202001 - The Coder of the site / Presenter of the project
- İsmail Kerem Erkul - B231202068 - The Coder of the site

**GitHub Link:** https://github.com/KursatKerem56/UI-project

## Project Subject and Introduction

This project involves the design and implementation of a website for "Durumcu KAMİ", a Turkish durum restaurant. The website serves as a digital menu, showcasing various Turkish durums, drinks, and extras. The goal of the project is website design using Html, Css, Bootstrap and Javascript technologies. It is aimed that the website to be built is suitable for the user interface design and testing stages.

The website consists of four main pages in total:

- **Homepage:** The main landing page, providing an overview of the menu categories (Turkish Durums, Drinks, Extras) and general information about the restaurant.
- **Turkish Durums Page:** Displays a categorized list of various Turkish durums offered, including ingredients and prices.
- **Drinks Page:** Presents a categorized list of available beverages, with prices and descriptions.
- **Extras Page:** Features a categorized list of side dishes and desserts, with prices and descriptions.

## Preparation Process and Design Process Report

### Requirements Gathering

Our approach to gathering requirements involved a variety of techniques as outlined in the course:

- **Observing Your Users:** We considered potential user behaviors and expectations when Browse a food menu online.
- **Interviewing Your Users:** Informal discussions with individuals who frequently order food online helped us understand their preferences for menu layout and information presentation.
- **Questionnaires and Surveys:** While not formally conducted with a large sample, we mentally posed questions to ourselves and mock users to identify key features and usability aspects.

**User Identification and Characteristics:**
You have to find out who users are. The target users for the Durumcu KAMİ website are individuals looking for a Turkish durum restaurant, primarily focusing on customers who prefer to browse menus online or order ahead. You must describe the users and their characteristics. Users are expected to have basic computer literacy and internet access. No specific physical limitations were assumed for the general user base, but the design aims for accessibility.

**User Needs:**
You must find out user users needs. Users need to easily find information about:

- Types of durums, drinks, and extras available.
- Prices of each item.
- Ingredients or descriptions of menu items.
- Contact information (phone number).
- The ability to navigate between menu categories efficiently.

**User's Work (Goal, Task Analysis, Actions):**
You must describe users's works (goal, task analysis (using scenario and use cases) and actions).

- **Goal:** To view the menu and decide what to order.
- **Task Analysis (using scenarios and use cases):**
  - **Scenario 1: New Customer Browse**
    - User arrives at the homepage.
    - User clicks on "Turkish Durums" to see options.
    - User filters durums by "chicken" category.
    - User reads descriptions and prices.
    - User goes back to the homepage to check "Drinks".
  - **Scenario 2: Returning Customer**
    - User arrives at the homepage.
    - User directly clicks on "Drinks" knowing what they want.
    - User selects "Traditional" drinks.
- **Actions:** Clicking on menu categories, scrolling through lists, reading text.

**Requirements Gathering (Psychological Principles and Principles from Experience):**
Gather requirements (using four psychological principles and three principles from experience: Visibility, Affordance, and Feedback).

- **Visibility:** All main menu categories (Turkish Durums, Drinks, Extras) are clearly visible on the homepage. Prices and ingredients are clearly displayed on menu pages.
- **Affordance:** The "durum-box", "drinks-box", and "extras-box" on the homepage visually suggest they are clickable elements that lead to respective menu pages due to their box-like structure and hover effects. The "category" buttons on menu pages clearly afford clicking to filter items.
- **Feedback:** Hover effects on menu boxes and category buttons provide visual feedback to the user that they are interactive elements. When a category is selected, it becomes "active" with a different background color, indicating the current filter applied.

### Design Parts

**Conceptual Design - Content Diagram (Four Steps):**
While doing conceptual designing you must produce content diagram using four steps.

1.  **Identify Top-Level Categories:** Homepage, Turkish Durums, Drinks, Extras.
2.  **Break Down Categories:**
    - Homepage: Links to Turkish Durums, Drinks, Extras.
    - Turkish Durums: Chicken Durums, Meat Durums, Others.
    - Drinks: Traditional, Cold Drinks, Hot Drinks.
    - Extras: Sides, Desserts, Specials.
3.  **Define Content within Categories:**
    - Each menu category page lists items with Name, Price, and Ingredients/Description.
4.  **Establish Navigation Paths:**
    - Homepage leads to Turkish Durums, Drinks, Extras.
    - Turkish Durums, Drinks, and Extras pages all link back to the Homepage.
    - Category filters within each menu page.

**UI Description According to Design Principles:**
Describe your Ul according to design principles that are Simplicity, Structure, Consistency, and Tolerance.

- **Simplicity:** The design is clean and uncluttered. Each page focuses on a single primary function (homepage for navigation, menu pages for displaying items). The use of tables for menu items provides a straightforward structure.
- **Structure:** Content is logically grouped. The header, menu categories, and menu table maintain a consistent layout across the menu pages.
- **Consistency:** The overall visual theme (color palette, font styles, button appearances) is consistent across all pages. Navigation elements (back link, category buttons) behave similarly. The "Durumcu KAMİ © 2025" signature is consistently placed at the bottom of menu pages.
- **Tolerance:** The filter functionality for menu items allows users to easily correct their view if they select the wrong category. The back-to-homepage link is always available for easy navigation.

**Human-Action Cycle Critique:**
Use the human-action cycle to critique the your UI.

- **Goal:** The user's goal is to find a specific menu item or browse available options.
- **Execution:** The user forms an intention (e.g., "I want to see chicken durums"), then translates this into an action (clicks "Chicken Durums" category button). The system's interface (clickable buttons, tables) supports this action.
- **World:** The interface provides clear visual cues.
- **Perception:** The user perceives the change in the menu table, displaying only chicken durums. The active category button also changes.
- **Interpretation:** The user understands that the displayed items are indeed chicken durums.
- **Evaluation:** The user evaluates whether the displayed information meets their needs.

The UI supports the human-action cycle by providing clear goals, discoverable actions, informative feedback, and an easily interpretable display.

**Interaction Styles and Graphical Interface Controls:**
Determine your interaction styles. Explain why you will use the graphical interface controls you intend to use (such as menus, tabs, buttons, primary and secondary windows, etc.).
The primary interaction style is **direct manipulation** and **menu selection**.

- **Menus:** The homepage acts as a main menu, allowing users to select major categories (Turkish Durums, Drinks, Extras). The `menu-categories` on the sub-pages function as filter menus.
- **Buttons:** The category filters on the menu pages (`<div class="category">`) act as buttons to filter the displayed content.
- **Links:** Standard `<a>` tags are used for navigation between pages and for the "Homepage" back link.
- **Tables:** Menu items are presented in structured HTML tables, which is an effective way to display tabular data (item name, price, ingredients/description).

We use these controls because they are intuitive and widely understood by users, promoting ease of navigation and information retrieval. Bootstrap's responsive grid system ensures that the layout adapts well to different screen sizes.

## Technologies Used

- HTML5
- CSS3
- Bootstrap 5.3
- JavaScript

## Deficiencies

- No order placement or shopping cart functionality is implemented, as the project focuses on static menu display.
- Limited dynamic content beyond menu filtering.
- Image optimization could be further improved for faster loading on some devices.
- No search functionality for menu items.
