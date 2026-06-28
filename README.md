# crossword1

# Crossword Game

## SD1 Assignment 1 – Part A: Project Design, Development and Deployment

## Project Description

The aim of this project was to design, develop and deploy a browser-based crossword puzzle game using HTML5, CSS3 and JavaScript. The game allows players to complete a crossword puzzle by selecting clues and entering letters into a crossword grid. The application validates answers, provides hints, records the player's score, measures completion time and provides visual feedback throughout the game.

The application was designed following a prototyping approach. Initial concepts were discussed within the group before being refined through several iterations based on testing and usability improvements.

The finished application is lightweight, responsive and runs entirely within a web browser without requiring additional software.

# Team Members and Contributions

| Team Member | Role                   | Contribution                                                       |
| ----------- | ---------------------- | ------------------------------------------------------------------ |
| Student 1   | Project Coordinator    | Organised meetings, Git repository and documentation               |
| Student 2   | Front-end Developer    | Developed HTML layout and CSS styling                              |
| Student 3   | JavaScript Developer   | Implemented crossword logic, scoring system, timer and hint system |
| Student 4   | Tester & Documentation | Conducted testing, bug reporting and README preparation            |


# Target Users

The primary target audience consists of students and casual puzzle game players aged between 16 and 35 years.

The application is intended to provide an enjoyable educational experience while encouraging vocabulary development and logical thinking.

Users require:

* Simple controls
* Clear instructions
* Immediate feedback
* Responsive interface
* Quick loading times
* Compatibility across modern web browsers

# User Profiles

## User Profile 1

**Name:** Sarah

**Age:** 19

**Occupation:** University Student

### Goals

* Improve vocabulary
* Enjoy short puzzle games between lectures
* Play on laptop or tablet

### Requirements

* Easy navigation
* Timer
* Simple interface
* Helpful hints

## User Profile 2

**Name:** James

**Age:** 27

**Occupation:** Office Administrator

### Goals

* Relax during breaks
* Challenge memory
* Complete puzzles quickly

### Requirements

* Fast performance
* Score tracking
* Responsive controls
* Keyboard support

# User Requirements

The following user requirements were identified during the requirements gathering stage.

| Requirement                  | Priority |
| ---------------------------- | -------- |
| Enter letters into crossword | High     |
| Display clues                | High     |
| Check answers                | High     |
| Highlight selected word      | High     |
| Timer                        | Medium   |
| Score tracking               | Medium   |
| Hint button                  | Medium   |
| Reset puzzle                 | High     |
| Reveal puzzle                | Low      |
| Responsive design            | Medium   |

# System Requirements

## Hardware

* Desktop PC
* Laptop
* Tablet
* Smartphone

## Software

* Google Chrome
* Microsoft Edge
* Mozilla Firefox
* Safari

## Development Languages

* HTML5
* CSS3
* JavaScript

## Development Tools

* Visual Studio Code
* Git
* GitHub

---

# Functional Requirements

The system shall:

* Display a crossword grid
* Display across and down clues
* Allow users to enter letters
* Highlight the selected word
* Validate answers
* Calculate score
* Track mistakes
* Display elapsed time
* Provide hints
* Reveal completed answers
* Reset the game

---

# Non-Functional Requirements

The application should:

* Be easy to learn
* Load within two seconds
* Be responsive across devices
* Use consistent colours and typography
* Provide immediate visual feedback
* Be accessible using keyboard controls
* Be maintainable through modular JavaScript

---

# User Interface Design

The interface consists of four main sections:

1. Header displaying the game title.
2. Crossword grid.
3. Clue panel containing Across and Down clues.
4. Game controls including Check, Hint, Reset and Reveal buttons.

# Storyboard

### Screen 1

Application loads.

↓

### Screen 2

Player selects a clue.

↓

### Screen 3

Player enters letters.

↓

### Screen 4

Player checks answers.

↓

### Screen 5

If correct, score increases.

↓

### Screen 6

