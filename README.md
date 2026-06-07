# Multitenant E-Commerce Application

## Scaffolding
- Use `bunx create-next-app@15.2.4` to scaffold the project with the following options.
    - What is your project named? _multitenant-ecommerce_
    - Would you like to use TypeScript? _Yes_
    - Would you like to use ESLint? _Yes_
    - Would you like to use Tailwind CSS? _Yes_
    - Would you like your code inside a `src/` directory? _Yes_
    - Would you like to use App Router? (recommended) _Yes_
    - Would you like to use Turbopack for `next dev`? _No_
    - Would you like to customize the import alias (`@/*` by default)? _No_

## Install shadcn/ui
- Check shadcn/ui version that can be used with the project via `bunx --bun shadcn@latest --version`
- Use the following command to use shadcn/ui in the project
    ```
    bunx --bun shadcn@2.4.0-canary.17 init
    ```
- Select the following options afterwards.
    - Which color would you like to use as the base color? _Neutral_
- This will create a new directory named `lib` inside the `/src` directory.
- You can add the components using the following `add` command.
    ```
    bunx --bun shadcn@2.4.0-canary.17 add button
    ```
- Instead of adding one by one, you can use the following command to add them all at once.
    ```
    bunx --bun shadcn@2.4.0-canary.17 add --all
    ```

## Run the Application
- Use `bun run dev` to run the application.
