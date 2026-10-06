# Student Registration Form (React)

A simple student registration form built with React and Vite. It demonstrates controlled components, state management with `useState`, and form handling in React.

## Features

- Controlled inputs for **Name** and **Email**
- Live preview of the entered values below the form
- Built-in browser validation for the email field
- Success alert on submit, without a page reload

## Tech Stack

- [React](https://react.dev/)
- [Vite](https://vitejs.dev/)
- JavaScript (ES6+)

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) v18 or higher
- npm (comes with Node.js)

### Installation

```bash
# Clone the repository
git clone https://github.com/itsjayasree7/react1.git

# Go into the project folder
cd react1

# Install dependencies
npm install

# Start the development server
npm run dev
```

Open the link shown in the terminal (usually `http://localhost:5173`).

## Available Scripts

| Command | Description |
| --- | --- |
| `npm run dev` | Starts the development server |
| `npm run build` | Creates a production build in `dist/` |
| `npm run preview` | Previews the production build locally |

## Project Structure

```
react1/
├── public/
├── src/
│   ├── App.jsx      # Registration form component
│   └── main.jsx     # App entry point
├── index.html
├── package.json
└── README.md
```

## How It Works

1. `useState` stores the current value of each input (`name`, `email`).
2. `onChange` updates the state on every keystroke, and `value={...}` feeds it back into the input. This pattern is called a **controlled component**.
3. On submit, `event.preventDefault()` stops the page from refreshing, and an alert shows the entered details.
4. The paragraphs under the form re-render automatically whenever the state changes.

## Author

**Jayasree V**
GitHub: [@itsjayasree7](https://github.com/itsjayasree7)
