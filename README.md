# 🎵 Frontend Immersion - Spotify Homepage Clone

Welcome to the **Frontend Immersion by Alura**! This project focuses on creating a responsive Spotify homepage clone. Below is an overview of what we accomplished during Days 1, 2, 3, and 4.

---

## Day 1: Overview 📅

### Topics Covered 📚

- **HTML, CSS, and JavaScript Review**

  - Recapped the core differences between these technologies:
    - **HTML**: 🏰️ Structure and content.
    - **CSS**: 🎨 Styling and layout.
    - **JavaScript**: ⚙️ Interactivity (not used today).

- **Building the Sidebar Navigation**

  - Created a functional sidebar with HTML and CSS.
  - Added navigation items like 🏠 Home, 🔍 Search, and 📚 Your Library.

- **Introducing CSS Styling**

  - Applied properties like `background-color`, `padding`, `border-radius`, and more.
  - Styled the sidebar for a clean and modern look.

- **DevTools Tricks**
  - 🛠️ Explored browser developer tools to tweak and debug styles in real-time.

---

## Day 2: Overview 📅

### Topics Covered 📚

- **Finalizing the Sidebar Menu**

  - Finalized the sidebar by adding 🌍 a "Language" section and a 🍪 "Cookies" button for settings.

- **Adding a Footer**

  - Designed and positioned a fixed footer containing a call-to-action for Spotify Premium.
  - Styled the footer with gradients and responsive design principles.

- **CSS Flexbox Fundamentals**

  - Learned how to align and position elements using properties like `justify-content`, `align-items`, and `gap`.
  - Utilized Flexbox for both horizontal and vertical alignment of components.

- **Positioning in CSS**
  - Explored different positioning techniques (`relative`, `absolute`, `fixed`) to ensure layout consistency.

---

## Day 3: Overview 📅

### Topics Covered 📚

- **Better Project Structure** 📂

  - Organized files into a `src` folder for better project management.
  - Created new CSS files for specific components.

- **Code Refactoring** 🛠️

  - Improved HTML structure and CSS organization for readability and maintainability.

- **Flexbox Layout Implementation** 🏰️

  - Applied Flexbox principles to structure the layout efficiently.

- **Responsive Design Concepts** 📱

  - Explored techniques to make the UI responsive on different screen sizes.

- **Creating the Top Menu** 🎧
  - Implemented a search bar.
  - Designed and styled the header navigation with login and signup buttons.

---

## Day 4: Overview 📅

### Topics Covered 📚

- **Creating the Homepage Cards** 🌟

  - Designed and structured the cards for displaying artists and playlists.
  - Used CSS for styling to match the Spotify design.

- **CSS Grid Layout** 🛠️

  - Implemented CSS Grid for a more flexible and dynamic layout.
  - Learned how to control column and row sizes efficiently.

- **Making the Project Responsive** 📱

  - Created the `media-queries.css` file to handle different screen sizes.
  - Applied breakpoints to adjust layouts for mobile and tablet views.

- **Introducing JavaScript** 📝

  - Started adding interactivity to the project using JavaScript.
  - Manipulated elements dynamically through the DOM.

- **Using Promises in JavaScript** 🏆

  - Learned about asynchronous JavaScript.
  - Utilized `fetch` and Promises to request and display artist data dynamically.

---

## Tools and Resources Used 🔧

- **[Font Awesome](https://fontawesome.com/)** for icons.
- **Google Chrome DevTools** to test and refine styles.
- **Reset CSS** to standardize browser styles.
- **Flexbox & CSS Grid** for responsive and dynamic layouts.

---

## Current Features 🌟

- 🎨 Functional sidebar navigation with:
  - 🏠 "Home" and 🔍 "Search" links.
  - 📚 A "Your Library" button with a clean dropdown-style interaction.
  - ➕ Playlist creation placeholder with explanatory text.
  - 🌍 Language and cookie settings sections.
- 🎵 A fixed footer with a prominent "Test Spotify Premium for Free" message.
- 📱 Responsive layout with properly aligned components using Flexbox and Grid.
- 🔍 Search bar for quick access to content.
- 📝 Dynamic artist and playlist cards powered by JavaScript and Promises.

---

## Codebase Overview 📂

- **HTML**
  - Structured the sidebar, footer, and library sections.
  - Created a responsive top menu.
  - Added artist and playlist cards dynamically.
- **CSS**
  - Utilized Flexbox and CSS Grid for layout.
  - Styled buttons, icons, and text with consistent spacing and colors.
  - Improved code organization with separate stylesheets.
- **JavaScript**
  - Implemented interactivity using DOM manipulation.
  - Integrated Promises and `fetch` for dynamic data handling.

---

## How to Run Locally 🖥️

1. Clone this repository:

   ```bash
   git clone https://github.com/ricardotemporal/frontend-immersion.git
   ```

2. Open the project folder:

   ```bash
   cd frontend-immersion
   ```

3. Install dependencies and run the local API server:

   ```bash
   npm i json-server -g
   json-server --watch api-artists/artists.json --port 3000
   ```

4. Open `index.html` in your favorite browser or use Live Server in VS Code.
