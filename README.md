# Motswna Intelligence – 

Welcome to the **Motswna Intelligence** company landing page! This project is built with [Next.js](https://nextjs.org/) and powered by [TinaCMS](https://app.tina.io), giving our team the ability to visually manage content and collaborate on updates directly within the website.


---

## 🌟 Key Features

- 🔧 Visual editing with [TinaCMS](https://app.tina.io)
- ✍️ Markdown/JSON content stored in GitHub
- 🌐 Hosted on GitHub Pages or [Vercel](https://vercel.com)
- 🛠 Local development with Tina GraphQL API
- 👥 Ready for team collaboration and content modeling

---

## 🚀 Getting Started

### Requirements

Make sure you have the following installed:

- Git
- Node.js (LTS version recommended)
- [pnpm](https://pnpm.io) (preferred package manager)
- A [TinaCMS account](https://app.tina.io)

---


---

## 🚀 Getting Started

### 1. Install Dependencies

```bash
pnpm install
```

### 2. Start Local Development

```bash
pnpm dev
```

### 🔗 Local URLs

* [http://localhost:3000](http://localhost:3000) – Website preview
* [http://localhost:3000/admin](http://localhost:3000/admin) – Tina Cloud editor
* [http://localhost:3000/exit-admin](http://localhost:3000/exit-admin) – Exit edit mode
* [http://localhost:4001/altair/](http://localhost:4001/altair/) – GraphQL playground

---

## 🌍 Deploying to Vercel

This project is fully compatible with [Vercel](https://vercel.com), which supports both static and dynamic rendering and integrates well with TinaCMS.

### Steps:

1. Push your repository to GitHub.
2. Connect the repository to Vercel.
3. Add the following environment variables in **Vercel → Project Settings → Environment Variables**:

```env
NEXT_PUBLIC_TINA_CLIENT_ID=your-client-id
TINA_TOKEN=your-token
NEXT_PUBLIC_TINA_BRANCH=main
```

4. Click **Deploy** — your site will be live in minutes!

---

## 📦 Build for Production

To generate a production build locally:

```bash
pnpm build
```

---

## 🙏 Thanks

Big thanks to the incredible [TinaCMS](https://tina.io) team for creating a powerful content editing experience and an open-source foundation for modern content management!

---
