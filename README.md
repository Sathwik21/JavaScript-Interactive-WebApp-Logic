# 🚀 JavaScript Interactive Web App (MVC-Based Structure)

A hands-on web application built using **HTML, CSS, and JavaScript** that demonstrates **event-driven programming, user input handling, DOM manipulation, and logic-based UI updates**, organized using a simple **MVC (Model-View-Controller)** approach.

---

## 🛠️ Tech Stack

- HTML5  
- CSS3  
- JavaScript  

---

## 💡 Skills Demonstrated

- DOM Manipulation  
- Event Handling  
- JavaScript Functions and Logic  
- User Input Processing  
- Conditional Rendering  
- Dynamic UI Updates  
- Code Organization using MVC Pattern  
- Debugging & Problem Solving  

---

## 🧩 MVC Architecture (Code-Based Explanation)

This project follows a **logical MVC structure within `app.js`**:

### 🔹 Model (M) – Data & Logic
- Contains **core logic functions** that process input values  
- Performs **calculations / conditions** based on user input  
- Stores and updates **computed results** before displaying  

👉 Example in the code:
- Functions that calculate results based on input  
- Conditional checks (if/else logic)  
- Data transformations before rendering  

---

### 🔹 View (V) – UI Layer
- Defined in **`index.html` and `styles.css`**  
- Contains:
  - Input fields  
  - Buttons  
  - Output/display elements  
- Responsible for **showing results to the user**

👉 Example in the code:
- HTML elements (`input`, `button`, `div`, `span`)  
- CSS styling for layout and presentation  
- Output sections where results are displayed  

---

### 🔹 Controller (C) – Interaction Layer
- Implemented in **`app.js` (event listeners + DOM updates)**  
- Handles:
  - User actions (clicks, inputs)  
  - Calls Model functions  
  - Updates the View dynamically  

👉 Example in the code:
- `addEventListener()` for button clicks  
- Reading input values using DOM (`document.getElementById`)  
- Updating UI using `.innerHTML` / `.textContent`  

---

## 📂 Project Structure

```bash
public/
  index.html    # View: UI structure (inputs, buttons, output display)
  styles.css    # View: styling and layout
  app.js        # Controller + Model: event handling, logic, and DOM updates
