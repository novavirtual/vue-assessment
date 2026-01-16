# Vue.js Frontend Assessment

## Overview
This is a simple Task Manager application built with Vue.js 3. However, there are some bugs that need to be fixed, and one feature that needs to be implemented.

## Getting Started
1. Clone this repository
2. Create a new branch with your name: `git checkout -b yourname-branch`
3. Open `index.html` in your web browser
4. Try using the app - you'll notice some things don't work correctly
5. Open the code and fix the issues listed below
6. Commit your changes and push your branch

## Your Tasks

### Task 1: Fix the Input Binding
**Problem:** When you type in the input field, the `newTask` value in the debug section doesn't update.

**Hint:** Look at how the input element is bound to the data. Vue has a special directive for two-way data binding.

**Location:** Line 68-72 in index.html

---

### Task 2: Fix the Add Button
**Problem:** Clicking the "Add Task" button doesn't add a new task to the list.

**Hint:** Look at how the click event is attached to the button. Vue uses a different syntax for event handling.

**Location:** Line 75 in index.html

---

### Task 3: Fix the List Rendering
**Problem:** Open the browser's Developer Console (F12). You'll see a warning about the list rendering.

**Hint:** When using `v-for`, Vue requires something unique for each item to track changes efficiently.

**Location:** Line 81 in index.html

---

### Task 4: Implement Delete Feature
**Problem:** Each task should have a "Delete" button that removes it from the list.

**Requirements:**
- Add a delete button inside each task item (after the `<span>`)
- The button should have `class="delete-btn"` and display the text "Delete"
- Clicking the button should call the `deleteTask` method with the task's id
- Implement the `deleteTask` method to remove the task from the array

**Locations:**
- Button: Line 84-85 in index.html
- Method: Line 115-117 in index.html

---

## Evaluation Criteria
- All 4 tasks completed correctly
- Code follows Vue.js best practices
- No console errors or warnings

## Resources (if allowed)
- Vue.js Documentation: https://vuejs.org/guide/essentials/template-syntax.html
- Vue.js List Rendering: https://vuejs.org/guide/essentials/list.html

Good luck!
