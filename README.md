# Splash App (ALX Project 0x03)

A modern **Next.js + TypeScript** application showcasing advanced frontend development practices.  
This project demonstrates **shared layouts, reusable components, responsive design, error handling, and TypeScript type safety** while integrating **TailwindCSS** and **React Icons**.  

It serves as a **production-ready foundation** for scalable applications, including AI-driven features such as text generation, text-to-image tools, and interactive dashboards.  

---

## 🚀 Features

- **Shared Layouts (DRY principle)** – Centralized `Header`, `Footer`, and `Layout` components for consistent branding.  
- **Reusable UI Components** – Example: `Button` with customizable props and theme support.  
- **Responsive Design** – Built with TailwindCSS utilities, optimized for all screen sizes.  
- **TypeScript Type Safety** – Centralized interfaces for better maintainability.  
- **Google Fonts Integration** – Using Montserrat for modern typography.  
- **Imperative Routing** – Navigation powered by `useRouter`.  
- **Custom Error Handling** – Friendly and fun 404 page.  

---

## 🛠️ Tech Stack

- **[Next.js](https://nextjs.org/)** – React framework with SSR and static generation.  
- **[TypeScript](https://www.typescriptlang.org/)** – Strongly typed JavaScript.  
- **[TailwindCSS](https://tailwindcss.com/)** – Utility-first CSS framework.  
- **[React Icons](https://react-icons.github.io/react-icons/)** – Scalable vector icons.  
- **[Google Fonts](https://fonts.google.com/)** – Montserrat font family.  

---

## 📂 Project Structure

```markdown
alx-project-0x03/
├── components/
│   ├── common/
│   │   └── Button.tsx
│   └── layouts/
│       ├── Header.tsx
│       ├── Footer.tsx
│       └── Layout.tsx
│
├── interfaces/
│   └── index.ts
│
├── pages/
│   ├── index.tsx
│   └── 404.tsx
│
├── styles/
│   └── global.css
│
├── public/            # Static assets (optional)
├── package.json
├── tsconfig.json
└── README.md
