# Interactive Map Workout Tracker

Frontend-focused, object-oriented JavaScript application that demonstrates real-world usage of browser APIs, third-party mapping libraries, and clean application architecture. The app allows users to log workouts directly on an interactive map using their current geolocation, with persistent client-side storage.

**Tech focus:** JavaScript (ES6+), OOP, Leaflet.js, browser APIs, UI state management

---

## Why This Project Matters

This project showcases the ability to:

- Build a non-trivial interactive UI without frameworks  
- Architect a maintainable application using **Object-Oriented Programming**  
- Integrate third-party libraries and native browser APIs  
- Manage application state and persistence without a backend  
- Write clean, readable, and scalable JavaScript  

It reflects the type of problem-solving and structure expected in production frontend codebases.

---

## Core Features

- Uses the **Geolocation API** to center the map on the user’s real location  
- Interactive map powered by **Leaflet.js** and **OpenStreetMap**  
- Click-to-log workouts with form validation and UI feedback  
- Supports multiple workout types using **class inheritance**  
- Renders dynamic markers, popups, and animated map transitions  
- Persists data across sessions via **localStorage**

---

## Technical Highlights

### Architecture

- Object-oriented design with clear separation of concerns  
- Base `Workout` class with `Running` and `Cycling` subclasses  
- Central `App` controller class managing:
  - Map lifecycle  
  - Event handling  
  - State updates  
  - UI rendering  
  - Persistence  

### JavaScript Concepts Demonstrated

- ES6 classes and inheritance  
- Private class fields (`#map`, `#workouts`)  
- Event delegation  
- Functional input validation  
- Template-based DOM rendering  
- Client-side persistence with JSON serialization  

---

## External Integrations

- **Leaflet.js** — map rendering, markers, and popups  
- **OpenStreetMap** — map tile service  
- **Browser Geolocation API** — user location detection  
- **Web Storage API (localStorage)** — client-side persistence  

---

## Tech Stack

### Frontend
- JavaScript (ES6+)
- HTML
- CSS

### Libraries & APIs
- Leaflet.js
- OpenStreetMap
- Geolocation API
- Web Storage API

### Tooling
- No frameworks or build tools — runs directly in the browser
