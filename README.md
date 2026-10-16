# Ajeet Kumar — Personal Portfolio Website

## 1. Fastest Way to Open Locally (No Setup Needed)
1. Extract this `.zip` folder on your computer or phone.
2. Double-click **`index.html`** — it will open directly in your web browser (Chrome, Edge, Brave, Firefox, or Safari) with your profile photo, interactive project filters, skill search, and PDF resume download ready to use.

## 2. Fastest Way to Publish Online for Free (30 Seconds)
- **Option A — Netlify Drop (No coding required):**
  1. Go to https://app.netlify.com/drop
  2. Drag and drop this extracted folder (containing `index.html`) onto the page.
  3. Your live portfolio URL will be online immediately!
- **Option B — GitHub Pages:**
  1. Create a new repository on https://github.com/ajeet2026 (e.g., `ajeet2026.github.io`).
  2. Upload `index.html` and `Ajeet_Kumar_Resume_AI_Engineer.pdf` to the repository.
  3. Go to **Settings → Pages → Deploy from branch (`main`)** and your portfolio will be live at `https://ajeet2026.github.io`.

## 3. Running the React + TypeScript Source (`react-ts-source/App.tsx`)
If you want to customize and deploy using a full Vite + React + TypeScript setup:
```bash
npm create vite@latest ajeet-portfolio -- --template react-ts
cd ajeet-portfolio
npm install lucide-react tailwindcss @tailwindcss/vite
```
Copy `react-ts-source/App.tsx` into `src/App.tsx` and run:
```bash
npm run dev
```
