# Design System

### Initial projetc
```bash
npm init -y
npm i -D typescript
npx tsc --init
npx tsc
npm i tsup -D
```
### Build
```bash
cd ignite-design-system/packages/tokens
npm run build
```
### React
```bash
cd ignite-design-system/packages/react
npm init -y
npm i -D typescript
npm i tsup -D
npm i -D react @types/react @types/react-dom
npm i @radix-ui/react-avatar
npm i @radix-ui/react-checkbox
npm i phosphor-react
```
### Root
```bash
cd ignite-design-system
npm init -y
```
### Eslint
```bash
cd eslint-config
npm init -y
npm i -D eslint @rocketseat/eslint-config
```
### Stitches
```bash
npm i @stitches/react
```
### Storybook
```bash
cd ignite-design-system/packages
mkdir docs
npx sb init --builder=vite @storybook/builder-vite --type react --use-npm
npm i vite @vitejs/plugin-react -D
npm i react react-dom
touch vite.config.js
npm i @storybook/addon-a11y
```
### TurboRepo
```bash
npm i turbo@latest -D
```
### Deploy Github pages
```bash
npm i @storybook/storybook-deployer --save-dev
```
### Changesets
```bash
npm i @changesets/cli -D
npx changeset init
npm login
npm run changeset
npm run version-packages
npm run release
```
