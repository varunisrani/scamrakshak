# ScamRakshak

ScamRakshak is a front-end concept for a security product, presenting biometric access, monitoring, integrations, pricing, and contact experiences.

## Core features

- Responsive product landing page with animated security-themed sections.
- Interactive demonstration dashboards for integrations, user groups, monitoring, and biometric access.
- Separate pricing, contact, and advanced product pages through the Next.js App Router.
- Reusable Radix UI-based controls styled with Tailwind CSS.

## Technology stack

- Next.js 14 and React 18
- JavaScript and JSX
- Tailwind CSS, Radix UI, and Lucide icons
- Framer Motion

## Prerequisites

- Node.js 20 or newer
- npm (a `package-lock.json` is included)

## Local setup

```bash
git clone https://github.com/varunisrani/scamrakshak.git
cd scamrakshak
npm ci
npm run dev
```

The development server is available at `http://localhost:3000` by default.

To create and serve a production build:

```bash
npm run build
npm run start
```

The manifest also defines `npm run lint`.

## Configuration

The current source does not read any environment variables. All displayed data and interactions are implemented in the client-side components.

## Project structure

```text
src/app/          App Router pages, layout, fonts, and global styles
src/components/   Product sections, dashboards, header/footer, and UI primitives
src/hooks/        Shared toast hook
src/lib/          Styling utilities
```

## Status and limitations

This repository is a UI prototype rather than a deployed security service. The named integrations, monitoring events, biometric controls, and user groups are demonstrations backed by component state; there is no authentication, persistence, external integration, or security-scanning backend in this codebase.