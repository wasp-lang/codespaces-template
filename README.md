# A Wasp template on Github Codespaces

<img src="./src/client/waspLogo.png" width='100px'/>

This is a [Wasp](https://wasp-lang.dev/) template configured for developer environments on [Github Codespaces](https://github.com/features/codespaces).

* Look for the `main.wasp` file to see how a Wasp App is built!
* The `src` directory contains your client and server files that you edit and reference within `main.wasp`
* Wasp uses this information to put all the pieces of your app together, so you can focus on the important stuff (you can see what Wasp builds in `.wasp/out`, but **don't** edit these files 🐝)!

Visit [wasp-lang.dev](https://wasp-lang.dev/docs/tutorials/todo-app) to go through our TODO app tutorial.

## Next Steps

Click on "Use this template" and then "Open in a codepsace" to get started with your own project.

When the Codespace is ready, you can start the development server by running:
```
wasp start
```
## Add Github Codespaces to an existing project

To get started with Wasp on Github Codespaces, add the `.devcontainer` folder which contains the configuration for Github Codespaces. To learn more, please see the [Getting Started](https://docs.github.com/en/codespaces/getting-started/quickstart) documentation.

## Wasp CLI Commands

* `wasp start` starts development environment
* `wasp db migrate-dev` to run database migrations
* `wasp db studio` to open Prisma Studio and view your database models
