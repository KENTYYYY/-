gomihiroi-lp/
├── public/
│   ├── favicon.ico
│   └── images/
│       ├── mascot_otter.png
│       ├── screenshot_top.png
│       ├── screenshot_battle.png
│       └── screenshot_reward.png
│
├── src/
│   ├── components/
│   │   ├── HeroSection.tsx
│   │   ├── FeatureSection.tsx
│   │   ├── FlowSection.tsx
│   │   ├── ScreenshotGallery.tsx
│   │   ├── CTASection.tsx
│   │   ├── FAQ.tsx
│   │   ├── Footer.tsx
│   │   └── HeaderMobile.tsx
│   │
│   ├── pages/
│   │   └── index.tsx
│   │
│   └── styles/
│       └── globals.css
│
├── .gitignore
├── package.json
├── tsconfig.json
├── tailwind.config.js
├── postcss.config.js
├── next.config.js
└── README.md
npm install next react react-dom
npm install -D typescript tailwindcss postcss autoprefixer
npx tailwindcss init -p
npm install framer-motion lucide-react
module.exports = {
  content: ["./src/**/*.{js,ts,jsx,tsx}"],
  theme: {
    extend: {},
  },
  plugins: [],
}
@tailwind base;
@tailwind components;
@tailwind utilities;

body {
  font-family: sans-serif;
}
git init
git add .
git commit -m "🎉 LP初期構成コミット"
git branch -M main
git remote add origin https://github.com/あなたのユーザー名/gomihiroi-lp.git
git push -u origin main
