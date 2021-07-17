# TailwindCSS iOS 15 Notification Summary

The code in this repository is base on the
[Rebuilding iOS 15 with Tailwind CSS](https://youtu.be/eSzNNYk7nVU)
notes.

## Setup Notes

```bash
npm init vite
npm install -D tailwindcss@latest postcss@latest autoprefixer@latest
npx tailwindcss init -p

```

Modify line below.

```bash title="tailwind.config.js"
   purge: ['./index.html', './src/**/*.{vue,js,ts,jsx,tsx}'],
```

Replace all line with lines below.

```bash title="style.css"
@tailwind base;
@tailwind components;
@tailwind utilities;
```
