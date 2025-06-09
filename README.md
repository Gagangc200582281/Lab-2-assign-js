# 📁 Node.js Assignment – ES Modules

A simple project demonstrating how to use **custom JavaScript modules** with **Node.js** using **ES Module (ESM) syntax**.

---

## 📄 Files Overview

- `app.js` → Main entry point. Imports and runs functions from `utils.js`
- `utils.js` → Exports 5 utility functions:
  1. `sendStudyReminder(name, subject)` → Logs a study reminder to the console
  2. `litresToGallons(litres)` → Converts litres to gallons
  3. `calculateAverage(numbers)` → Calculates average from an array of numbers
  4. `formatCountdown(seconds)` → Formats seconds into `HH:MM:SS`
  5. *(Slot reserved for future utilities)*

---

## 🚀 How to Run

1. Ensure [Node.js](https://nodejs.org/) is installed on your system.
2. In your project directory, make sure your `package.json` contains:
   ```json
   {
     "type": "module"
   }
