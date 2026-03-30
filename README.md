# Imparare la lingua italiana

Progetto React + Vite pronto per GitHub Pages.

## Avvio locale

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
```

## Deploy su GitHub Pages

1. Crea un nuovo repository su GitHub.
2. Carica tutti i file di questo progetto nel repository.
3. Fai push su `main`.
4. In GitHub vai su **Settings > Pages**.
5. In **Build and deployment** scegli **GitHub Actions**.
6. Il file `.github/workflows/deploy.yml` farà il deploy automatico.

## Nota importante

Questo progetto usa `HashRouter`, così le pagine funzionano bene anche su GitHub Pages.
