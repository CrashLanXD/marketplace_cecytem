# 🤘🏽 CECyTEM Marketplace

---

# 🚀 Getting Started

> [!NOTE]
> Esto es solo una prueba, la pagina final es esta: https://cecytem-marketplace.vercel.app/

Before getting started, make sure you have Node.js installed on your machine. If not, you can download and install it from [the official website](https://nodejs.org/). After that, clone the repository using the following command!:

```sh
git clone https://github.com/CrashLanXD/marketplace_cecytem.git
```
Once you're in the project directory, follow the instructions in the "Commands" section to set up and start working on the project.

> Make your changes and create a pull request 😎

## 👾 Project Structure

Inside of the project, you'll see the following folders and files:

```text
/
├── public/
│   └── favicon.svg
├── src/
│   ├── pages/
│   │   └── index.html
│   │
│   └── input.css
├── package-lock.json
├── tailwind.config.js
└── package.json
```

Tailwind looks for `.html` or `.js` files in the `src/pages/` directory.

Any static assets, like images, can be placed in the `public/` directory.

## 🤖 Commands

All commands are run from the root of the project, from a terminal:

| Command       | Action                                             |
| :------------ | :------------------------------------------------- |
| `npm install` | Installs dependencies                              |
| `npm run dev` | Compiles Tailwind CSS based on input file changes. |

> [!NOTE]
> To start the development server, you can use any live server extension in your preferred code editor, such as Live Server in VS Code or Live Preview.

> [!IMPORTANT]
> this command: `npm run dev`
> Generates the appropriate CSS for the project and watches for changes in the input file (input.css) located in the src/ directory. The compiled CSS is then outputted to the output.css file in the dist/ directory. This command is essential for working with Tailwind CSS, ensuring that your styles are compiled correctly as you make changes to your project.
