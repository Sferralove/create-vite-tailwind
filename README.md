# Create Vite Tailwind

Starter template per progetti React con Vite e Tailwind CSS.

Il repository fornisce una base frontend gia pronta con una struttura cartelle iniziale, alias Vite configurati e un set di dipendenze comuni per costruire rapidamente applicazioni React moderne.

## Stack incluso

- React 19
- Vite 7
- Tailwind CSS 4
- React Router 7
- Redux 5 e React Redux 9
- Axios
- Headless UI
- Radix UI
- Lucide React e React Icons
- Utility per classi Tailwind come `clsx`, `tailwind-merge` e `class-variance-authority`

## Struttura iniziale

La cartella `src` e gia predisposta con directory dedicate a:

- `assets`
- `components`
- `context`
- `pages`
- `services`
- `utils`
- `views`

Sono inoltre configurati gli alias import in [vite.config.js](./vite.config.js), ad esempio `@/`, `@components`, `@assets` e simili.

## Prerequisiti

- Node.js 20.19+ oppure 22.12+
- npm 10+

## Installazione

Clona il repository e installa le dipendenze:

```bash
git clone https://github.com/Sferralove/create-vite-tailwind.git
cd create-vite-tailwind
npm install
```

## Script disponibili

Avvio del server di sviluppo:

```bash
npm run dev
```

Build di produzione:

```bash
npm run build
```

Preview locale della build:

```bash
npm run preview
```

Nota: l'indirizzo locale del dev server viene assegnato da Vite al momento dell'avvio e puo variare in base alla configurazione o alla porta disponibile.

## Note

- Il progetto usa PostCSS con il plugin `@tailwindcss/postcss`, richiesto dal setup Tailwind CSS 4.
- Sono presenti `.htaccess` e `Web.config` per facilitare il fallback delle route SPA in deploy su Apache o IIS.
- Il file `components.json` prepara il progetto all'uso con componenti in stile `shadcn/ui`.

## Autore

- Angelo Sferra
- Contatti: sferra.angelo@gmail.com
