# 🛠️ Tailwind Custom Configuration

A minimal `tailwind.config.js` file to kickstart your Tailwind CSS project with custom color configuration.

---

## 📄 File Overview

```js
/** @type {import('tailwindcss').Config} */
module.exports = {
  content: [],
  theme: {
    extend: {
      colors: {
        primary: '#1e40af',
        secondary: '#000000',
      },
    },
  },
  plugins: [],
}


🎯 Purpose
This repository contains only the configuration file for Tailwind CSS with two custom colors:

Primary: #1e40af – A deep blue color, great for buttons, headers, etc.

Secondary: #000000 – Standard black for text or dark backgrounds.

Use this config to start quickly with your design system or customize further.

👨‍💻 Who Can Use This?
This config is perfect for:

Beginners learning Tailwind customization

Developers creating reusable UI kits

Designers working with consistent branding colors

Anyone who wants a ready-made Tailwind setup

🚀 How to Use
Create a Tailwind project (if not already):

bash

npm install -D tailwindcss
npx tailwindcss init
Replace your tailwind.config.js with this one.

Set your content paths in the config:

js

content: ["./index.html", "./src/**/*.{js,ts,jsx,tsx}"]
Start building using the new color utilities:

html

<div class="bg-primary text-white p-4 rounded">
  Primary colored box
</div>

<p class="text-secondary">Secondary colored text</p>
🔌 Recommended VS Code Extension
To make Tailwind development easier, install the following extension:

🔗 Tailwind CSS IntelliSense

It provides:

Autocomplete for Tailwind classes

Linting and warnings

Hover previews of classes

🌟 Benefits of Using This Config
✅ Saves setup time
✅ Enforces consistent color usage
✅ Easy to extend further
✅ Ideal for learning and production use

