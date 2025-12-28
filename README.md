# AetherPlan - Premium Visual Study Application

AetherPlan is a **premium visual study todo application** designed to help users visualize their learning progress. It goes beyond simple task lists by providing rich visual feedback through animated progress bars, charts, and a fluid user interface.

[**🚀 Live Demo**](https://aetherplan.netlify.app/)


## 🎯 Product Goal

Build a study-focused todo app that not only manages tasks but **visually represents learning progress** through **animated progress bars and charts**. The app is designed to make users *feel* their progress.

## 🧩 Key Features

### 1. 📊 Visual Progress System
*   **Dashboard**: Overall progress shown using a circular progress ring and subject-wise vertical fluid/glass progress bars.
*   **Subject Details**: Deep dive into subjects with horizontal progress bars and accordion-style unit breakdowns.
*   **Real-time Updates**: Every completed task instantly reflects across all visuals.
*   **Fluid Animations**: Glassmorphism design with liquid gradient fills and smooth entry animations.

### 2. 📝 Task Management
*   **Hierarchical Structure**: Organize by **Subjects** > **Units** > **Subtasks**.
*   **Focus Mode**: Integrated **Pomodoro Timer** to stay productive.
*   **Notes**: Knowledge base support with Markdown for keeping study notes.

### 3. 📈 Analytics
*   **Visual Charts**: Bar charts and stacked bar charts to compare subject and unit completion.
*   **Data-Driven**: Insights into your study habits and progress.

### 4. 🎨 Premium UI/UX
*   **Dark Mode**: Optimized for long study sessions.
*   **Aesthetic**: "Antigravity" hover effects, soft shadows, and a modern color palette.

## ⚛️ Tech Stack

*   **Frontend**: React (TypeScript), Vite
*   **Styling**: Tailwind CSS, Vanilla CSS (for custom glass effects)
*   **Animations**: Framer Motion
*   **Charts**: Chart.js, React-Chartjs-2
*   **State Management**: Context API
*   **Icons**: Lucide React
*   **3D Elements**: React Three Fiber / Drei (for potential 3D enhancements)

## 🚀 Getting Started

Follow these steps to set up the project locally.

### Prerequisites

*   Node.js (v18 or higher recommended)
*   npm or yarn

### Installation

1.  **Clone the repository**
    ```bash
    git clone https://github.com/mohdsarfraz08/aetherplan.git
    cd AetherPlan
    ```

2.  **Install dependencies**
    ```bash
    npm install
    ```

3.  **Run the development server**
    ```bash
    npm run dev
    ```
    The app will be available at `http://localhost:5173`.

### Building for Production

To create a production build:

```bash
npm run build
```

This will generate static files in the `dist` directory.

## 📂 Project Structure

```
src/
├── features/         # Feature-based modules (Dashboard, Study, Focus, etc.)
├── components/       # Reusable UI components (Buttons, Inputs, etc.)
├── context/          # Global state management (StudyContext, etc.)
├── hooks/            # Custom React hooks
├── styles/           # Global styles and Tailwind configuration
├── types/            # TypeScript type definitions
└── App.tsx           # Main application component
```

## 🤝 Contributing

We welcome contributions! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on how to help improve AetherPlan.

---

*Designed to make learning focused, visual, and rewarding.*
