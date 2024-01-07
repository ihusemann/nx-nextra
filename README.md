# Nx with Nextra

Next.js throws an error when starting the server after build when using Nextra V2 and V3.

```
Error: > Couldn't find a `pages` directory. Please create one under the project root
```

## Install & Run

```bash
npm i

# development server works fine
npx nx serve docs

# production build fails during run:
npx nx build docs

npx nx run docs:serve:production
```

## Next.js w/o Nextra Runs Fine

```bash
npx nx build web

# runs prod server without error
npx nx run web:serve:production
```
