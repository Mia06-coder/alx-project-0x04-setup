# Context API Global State Counter App

This project demonstrates how to use **React Context API** to manage global state across multiple components without prop drilling. It extends the base structure of `alx-project-0x04` and introduces shared state between the `Header` and `CounterApp` components.

---

## 📚 Table of Contents

- [Screenshots](#screenshots)
- [Tech Stack](#tech-stack)
- [Project Structure](#project-structure)
- [Objective](#objective)
- [Installation](#installation)
- [Implementation](#implementation)
- [Credits](#credits)
- [Contact](#contact)

---

## Screenshots

![Counter App with Context API](./public/assets/images/context-api.png)

---

## Tech Stack

![React](https://img.shields.io/badge/React-18-61DAFB?style=flat&logo=react)
![TypeScript](https://img.shields.io/badge/TypeScript-4.x-3178C6?style=flat&logo=typescript)
![Next.js](https://img.shields.io/badge/Next.js-13+-000000?style=flat&logo=next.js)
![Redux Toolkit](https://img.shields.io/badge/Redux%20Toolkit-1.x-764ABC?style=flat&logo=redux)
![React Redux](https://img.shields.io/badge/React--Redux-7.x-593D88?style=flat&logo=react)
![Context API](https://img.shields.io/badge/Context%20API-Built--in-blueviolet?style=flat&logo=react)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-20.x-339933?style=flat&logo=nodedotjs)
![npm](https://img.shields.io/badge/npm-9.x-CB3837?style=flat&logo=npm)

---

## Project Structure

```plaintext
alx-project-0x05/
├── components/
│ ├── layouts/
│ │ └── Header.tsx
├── context/
│ └── CountContext.tsx
├── pages/
│ ├── _app.tsx
│ ├── index.tsx
│ └── counter-app.tsx
├── styles/
│ └── globals.css
├── public/
├── package.json
├── README.md
└── ...
```

---

## Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/mia06-coder/alx-project-0x04-setup.git
   cd alx-project-0x05
   ```

2. Install dependencies

   ```bash
   npm install
   ```

3. Run the development server
   ```bash
   npm run dev -- -p 3000
   ```

---

## Objective

The **Context API** allows us to maintain a global state that can be accessed and modified across components without needing to pass props manually at every level.

In this app:

- A counter state is declared globally.
- The `Header` and `CounterApp` components both consume and reflect changes in this global state.
- When the counter is incremented or decremented in one component, the change is reflected in the other.

---

## Implementation

1. **Create Context Provider**: `context/CountContext.tsx` contains the global counter logic
2. **Wrap Application in Provider** in `pages/_app.tsx`
3. **Update Header to Reflect Global State** in `components/layouts/Header.tsx`

---

## Credits

- Project idea & structure inspired by [ALX](https://www.alxafrica.com/) exercises
- Icons and badges from [Shields.io](https://shields.io/)

---

## Contact

Made with ❤️ by **Mia Mudzingwa**

- GitHub: [Mia06-coder](https://github.com/Mia06-coder)
- LinkedIn: [mia-mudzingwa](https://www.linkedin.com/in/mia-mudzingwa)
