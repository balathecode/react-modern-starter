![Node.js CI](https://github.com/thelinuxlich/react-modern-starter/workflows/Node.js%20CI/badge.svg)&nbsp;&nbsp;&nbsp;<a href="https://app.netlify.com/start/deploy?repository=https://github.com/thelinuxlich/react-modern-starter"><img src="https://www.netlify.com/img/deploy/button.svg"></a>

# react-modern-starter

- [React](https://reactjs.org/docs/getting-started.html) for rendering
- [React Router](https://reactrouter.com/web/guides/quick-start) for routing
- [Valtio](https://github.com/pmndrs/valtio) for state management
- [Tailwind CSS](https://tailwindcss.com) for UI
- [Vite](https://vitejs.dev/guide/) for bundling
- [uvu](https://github.com/lukeed/uvu) for testing
- [C8](https://github.com/bcoe/c8) for code coverage
- [Prettier-Standard](https://github.com/sheerun/prettier-standard) for formatting and linting
- [lint-staged](https://github.com/okonet/lint-staged) with precommit task for linting
- Github Actions CI preconfigured for running lint + tests
- SSR/SSG builtin
- Rudimentary autorouting based on directory convention(similar to Next.js)

## Setup

- Clone to local
- cd react-modern-starter
- yarn

## Tasks

- yarn dev (standard dev server)
- yarn format (format the codebase following prettier-standard rules)
- yarn dev:serve (SSR dev server)
- yarn build (bundle client and server(SSR) for production)
- yarn build:client (bundle client for production)
- yarn build:server (bundle server(SSR) for production)
- yarn generate (bundle static SSR/SSG)
- yarn serve (preview the production bundle(SSR))
- yarn test (run the test suite and generate code coverage)
