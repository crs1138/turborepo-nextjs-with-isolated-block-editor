# PoC NextJS Using Isolated Block Editor

This is a Turborepo with the minimal configuration to try out the possibility of using an isolated block editor (known from the WP/Gutenberg project) within an NextJS application.

## Using this example

1. Clone the repo to your local dev environment
2. Change to the folder 

    ```sh
    cd turborepo-nextjs-with-isolated-block-editor`.
    ```

3. Run the following command to install all dependencies:

    ```sh
    pnpm install
    ```

4. Start the local dev server

    ```sh
    pnpm dev
    ```

## What's inside?

This Turborepo includes the following packages/apps:

### Apps and Packages

- `altas-editor`: a [Next.js](https://nextjs.org/) app
- `@repo/block-editor`: a react component library using the [isolated-block-editor](https://github.com/Automattic/isolated-block-editor/)
- `@repo/eslint-config`: `eslint` configurations (includes `eslint-config-next` and `eslint-config-prettier`)
- `@repo/typescript-config`: `tsconfig.json`s used throughout the monorepo

### Utilities

This Turborepo has some additional tools already setup for you:

- [TypeScript](https://www.typescriptlang.org/) for static type checking
- [ESLint](https://eslint.org/) for code linting
- [Prettier](https://prettier.io) for code formatting
