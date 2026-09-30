<div align="center">

<img src="./assets/mitacsc_logo.png" alt="MIT ACSC Logo" width="340" />

# MAEER's MIT Arts, Commerce & Science College
### Alandi (D), Pune - 412 105
*(An Autonomous College Affiliated to Savitribai Phule Pune University | Accredited by NAAC with 'A' Grade)*

---

## 🎓 School of Computer Science & Applications
### Department of Science and Computer Science

### **Course: Lab Course on Full Stack Development - III**
**Course Code:** `2412MJET306A` &nbsp;|&nbsp; **Academic Year:** `2026-27`

<p align="center">
  <img src="https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white" alt="Angular" />
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
</p>

</div>

---

## 👨‍🎓 Student & Academic Details

| Field | Details |
| :--- | :--- |
| **Student Name** | **Mr. Aniket Tayade** |
| **Class** | **S.Y. M.Sc. (Computer Science)** |
| **Semester** | **Semester III** |
| **Division** | `M1` |
| **Roll Number** | `SM1111` |
| **Course Incharge / Guide** | `Dr. Santosh Pandure Sir` |

---

## 📌 Repository Overview

This repository houses all the practical assignments prescribed in the syllabus for the **Full Stack Development - III Lab Course (2412MJET306A)**. 

To maintain clarity and ease of academic review, each practical is structured as a **self-contained standalone code module** inside its respective technology directory:
- **`Angular/`**: Contains Solutions for Practical 01 through Practical 09.
- **`React/`**: Contains Solutions for Practical 10 through Practical 14.

Every practical file encapsulates the core component logic, view template / JSX, and custom styling required to execute and understand the assignment.

---

## 📑 Assignment Completion Sheet (Index)

| Sr. No. | Technology | Assignment Name | File Path | Status |
| :---: | :---: | :--- | :--- | :---: |
| **1** | Angular | A simple 'Hello World' application built using the Angular framework. | [`Angular/Practical-01`](./Angular/Practical-01) | ✅ Completed |
| **2** | Angular | An Angular application designed to display a simple timetable, showcasing scheduled events or tasks in an easy-to-read format using Angular components and data binding. | [`Angular/Practical-02`](./Angular/Practical-02) | ✅ Completed |
| **3** | Angular | Write an Angular program to demonstrate string interpolation by displaying a dynamic message stored in a component class. | [`Angular/Practical-03`](./Angular/Practical-03) | ✅ Completed |
| **4** | Angular | Write an Angular program to display a list of 10 student names using an array. | [`Angular/Practical-04`](./Angular/Practical-04) | ✅ Completed |
| **5** | Angular | Create an angular app to display a Time Table using one way data binding. | [`Angular/Practical-05`](./Angular/Practical-05) | ✅ Completed |
| **6** | Angular | Create an angular app to display student portfolios. | [`Angular/Practical-06`](./Angular/Practical-06) | ✅ Completed |
| **7** | Angular | Create an Angular App to demonstrate the two way data binding. | [`Angular/Practical-07`](./Angular/Practical-07) | ✅ Completed |
| **8** | Angular | Simple routing demo in Angular. | [`Angular/Practical-08`](./Angular/Practical-08) | ✅ Completed |
| **9** | Angular | Defining route parameters and retrieving data in components. | [`Angular/Practical-09`](./Angular/Practical-09) | ✅ Completed |
| **10** | React | Build Hello World React App. | [`React/Practical-10`](./React/Practical-10) | ✅ Completed |
| **11** | React | Counter App – Increment, decrement, and reset a number using React. | [`React/Practical-11`](./React/Practical-11) | ✅ Completed |
| **12** | React | To-Do List – Add, edit, mark complete, and delete tasks using React. | [`React/Practical-12`](./React/Practical-12) | ✅ Completed |
| **13** | React | Calculator – Basic arithmetic operations using React. | [`React/Practical-13`](./React/Practical-13) | ✅ Completed |
| **14** | React | Digital Clock – Display live time and date using React. | [`React/Practical-14`](./React/Practical-14) | ✅ Completed |

---

## 📂 Detailed Practical Summaries

### 🅰️ Angular Practicals (`Angular/`)

#### 1. Practical-01: Hello World Application
- **Key Concepts:** Component declaration, Standalone components, template binding, styles.
- **Summary:** Introductory Angular component presenting dynamic title, greeting message, and styled card layout.

#### 2. Practical-02: Scheduled Events & Timetable App
- **Key Concepts:** Complex interfaces (`ScheduleEvent`), interactive tab selection (`(click)` event binding), `*ngFor` iteration, badge status coloring with `[ngClass]`.
- **Summary:** An interactive timetable dashboard displaying lecture schedules, venues, instructors, and session types (Theory, Lab, Recess) across multiple days of the week.

#### 3. Practical-03: String Interpolation Demonstration
- **Key Concepts:** Angular string interpolation syntax `{{ }}`, method invocation in template, arithmetic expressions, date pipe `| date:'fullDate'`.
- **Summary:** Demonstrates how Angular dynamically binds and evaluates component class properties and expressions into the DOM.

#### 4. Practical-04: Student Names Array Iteration
- **Key Concepts:** `*ngFor` structural directive, array manipulation, `CommonModule`.
- **Summary:** Displays an array of 10 student names formatted in an unordered list.

#### 5. Practical-05: Timetable using One-Way Data Binding
- **Key Concepts:** One-way data binding, 2D arrays (`timetable: string[][]`), nested loops, table rendering.
- **Summary:** Displays weekly lecture slots utilizing one-way data binding from component arrays to HTML table cells.

