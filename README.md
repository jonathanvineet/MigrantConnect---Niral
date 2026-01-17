# MigrantConnect-Niral

MigrantConnect is an Aadhaar-enabled platform for migrant workers in Tamil Nadu, offering secure registration, job tracking, wage transparency, access to benefits, and real-time grievance redressal.

## Prerequisites

- Node.js 18 or newer
- pnpm (recommended) or npm/yarn

Install pnpm (if you don't have it):

```bash
npm install -g pnpm
```

## Install dependencies

Using pnpm (recommended):

```bash
pnpm install
```

Or using npm:

```bash
npm install
```

After installing dependencies you may want to disable Next.js telemetry:

```bash
npx next telemetry disable
```

## Environment

If your project needs environment variables, create a local file:

```bash
cp .env.example .env.local
# then edit .env.local as needed
```

## Development

Start the development server:

```bash
pnpm dev
# or
npm run dev
```

Open http://localhost:3000 in your browser.

## Build and Production

Build the app:

```bash
pnpm build
# or
npm run build
```

Start the production server (after building):

```bash
pnpm start
# or
npm start
```

## Useful scripts

- `pnpm dev` — run Next.js in development mode with fast refresh
- `pnpm build` — build for production
- `pnpm start` — run built production server
- `pnpm lint` — run linting (if configured)

If you run into dependency peer errors with npm, try using `pnpm` which generally handles peers better.

---

If you'd like, I can also add an example `.env.example` or update the README with developer notes specific to this project.

