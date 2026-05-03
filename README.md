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

<img width="2879" height="1799" alt="Screenshot 2026-05-03 112605" src="https://github.com/user-attachments/assets/3a96e220-0ac5-4c38-b588-8e8916e1b218" />
<img width="2805" height="1286" alt="Screenshot 2026-05-03 112736" src="https://github.com/user-attachments/assets/b9a62700-1453-48e0-81ea-c2330f4a9e1f" />
<img width="2879" height="1799" alt="Screenshot 2026-05-03 112710" src="https://github.com/user-attachments/assets/3a4e60f3-8b27-43c1-8d98-1a52158895ec" />
<img width="2875" height="1799" alt="Screenshot 2026-05-03 112645" src="https://github.com/user-attachments/assets/f5c1ca00-f520-4454-98e5-9ee7e912ba33" />
<img width="2879" height="1799" alt="Screenshot 2026-05-03 112809" src="https://github.com/user-attachments/assets/465168c0-986a-4742-9b22-9ea15b0457ce" />
<img width="2273" height="1473" alt="Screenshot 2026-05-03 112831" src="https://github.com/user-attachments/assets/9b4f81f9-1f8c-4c13-894c-03bc0c976e3b" />


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
