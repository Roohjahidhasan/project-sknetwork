# Project SK Network

![Project Banner](https://via.placeholder.com/800x200.png?text=Project+SK+Network)

A modern **Next.js 16 project** featuring a responsive media player, image/video support, and contact forms powered by **Formspree**. Optimized for **static export** and **BDIX hosting**.

---

## 🔹 Features

- 🎬 **Video & Image Player**
  - Play, pause, skip, volume control, fullscreen
  - Auto-hide controls on inactivity
- 📱 **Responsive Design**
  - Works perfectly on mobile, tablet, and desktop
- ✉️ **Formspree Integration**
  - Contact form ready to send messages without backend
- ⚡ **Next.js 16 + Turbopack**
  - Fast, optimized production build
- 🎨 **Tailwind CSS Styling**
  - Modern UI components with Lucide icons

---

## 🔹 Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/project-sknetwork.git
cd project-sknetwork
Install dependencies:

bash
Copy code
npm install
Run the development server:

bash
Copy code
npm run dev
Open http://localhost:3000 to view in your browser.

🔹 Build for Production
bash
Copy code
npm run build
npm start
For static hosting (recommended for BDIX server):

bash
Copy code
# Export static version
npm run build
npm run export
This will create an out/ folder ready for deployment.

🔹 Project Structure
lua
Copy code
project-sknetwork/
├─ app/
│  ├─ globals.css
│  └─ layout.tsx
├─ components/
│  └─ media-player.tsx
├─ public/
├─ pages/
├─ package.json
└─ next.config.js
