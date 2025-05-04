# Next.js 15 Starter Template

A minimal, modern starter template built with **Next.js 15**, **TailwindCSS 4**, **TypeScript**, and essential libraries like **Lucide Icons**, **Radix UI**, and **Next Themes**.
Perfect for quickly launching new projects with best practices in mind.

## ✨ Features

- **Next.js 15** with **Turbopack** for fast development
- **TailwindCSS 4** with animation support
- **TypeScript** for type safety
- **Radix UI Toasts** for notifications
- **Lucide React Icons**
- **Dark mode** support with **Next Themes**
- Useful utilities (`clsx`, `tailwind-merge`, etc.)
- Pre-configured ESLint setup
- Folder structure optimized for scalability
- JWT utilities with `jose`

## 🛠️ Tech Stack

- **Next.js 15** (Pages and App Router support)
- **React 19**
- **TailwindCSS 4**
- **Radix UI**
- **Lucide Icons**
- **Next Themes**
- **TypeScript**

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/nextjs-starter-template.git
cd nextjs-starter-template
```

### 2. Install dependencies

Using **npm**:

```bash
npm install
```

Or using **yarn**:

```bash
yarn install
```

Or using **pnpm**:

```bash
pnpm install
```

### 3. Run the development server

```bash
npm run dev
```

The app will be running at [http://localhost:3000](http://localhost:3000).

---

## 📁 Folder Structure

```
src/
 ├─ app/                # App directory (app router)
 │    ├─ layout.tsx
 │    ├─ page.tsx
 │    └─ globals.css
 ├─ components/         # Reusable UI components
 │    ├─ sections/
 │    └─ shared/
 │         ├─ header.tsx
 │         └─ footer.tsx
 ├─ hooks/              # Custom hooks
 ├─ lib/                # Utilities (jwt, etc.)
 ├─ pages/              # Pages directory (API routes)
 │    └─ api/
 ├─ ui/                 # UI components (toasts, theme provider)
public/                 # Static files
```

---

## ⚙️ Available Scripts

- `npm run dev` — Start development server (Turbopack enabled)
- `npm run build` — Create production build
- `npm run start` — Start production server
- `npm run lint` — Run ESLint

---

## 📦 Environment Variables

Create a `.env.local` file based on `.sample.env.local`.

```bash
cp .sample.env.local .env.local
```

Add your environment variables there.

---

## 📜 License

This project is licensed under the **MIT License**.

---

# Happy coding! 🚀
