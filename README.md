# Vulnerable Web Playground

Projet de portfolio pour apprendre et comprendre les vulnerabilites web (OWASP Top 10).

Application intentionnellement vulnerable pour fins educatives uniquement.

## Status

EN COURS DE DEVELOPPEMENT

## Architecture

```
vulnerable-web-playground/
├── backend/
│   ├── src/
│   │   ├── routes/
│   │   │   ├── auth.js
│   │   │   ├── users.js
│   │   │   ├── comments.js
│   │   │   └── admin.js
│   │   ├── middleware/
│   │   ├── server.js
│   │   └── db.js
│   ├── package.json
│   └── Dockerfile
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── styles/
│   │   └── App.tsx
│   ├── package.json
│   └── Dockerfile
├── docs/
│   ├── vulnerabilities.md
│   ├── exploitation-guide.md
│   ├── fixes.md
│   └── images/
├── test-payloads/
├── docker-compose.yml
└── README.md
```

## Vulnerabilites a implementer

- SQL Injection
- Authentification cassee
- Exposition de donnees
- XXE/Injection XML
- Broken Access Control (IDOR)
- Mauvaise configuration de securite
- XSS (Cross-Site Scripting)
- Deserialisation dangereuse
- CSRF
- Dependances vulnerables

## Commandes

```bash
docker-compose up
```

## Note de securite

INTENTIONNELLEMENT VULNERABLE - Usage local uniquement.
