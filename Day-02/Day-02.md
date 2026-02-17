Set up and run the app locally

Follow the Adobe App Builder "Get started" guide: https://developer.adobe.com/app-builder/docs/get_started/

Prerequisites
- Node.js v18+ (recommended — can be managed with `nvm`)
- npm (or compatible package manager)
- An Adobe account with organization access (required to create App Builder projects)

Install the Adobe CLI
Run:

```bash
npm install -g @adobe/aio-cli
```

Log in with Adobe
Run:

```bash
aio login
```

This opens a browser for authentication. Sign in and choose the organization you want to use. After successful login you can close the browser tab.

Create a project
You can create a project either via the Adobe Console or the `aio` CLI.

Adobe Console (web)
- Go to https://developer.adobe.com/console/
- Click "Create project" and choose a suitable App Builder template.

aio CLI
Run:

```bash
aio app init --standalone-app
```

- The CLI requires you to be logged in (`aio login`).
- When prompted, select an existing project or press `+` to create a new one.
- If creating new, confirm prompts (project name, title, description).
- You may be asked to overwrite `.vscode/launch.json` — type `Y` to accept or `N` to skip.
- The CLI will list available features (all selected by default); toggle options with the spacebar and press Enter to proceed.

Run the project locally
- Start local development server:

```bash
aio app dev
```

- To run the app in the configured workspace:

```bash
aio app run
```

- To view the current organization, project, and workspace:

```bash
aio where
```

The `aio app dev` command prints a local URL (for example, `http://localhost:PORT`). Open that URL in your browser to view the app.

Congratulations — your app is running locally.