Puzzle completed.

↓

### Screen 7

Completion message displayed.

---

# High-Level Pseudocode

```
START

Load crossword

Display clues

WHILE puzzle incomplete

Select clue

Enter letters

IF player checks answers

Compare input with solution

Highlight correct answers

Highlight incorrect answers

Update score

ENDIF

ENDWHILE

Display completion message

END
```

---

# System Flow

```
Start

↓

Load Puzzle

↓

Display Crossword

↓

Select Clue

↓

Enter Letters

↓

Check Answers

↓

Correct?

↓

No → Continue Playing

↓

Yes

↓

Puzzle Complete

↓

Display Final Score

↓

End
```

---

# Development Strategy

The project followed an Agile prototyping methodology.

Development began with simple interface mock-ups before implementing core functionality. Features were developed incrementally, allowing each section of the application to be tested before additional functionality was introduced.

The Git repository enabled collaboration by allowing group members to work on different sections of the project simultaneously.

## Advantages

* Early testing
* Continuous improvement
* Easier bug fixing
* Better collaboration

## Disadvantages

* Merge conflicts can occur
* Requires regular communication
* Documentation must be updated frequently

---

# Project Risks

| Risk                  | Likelihood | Impact | Mitigation                |
| --------------------- | ---------- | ------ | ------------------------- |
| JavaScript errors     | Medium     | High   | Frequent testing          |
| Git merge conflicts   | Medium     | Medium | Use separate branches     |
| Browser compatibility | Low        | Medium | Test in multiple browsers |
| Scope expansion       | Medium     | High   | Keep requirements simple  |

---

# Test Plan

| Test            | Expected Result             | Outcome |
| --------------- | --------------------------- | ------- |
| Crossword loads | Grid displayed              | Pass    |
| Clues displayed | Across and Down visible     | Pass    |
| Letter entry    | Character displayed         | Pass    |
| Check answers   | Correct answers highlighted | Pass    |
| Hint button     | One letter revealed         | Pass    |
| Reset button    | Grid cleared                | Pass    |
| Reveal button   | Puzzle completed            | Pass    |
| Timer           | Counts correctly            | Pass    |
| Score           | Updates correctly           | Pass    |

---

# Testing Summary

Testing was conducted throughout development.

Functional testing confirmed that all primary game features worked as expected.

User interface testing ensured that buttons, keyboard controls and clue selection operated correctly.

Browser testing was completed using Google Chrome and Microsoft Edge.

Minor issues relating to word highlighting and crossword intersections were identified during development and corrected before deployment.

---

# Deployment

The project was managed using Git and hosted on GitHub.

The final version was deployed using GitHub Pages, allowing the application to be accessed directly through a web browser.

Git was used for:

* Version control
* Collaborative development
* Backup
* Change tracking

---

# Evaluation

The project successfully met its primary objectives.

Users were able to:

* Complete crossword puzzles
* Receive immediate feedback
* Track their score
* Measure completion time
* Use hints when necessary

Areas for future improvement include:

* Multiple crossword puzzles
* Random puzzle generation
* Difficulty selection
* Save game functionality
* Mobile gesture controls
* Online leaderboard

Overall, the project met the agreed requirements and demonstrated effective application of HTML, CSS and JavaScript within a browser-based environment.

---

# References

Mozilla Developer Network (2025) *HTML Documentation*. Available at: https://developer.mozilla.org/ (Accessed: 28 June 2026).

Mozilla Developer Network (2025) *CSS Documentation*. Available at: https://developer.mozilla.org/ (Accessed: 28 June 2026).

Mozilla Developer Network (2025) *JavaScript Guide*. Available at: https://developer.mozilla.org/ (Accessed: 28 June 2026).

GitHub (2025) *GitHub Documentation*. Available at: https://docs.github.com/ (Accessed: 28 June 2026).

W3C (2025) *HTML5 Specification*. Available at: https://www.w3.org/ (Accessed: 28 June 2026).
