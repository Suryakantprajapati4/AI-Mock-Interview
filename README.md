AI Mock Interview project.

Project Details:
- Name: AI Mock Interview
- Developer: Suryakant
- Degree: BTech CSE (AI & DS) Final Year
- Tech Stack: React, TypeScript, Vite, Firebase, 
  Clerk Auth, Google Gemini AI, Tailwind CSS, 
  ShadcnUI, Recharts

Features:
- AI-generated interview questions
- Speech-to-text answer recording
- Webcam support during interview
- AI feedback with ratings (1-10)
- Performance insights dashboard
- Overall score circular chart
- Strong areas vs needs improvement
- Dark/Light mode toggle
- Mobile responsive
- PDF download of feedback
- Interview history with scores
- About Us, Services, Contact Us pages

Include in README:
1. Project banner/title with badges
2. About section
3. Features list with emojis
4. Tech stack with icons/badges
5. Screenshots section (placeholder)
6. Installation steps
7. Environment variables (.env setup)
8. How to use
9. Project structure
10. Contributing
11. License (MIT)
12. Contact/Author section

![Uploading Screenshot 2026-05-03 112605.png…]()


# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

- Configure the top-level `parserOptions` property like this:

```js
export default tseslint.config({
  languageOptions: {
    // other options...
    parserOptions: {
      project: ['./tsconfig.node.json', './tsconfig.app.json'],
      tsconfigRootDir: import.meta.dirname,
    },
  },
})
```

- Replace `tseslint.configs.recommended` to `tseslint.configs.recommendedTypeChecked` or `tseslint.configs.strictTypeChecked`
- Optionally add `...tseslint.configs.stylisticTypeChecked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and update the config:

```js
// eslint.config.js
import react from 'eslint-plugin-react'

export default tseslint.config({
  // Set the react version
  settings: { react: { version: '18.3' } },
  plugins: {
    // Add the react plugin
    react,
  },
  rules: {
    // other rules...
    // Enable its recommended rules
    ...react.configs.recommended.rules,
    ...react.configs['jsx-runtime'].rules,
  },
})
```
