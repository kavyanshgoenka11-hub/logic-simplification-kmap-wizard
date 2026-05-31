# Logic Simplification & K-Map Wizard

An interactive web-based application for Boolean Logic Simplification using Karnaugh Maps (K-Maps). The tool enables users to enter Boolean expressions or minterm/maxterm representations and instantly generate truth tables, K-Maps, simplified SOP/POS expressions, and logic circuit diagrams.

## Live Demo

🔗 yelping-blush-m3j4ozvvqh.edgeone.app


## Project Overview

Logic Simplification & K-Map Wizard is designed to help students, educators, and digital logic enthusiasts simplify Boolean expressions efficiently.

The application supports real-time analysis and visualization of digital logic functions using a clean and interactive user interface.

Users can:

- Enter Boolean expressions directly
- Input Minterms or Maxterms
- Generate Truth Tables automatically
- Visualize 4-variable Karnaugh Maps
- Obtain simplified SOP and POS expressions
- Generate Logic Circuit Diagrams
- Copy generated expressions instantly


## Features

### Boolean Expression Input

Supports Boolean expressions using:

- AND (`*`, `&`, or space)
- OR (`+` or `|`)
- NOT (`'`)

Example:

A'B + CD'

### Minterm / Maxterm Support

Supports:

m(0,1,3,5) and M(2,4,6,8) representations.

### Truth Table Generation

Automatically generates the complete truth table for all combinations of:

- A
- B
- C
- D


### Karnaugh Map Visualization

Provides a graphical 4-variable K-Map representation with:

- Gray Code Ordering
- SOP Grouping
- POS Grouping
- Group Highlighting


### SOP Simplification

Generates:

- Canonical SOP
- Minimal SOP Expression

### POS Simplification

Generates:

- Canonical POS
- Minimal POS Expression

### Logic Diagram Generation

Automatically generates:

#### SOP Circuit

- NOT Gates
- AND Gates
- OR Gates

#### POS Circuit

- NOT Gates
- OR Gates
- AND Gates

using SVG-based rendering.


### Responsive User Interface

Works across:

- Desktop
- Tablet
- Mobile Devices


## Technology Stack

### Frontend

- HTML5
- CSS3
- JavaScript (ES6)

### UI Framework

- Tailwind CSS

### Mathematical Rendering

- KaTeX

### Graphics

- SVG (Scalable Vector Graphics)

### Logic Processing

- Custom Boolean Expression Parser
- Truth Table Generator
- K-Map Solver
- Logic Diagram Generator


## Project Architecture

User Input
     ↓
Expression Parser
     ↓
Truth Table Generator
     ↓
K-Map Generator
     ↓
SOP/POS Simplifier
     ↓
Logic Diagram Renderer
     ↓
Result Visualization

## Educational Applications

This project can be used for:

- Digital Logic Design
- Theory of Computation
- Computer Organization
- Electronics Engineering
- Academic Demonstrations
- Boolean Algebra Learning

---

## Future Improvements

- 5 Variable K-Map Support
- 6 Variable K-Map Support
- Don't Care Conditions
- Expression Export as PDF
- Save Results Feature
- Backend Database Integration
- User Authentication
- Dark/Light Theme Toggle
- Advanced Quine-McCluskey Minimization

---

## Learning Outcomes

Through this project I gained practical experience in:

- JavaScript Programming
- Boolean Algebra Processing
- Digital Logic Design
- Algorithm Development
- SVG Graphics Rendering
- UI/UX Design
- Frontend Web Development
- Problem Solving
- 

## License

This project is intended for educational and learning purposes.
