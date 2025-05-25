# 🚀 Strapi + Next.js CMS Demo

Ce projet est une démonstration complète d'une stack headless composée de **Strapi** pour la gestion de contenu (CMS) et **Next.js** pour l'affichage côté client.

---

## 🧱 Stack utilisée

- 🧠 Strapi (v4, Node.js headless CMS)
- ⚛️ Next.js (13/14)
- 🎨 Tailwind CSS
- 🔗 Axios / GraphQL (pour requêtes)
- 🔒 Auth API (admin)
- ☁️ (optionnel) Déploiement Vercel + Railway/Render pour le CMS

---

## 🔧 Fonctionnalités prévues

- 📰 Création de contenu (articles, pages)
- 📡 Consommation d'API Strapi depuis Next.js (REST ou GraphQL)
- 🔍 Pages dynamiques en SSG/ISR/SSR
- 🎨 Design responsive avec Tailwind
- 📁 Uploads de fichiers/images depuis le back office
- 🛠️ Panel admin Strapi customisé

---

## 📁 Arborescence

```plaintext
strapi-nextjs-cms-demo/
├── backend/       ← Strapi CMS
│   ├── config/
│   ├── content-types/
│   └── ...
├── frontend/      ← Next.js site
│   ├── pages/
│   ├── components/
│   ├── lib/api.ts
│   └── ...
