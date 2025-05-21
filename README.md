# ReactDevOps
https://dev.azure.com/williamnanfack/GitDevOpsVsCode/_apis/build/status/WilliamNG01.ReactDevOps?branchName=main

[![Build Status](https://dev.azure.com/williamnanfack/GitDevOpsVsCode/_apis/build/status/WilliamNG01.ReactDevOps?branchName=main)](https://dev.azure.com/williamnanfack/GitDevOpsVsCode/_build/latest?definitionId=3&branchName=main)

Structure du projet
src/
├── assets/              # Images, icônes, fichiers statiques
├── components/          # Composants UI réutilisables (Button, Modal, etc.)
├── features/            # Modules fonctionnels (domaines métiers)
│   ├── appointments/    # Rendez-vous
│   │   ├── components/  # Composants spécifiques aux rendez-vous
│   │   ├── pages/       # Pages vues (Liste, Détail, Création)
│   │   ├── api.ts       # Appels API liés
│   │   ├── types.ts     # Types et interfaces
│   │   └── slice.ts     # État local ou Redux (si applicable)
│   ├── patients/
│   ├── doctors/
│   ├── documents/
│   └── billing/
├── hooks/               # Custom hooks (useFetch, useAuth, etc.)
├── layout/              # Layouts globaux (Sidebar, Header, etc.)
├── pages/               # Routing principal (si React Router ou Next.js)
├── router/              # Définition des routes (React Router, TanStack Router…)
├── services/            # Services partagés : Auth, API, DateService, etc.
├── store/               # Gestion de l'état global (Zustand / Redux)
├── utils/               # Fonctions utilitaires génériques
├── i18n/                # Fichiers de traduction
├── theme/               # Thèmes Tailwind, Chakra, MUI, etc.
└── index.tsx            # Point d’entrée React

