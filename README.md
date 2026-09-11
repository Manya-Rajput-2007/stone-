# ✊ Stone Paper Scissors Game

An interactive web-based Stone Paper Scissors game built using HTML, CSS, and JavaScript.

The game allows players to choose between Rock, Paper, and Scissors while competing against the computer. The score is updated dynamically based on the outcome of each round.

---

## 📌 About the Project

Stone Paper Scissors is a classic decision-making game implemented as a browser-based application.

The project demonstrates the fundamentals of frontend web development by combining HTML for structure, CSS for styling, and JavaScript for game logic and interactivity.

Players can select one of three moves:

* 🪨 Rock
* 📄 Paper
* ✂️ Scissors

The computer generates a random move, and the winner is determined according to the traditional rules of the game.

---

## 🎯 Objectives

The main objectives of this project are:

* Practice HTML structure and semantic elements.
* Learn CSS styling and layout design.
* Understand JavaScript event handling.
* Implement conditional statements and game logic.
* Practice DOM manipulation.
* Build an interactive browser-based application.

---

## ✨ Features

* Interactive Rock, Paper, and Scissors choices.
* Computer-generated random moves.
* Automatic winner determination.
* Separate score tracking for player and computer.
* Dynamic game status messages.
* Image-based buttons for an engaging user interface.

---

## 🎮 Game Rules

The winner is decided according to these rules:

| Player Move | Computer Move | Winner |
| ----------- | ------------- | ------ |
| Rock        | Scissors      | Player |
| Paper       | Rock          | Player |
| Scissors    | Paper         | Player |
| Same Move   | Same Move     | Draw   |

### Simple Rule

* Rock beats Scissors.
* Scissors beats Paper.
* Paper beats Rock.

---

## 🛠️ Technologies Used

* **HTML5** — Structure of the game interface.
* **CSS3** — Styling, layout, and visual design.
* **JavaScript** — Game logic, random computer moves, score updates, and DOM manipulation.

---

## 📂 Project Structure

```text
stone-paper-scissors/
│
├── index.html
│   └── Main HTML structure
│
├── game.css
│   └── Styling and layout
│
├── deep.js
│   └── Game logic and JavaScript functionality
│
├── rock.png
│   └── Rock image
│
├── PAPER.jpg
│   └── Paper image
│
├── scissors.png
│   └── Scissors image
│
└── README.md
```

---

## ⚙️ How the Game Works

### 1. User Selects a Move

The player clicks on one of the three available choices:

```html
<div class="manyaa" id="rock">
```

```html
<div class="manyaa" id="paper">
```

```html
<div class="manyaa" id="scior">
```

### 2. Computer Generates a Random Move

JavaScript selects a random choice from Rock, Paper, or Scissors.

### 3. Winner Is Determined

The player's selection is compared with the computer's selection using conditional logic.

### 4. Score Is Updated

The score board tracks:

* Player Score (`you`)
* Computer Score (`comp`)

### 5. Game Message Updates

The result is displayed dynamically through the game status message:

```html
<p id="hn" class="man">Play Your Move</p>
```

---

## ▶️ How to Run the Project

### Clone the Repository

```bash
git clone https://github.com/Manya-Rajput-2007/stone-paper-scissors.git
```

### Navigate to the Project Folder

```bash
cd stone-paper-scissors
```

### Run the Application

Open the `index.html` file in any modern web browser.

No additional libraries or dependencies are required.

---

## 📸 Demo

Add screenshots or a GIF of your game interface here.

Example:

```markdown
![Stone Paper Scissors Game](./screenshot.png)
```

You can also deploy the project using GitHub Pages and add the live demo link.

---

## 🔮 Future Improvements

Possible enhancements for this project include:

* Add a "Play Again" or "Reset Score" button.
* Add animations when selecting a move.
* Display the computer's selected move visually.
* Add sound effects.
* Introduce multiple game rounds.
* Add difficulty levels.
* Improve responsive design for mobile devices.
* Create a dark mode theme.
* Add win streak tracking.

---

## 📚 Learning Outcomes

Through this project, I strengthened my understanding of:

* HTML elements and page structure.
* CSS styling and responsive layouts.
* JavaScript event listeners.
* Random number generation.
* Conditional statements.
* DOM manipulation.
* Interactive frontend application development.

---

## 👩‍💻 Author

**Manya Rajput**

B.Tech Computer Science Engineering Student | AIML & Software Development Enthusiast

Interested in Python, Artificial Intelligence, Machine Learning, Full-Stack Development, and Problem Solving.

### Connect With Me

* GitHub: [Manya Rajput](https://github.com/Manya-Rajput-2007)
* LinkedIn: [Manya Rajput](https://linkedin.com/in/manya-rajput-2a281b33)

---

## ⭐ Support the Project

If you enjoyed this project or found it useful for learning web development, feel free to explore and star the repository!

Happy Coding! 🚀
