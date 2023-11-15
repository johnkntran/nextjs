# Next.js Tutorial

This is how I did the [Next.js Tutorial](https://nextjs.org/learn/foundations/from-react-to-nextjs/getting-started-with-nextjs).

## Setup
- Open the [devcontainer.json](./.devcontainer/devcontainer.json) file and update the `"name"` field to the name of your project. Also update the `"postCreateCommand"` hook to use your Git username and email if needed.
- In VS Code, ensure you have the **Dev Containers** extension (`ms-vscode-remote.remote-containers`) installed and enabled.
- Hit `Command (CTRL) + Shift + P` to open the Command Palette and type `> Dev Containers: Reopen in Container`, then hit "OK".
- Once the container is up and running, open a terminal inside the container and run `npm install`.
- After the Javascript dependencies have been installed, run `npm run dev` to serve the Next.js app.
- Navigate to [http://localhost:5173](http://127.0.0.1:5173) to view the application.
