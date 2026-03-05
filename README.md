# Nitin Kumar Mishra - Portfolio

A modern, interactive portfolio web application built for Nitin Kumar Mishra, an AI Developer, Generative AI Engineer, and NASA Space Apps Challenge Winner.

## UI & Design Features

This portfolio is designed with a premium, sleek aesthetic, leveraging cutting-edge web technologies to create an engaging user experience:

*   **Interactive 3D Background**: Utilizes `@shadergradient/react` and `@react-three/fiber` to render a dynamic, animated, and responsive WebGL shader background that reacts to the environment.
*   **Modern Framework & Styling**: Built on **Next.js 15** with **React 19**, styled using **Tailwind CSS** for a highly responsive and customizable utility-first design system.
*   **Smooth Animations**: Incorporates **Framer Motion** for elegant page transitions, scroll animations, and interactive component states.
*   **Accessible Components**: Uses **Radix UI** primitives and **shadcn/ui** patterns to ensure all interactive elements (dialogs, dropdowns, tooltips, etc.) are fully accessible and keyboard-friendly.
*   **Typography**: Features a curated blend of Google Fonts (`Space Grotesk` for headings, `Inter` for body text, and `JetBrains Mono` for code/technical accents) to present a clean, developer-focused typographic hierarchy.
*   **Theming**: Supports seamless Light/Dark mode transitions via `next-themes`.

### Key Sections
*   `Hero`: High-impact introduction with the interactive shader background.
*   `About`: Professional summary and background details.
*   `Skills`: Visual representation of technical proficiencies.
*   `Projects`: Showcase of key developments and AI solutions.
*   `Experience`: Work history and professional roles.
*   `Achievements`: Highlights such as the NASA Space Apps Challenge victory.
*   `Contact`: Interactive form and links to professional networks.

---

## Project Setup

### Prerequisites

Ensure you have the following installed on your local machine:
*   [Node.js](https://nodejs.org/en/) (v18 or higher recommended)
*   **npm**, **yarn**, **pnpm**, or **bun** (Project uses `pnpm` based on lockfile)

### Installation

1.  **Clone the repository** (if you haven't already):
    ```bash
    git clone <repository-url>
    cd portfolio-main
    ```

2.  **Install dependencies**:
    We recommend using `pnpm` as it is the package manager used to generate the lockfile.
    ```bash
    pnpm install
    # or npm install / yarn install
    ```

3.  **Run the Development Server**:
    Start the local server with Next.js fast refresh.
    ```bash
    npm run dev
    # or pnpm dev / yarn dev
    ```

4.  **View the Application**:
    Open your browser and navigate to [http://localhost:3000](http://localhost:3000) to view the portfolio.

### Building for Production

To create an optimized production build, run:
```bash
npm run build
```

To start the local production server to test the build:
```bash
npm run start
```

### Key Commands

*   `npm run dev`: Starts the Next.js development server.
*   `npm run build`: Builds the application for production deployment.
*   `npm run start`: Runs the production server.
*   `npm run lint`: Runs ESLint to check for code issues.