#### 6. Practical-06: Student Portfolio Application
- **Key Concepts:** Complex nested model binding, project cards, skills list, external links binding with `[href]`.
- **Summary:** Comprehensive student portfolio page showcasing personal profile, skills matrix, project highlights, and contact information.

#### 7. Practical-07: Two-Way Data Binding
- **Key Concepts:** `FormsModule`, `[(ngModel)]` banana-in-a-box syntax.
- **Summary:** Demonstrates real-time synchronization between input fields and component state without page reloads.

#### 8. Practical-08: Simple Routing Demo
- **Key Concepts:** Angular Router (`@angular/router`), `RouterModule`, `Routes`, `<router-outlet>`, `routerLink`, `routerLinkActive`.
- **Summary:** Single-page navigation between Home and About components.

#### 9. Practical-09: Route Parameters & Data Retrieval
- **Key Concepts:** Parameterized routes (`path: 'user/:id'`), `ActivatedRoute`, `snapshot.paramMap.get('id')`.
- **Summary:** Extracts dynamic parameters from the URL route and updates component view accordingly.

---

### ⚛️ React Practicals (`React/`)

#### 10. Practical-10: Hello World React App
- **Key Concepts:** Functional Components, JSX, `useState` hook, controlled inputs, spinning animation.
- **Summary:** Interactive greeting card that updates dynamic text as the user types their name, along with React branding badges.

#### 11. Practical-11: Interactive Counter Application
- **Key Concepts:** State management (`useState`), conditional class binding, configurable step size, event handlers (`onClick`).
- **Summary:** Allows users to increment, decrement, and reset numeric values with configurable steps and color cues (green for positive, red for negative).

#### 12. Practical-12: Full-Featured To-Do List
- **Key Concepts:** CRUD operations in state (`tasks.map`, `tasks.filter`, `...tasks`), inline editing mode, task completion toggling, form submission (`onSubmit`).
- **Summary:** A task manager enabling adding, inline editing, striking through completed items, and removing tasks.

#### 13. Practical-13: Basic Arithmetic Calculator
- **Key Concepts:** Grid keypad layout, operator precedence, string expression evaluation, decimal precision handling, error boundaries.
- **Summary:** Sleek calculator handling addition, subtraction, multiplication, division, percentage, backspace (`DEL`), and all-clear (`AC`).

#### 14. Practical-14: Live Digital Clock
- **Key Concepts:** `useEffect` hook, `setInterval` / `clearInterval` memory management, format toggling (12-hour vs 24-hour), real-time date extraction.
- **Summary:** Glowing cyberpunk digital clock showing live hours, minutes, seconds, AM/PM tag, day of the week, and formatted calendar date.

---

## 🚀 How to Run the Solutions

Each practical file contains the complete component, template, and style code labeled by file comments.

### Running an Angular Practical
1. **Prerequisites:** Ensure Node.js (v18+) and Angular CLI (`npm i -g @angular/cli`) are installed.
2. **Generate or use an Angular workspace:**
   ```bash
   ng new fsd-angular-lab --standalone
   cd fsd-angular-lab
   ```
3. Copy the corresponding sections from `Angular/Practical-XX`:
   - Paste the code under `// app.component.ts` into `src/app/app.component.ts`.
   - Paste the code under `// app.component.html` into `src/app/app.component.html`.
   - Paste the code under `// app.component.css` into `src/app/app.component.css`.
4. **Start Development Server:**
   ```bash
   ng serve
   ```
5. Open browser at `http://localhost:4200/`.

---

### Running a React Practical
1. **Prerequisites:** Ensure Node.js (v18+) is installed.
2. **Create a React project using Vite:**
   ```bash
   npm create vite@latest fsd-react-lab -- --template react
   cd fsd-react-lab
   npm install
   ```
3. Copy the corresponding sections from `React/Practical-XX`:
   - Paste the code under `// App.jsx` into `src/App.jsx`.
   - Paste the code under `// App.css` into `src/App.css`.
4. **Start Development Server:**
   ```bash
   npm run dev
   ```
5. Open browser at the URL shown in terminal (typically `http://localhost:5173/`).

---

## 📁 Directory Structure

```text
├── assets/
│   └── mitacsc_logo.png           # Official College Logo
├── Angular/
│   ├── Practical-01               # Hello World Angular App
│   ├── Practical-02               # Scheduled Events & Timetable (Components & Data Binding)
│   ├── Practical-03               # String Interpolation Demo
│   ├── Practical-04               # Display 10 Student Names (Array & *ngFor)
│   ├── Practical-05               # Time Table using One-Way Data Binding
│   ├── Practical-06               # Student Portfolios App
│   ├── Practical-07               # Two-Way Data Binding ([(ngModel)])
│   ├── Practical-08               # Simple Routing Demo
│   └── Practical-09               # Route Parameters & Data Retrieval
├── React/
│   ├── Practical-10               # Hello World React App
│   ├── Practical-11               # Counter App (useState: inc, dec, reset)
│   ├── Practical-12               # To-Do List (Add, Edit, Complete, Delete)
│   ├── Practical-13               # Calculator (Arithmetic operations)
│   └── Practical-14               # Digital Clock (Live time & date with useEffect)
└── README.md                      # Comprehensive Lab Documentation
```

---

<div align="center">
  <sub>MAEER's MIT Arts, Commerce and Science College, Alandi (D), Pune • Department of Science and Computer Science</sub>
</div>
