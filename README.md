# Arcade Hub — Vercel Ready

This is a self-contained static browser arcade. It does not use a database, Prisma, server runtime, or environment variables. Browser-side game data can use localStorage.

## Deploy with GitHub + Vercel

1. Create a new GitHub repository.
2. Upload the **contents of this ZIP directly into the repository root**.
3. Confirm `index.html`, `package.json`, `vercel.json`, `.gitignore`, and `README.md` are visible at the repository root.
4. In Vercel, import that GitHub repository.
5. Do not add environment variables. Vercel can deploy this as a static site; no build command is required.

The important file is `index.html` at the repository root. Do not place it inside another folder.
