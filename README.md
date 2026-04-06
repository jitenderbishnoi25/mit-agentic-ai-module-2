# MIT Agentic AI - Module 2 UI Mockups

This repository houses the user interface mockup projects designed and implemented as part of the MIT Agentic AI Course. It features multiple distinct web application layouts, each demonstrating a unique design system and architectural structure built with vanilla HTML and CSS.

## 📂 Project Structure

All projects follow a unified directory structure separating design assets from codebase implementations:

```text
mit-agentic-ai-module-2/
├── apps/
│   ├── gen-ai-community/
│   │   ├── designs/        # Contains UI mockup PNG images
│   │   └── src/            # Contains HTML & CSS implementation
│   └── insurance-policy-admin/
│       ├── designs/        # Contains UI mockup PNG images
│       └── src/            # Contains HTML & CSS implementation
└── README.md
```

## 🌐 Applications

### 1. Insurance Policy Admin
A highly polished, data-dense enterprise dashboard application.
- **Design System**: Premium Enterprise Layout.
- **Aesthetics**: High-contrast, clean white cards over a soft gray-blue (`#F4F7F9`) backdrop, utilizing Corporate Blue (`#0056D2`) for accents, and color-coded status badges for instant comprehension.
- **Layout**: Employs a functional 70/30 asymmetrical grid. The main column houses the Policy Status summaries and a robust Transactions datatable. The right-hand column serves as a dedicated sidebar for Stakeholder Profile Cards (Owner and Agent specific details).

### 2. Global Gen-AI Community
A visual exploration into modern web design trends.
- **Design System**: Light Translucent **Glassmorphism**.
- **Aesthetics**: Floating pill-shaped navigation, vibrant background gradients (purple, electric blue, magenta), blurred translucent cards (`backdrop-filter: blur`), and dynamic hover animations.
- **Layout**: Features a centered Hero section, a horizontal "Featured Projects" carousel with integrated progress bars, and a three-column widget grid (Community Hub, Global Events calendar, Knowledge Base).

## 🚀 How to Run Locally

Because these prototypes are built on standard vanilla HTML and CSS without heavy framework dependencies, they are extremely easy to preview:

1. **Direct Browser Preview:**
   Navigate into any project's `src` folder (e.g., `apps/gen-ai-community/src/`) using your File Explorer and double-click `index.html`. Your default browser will render the page perfectly.

2. **Using a Local Server (Recommended for live-editing):**
   If you have Python installed, you can start a local development server by running this in your terminal from the `src` directory:
   ```bash
   # Example: Starting the Gen-AI Community app
   cd apps/gen-ai-community/src
   python -m http.server 8000
   ```
   Then open `http://localhost:8000` in your web browser. Alternatively, use the "Live Server" extension in VS Code.