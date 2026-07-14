# macOS Web Portfolio 🍎

A web-based interactive replica of the macOS desktop environment, built as a personal portfolio. This project brings a familiar, polished desktop experience to the browser, complete with a functional Dock, top Navigation Bar, and draggable, resizable application windows.

## 🌟 Features

- **macOS Desktop Interface**: A beautiful, responsive desktop experience mimicking the aesthetics of macOS.
- **Interactive App Windows**: Fully draggable, resizable, and stackable windows powered by `react-rnd`.
- **Top Navigation Bar & Dock**: Classic macOS system bar and an animated Dock for launching applications.
- **Included Applications**:
  - **Terminal / CLI**: A fully functional command-line interface simulation using `react-console-emulator`.
  - **Notes App**: A markdown-supported notepad built with `react-markdown` and `react-syntax-highlighter`.
  - **GitHub Window**: View GitHub projects and repositories directly within the desktop.
  - **Spotify Player**: An integrated music player interface.
  - **Resume Viewer**: A dedicated window to display your professional resume.

## 🛠️ Tech Stack

- **Framework**: [React 19](https://react.dev/)
- **Build Tool**: [Vite](https://vitejs.dev/)
- **Styling**: SCSS (Sass) for advanced, maintainable styling and animations.
- **Key Libraries**:
  - `react-rnd` - For draggable and resizable windows.
  - `react-console-emulator` - For the interactive CLI terminal.
  - `react-markdown` & `react-syntax-highlighter` - For rendering markdown notes and code snippets.

## 🚀 Getting Started

To run this project locally, follow these steps:

### Prerequisites

Make sure you have [Node.js](https://nodejs.org/) installed on your machine.

### Installation

1. Clone the repository (if you haven't already):
   ```bash
   git clone <repository-url>
   ```

2. Navigate into the project directory:
   ```bash
   cd "07. Mac OS"
   ```

3. Install the dependencies:
   ```bash
   npm install
   ```

4. Start the development server:
   ```bash
   npm run dev
   ```

5. Open your browser and navigate to the local URL provided by Vite (usually `http://localhost:5173`).

## 📜 Scripts

- `npm run dev`: Starts the Vite development server.
- `npm run build`: Bundles the app for production.
- `npm run lint`: Runs ESLint to check for code quality.
- `npm run preview`: Previews the production build locally.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page if you want to contribute.

## 📝 License

This project is open-source and available under the [MIT License](LICENSE).
