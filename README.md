# 🔐 Spring Boot - Authentification & Autorisation par Rôles

Un mini-projet Spring Boot démontrant la mise en place d'un système complet d'authentification et d'autorisation basé sur les rôles, avec une interface web Thymeleaf.

---

## 📋 Description

Ce projet illustre les bases de la sécurité dans les applications Spring, notamment :

- La gestion des utilisateurs en mémoire via `InMemoryUserDetailsManager`
- La protection des routes selon les rôles (`ADMIN`, `USER`)
- Une page de connexion personnalisée avec Thymeleaf
- Des dashboards distincts pour chaque rôle

---

## 🛠️ Technologies utilisées

| Technologie        | Version     |
|--------------------|-------------|
| Java               | 21         |
| Spring Boot        | 4.0.4         |
| Spring Security    | 6.x         |
| Thymeleaf          | 3.x         |
| Maven              | 3.x         |

---

## 🏗️ Structure du projet

<img width="313" height="779" alt="structure" src="https://github.com/user-attachments/assets/5636993e-ffec-4b64-ac0c-2794b2927adf" />


---

## Video d'affichage


https://github.com/user-attachments/assets/04d5a3d3-4203-4f89-97b3-fcb2e71f9498



---

## 🔒 Protection des routes

| Route              | Accès autorisé  |
|--------------------|-----------------|
| `/login`           | Tout le monde   |
| `/admin/**`        | ADMIN seulement |
| `/user/**`         | USER seulement  |
| `/`                | Authentifié     |

---


## 🖥️ Pages de l'application

- **`/login`** — Page de connexion personnalisée
- **`/admin/dashboard`** — Tableau de bord réservé à l'administrateur
- **`/user/dashboard`** — Tableau de bord réservé à l'utilisateur

---



## 📚 Concepts illustrés

- **Authentication** — Vérification de l'identité d'un utilisateur
- **Authorization** — Contrôle d'accès aux ressources selon le rôle
- **InMemoryUserDetailsManager** — Gestion des utilisateurs sans base de données
- **SecurityFilterChain** — Chaîne de filtres Spring Security
- **Thymeleaf Security** — Intégration de la sécurité dans les templates

---

