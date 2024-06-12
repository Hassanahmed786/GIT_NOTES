# GIT_NOTES

## Commands Table

| Command | Description |
|---------|-------------|
| `git config --global user.name "Your Name"` | Set the global username for Git commits. |
| `git config --global user.email "your-email@example.com"` | Set the global email for Git commits. |
| `git init` | Initialize a new Git repository. |
| `git clone <repo-url>` | Clone an existing repository. |
| `git status` | Show the working tree status. |
| `git add <file>` | Add file contents to the index. |
| `git commit -m "message"` | Record changes to the repository with a message. |
| `git push` | Update remote refs along with associated objects. |
| `git pull` | Fetch from and integrate with another repository. |
| `git branch` | List branches in the repository. |
| `git branch <branch-name>` | Create a new branch. |
| `git checkout <branch-name>` | Switch to the specified branch. |
| `git checkout -b <branch-name>` | Create a new branch and switch to it. |
| `git merge <branch-name>` | Merge specified branch into the current branch. |
| `git branch -d <branch-name>` | Delete the specified branch. |
| `git remote add upstream <repo-url>` | Add a new remote called "upstream". |
| `git fetch upstream` | Fetch updates from the upstream repository. |
| `git checkout main` | Switch to the main branch. |
| `git merge upstream/main` | Merge updates from the upstream main branch. |
| `git push origin <branch-name>` | Push a branch to the remote repository. |



## React Terminal Commands

| Command | Description |
|---------|-------------|
| `npx create-react-app my-app` | Create a new React application named "my-app". |
| `cd my-app` | Change directory to the "my-app" folder. |
| `npm start` | Start the development server and open the React application in the browser. |
| `npm run build` | Create a production build of the React application. |
| `npm test` | Run tests using the testing framework configured with Create React App. |
| `npm install` | Install all the dependencies listed in `package.json`. |
| `npm install <package-name>` | Install a specific npm package and add it to the dependencies in `package.json`. |
| `npm install --save-dev <package-name>` | Install a specific npm package and add it to the devDependencies in `package.json`. |
| `npm uninstall <package-name>` | Uninstall a specific npm package and remove it from `package.json`. |
| `npm run eject` | Eject the configuration files from Create React App to customize them directly (use with caution). |
| `npm run lint` | Run linter to check for code style issues. |
| `npm run lint:fix` | Run linter and automatically fix code style issues. |
| `npm run format` | Format the code using a tool like Prettier. |
| `npm run test -- --coverage` | Run tests and generate a code coverage report. |
| `npm run <custom-script>` | Run a custom script defined in the `scripts` section of `package.json`. |

## Git Commands for React Projects

| Command | Description |
|---------|-------------|
| `git init` | Initialize a new Git repository in the React project. |
| `git clone <repo-url>` | Clone an existing React project repository. |
| `git status` | Show the status of changes in the working directory. |
| `git add .` | Stage all changes in the working directory for the next commit. |
| `git commit -m "message"` | Commit the staged changes with a message. |
| `git push` | Push the local commits to the remote repository. |
| `git pull` | Fetch and merge changes from the remote repository. |
| `git branch` | List all the branches in the repository. |
| `git checkout -b <branch-name>` | Create a new branch and switch to it. |
| `git checkout <branch-name>` | Switch to an existing branch. |
| `git merge <branch-name>` | Merge a branch into the current branch. |
| `git branch -d <branch-name>` | Delete a local branch. |
| `git remote add origin <repo-url>` | Add a remote repository. |
| `git fetch` | Download objects and refs from another repository. |
| `git reset --hard HEAD` | Discard all changes and reset the working directory to the last commit. |

## React-Specific Commands

| Command | Description |
|---------|-------------|
| `npx create-react-app .` | Create a new React app in the current directory. |
| `npx react-scripts start` | Start the development server (used internally by `npm start`). |
| `npx react-scripts build` | Create a production build of the app (used internally by `npm run build`). |
| `npx react-scripts test` | Run tests (used internally by `npm test`). |
| `npx react-scripts eject` | Eject the configuration (used internally by `npm run eject`). |



## Vite + React Terminal Commands

| Command | Description |
|---------|-------------|
| `npm init vite@latest my-app -- --template react` | Create a new Vite + React application named "my-app". |
| `cd my-app` | Change directory to the "my-app" folder. |
| `npm install` | Install all the dependencies listed in `package.json`. |
| `npm run dev` | Start the development server and open the Vite + React application in the browser. |
| `npm run build` | Create a production build of the Vite + React application. |
| `npm run serve` | Serve the production build locally. |
| `npm install <package-name>` | Install a specific npm package and add it to the dependencies in `package.json`. |
| `npm install --save-dev <package-name>` | Install a specific npm package and add it to the devDependencies in `package.json`. |
| `npm uninstall <package-name>` | Uninstall a specific npm package and remove it from `package.json`. |
| `npx vite` | Run Vite commands directly. |
| `npx vite build` | Manually create a production build of the app. |
| `npx vite preview` | Preview the production build locally. |

## Git Commands for Vite + React Projects

| Command | Description |
|---------|-------------|
| `git init` | Initialize a new Git repository in the Vite + React project. |
| `git clone <repo-url>` | Clone an existing Vite + React project repository. |
| `git status` | Show the status of changes in the working directory. |
| `git add .` | Stage all changes in the working directory for the next commit. |
| `git commit -m "message"` | Commit the staged changes with a message. |
| `git push` | Push the local commits to the remote repository. |
| `git pull` | Fetch and merge changes from the remote repository. |
| `git branch` | List all the branches in the repository. |
| `git checkout -b <branch-name>` | Create a new branch and switch to it. |
| `git checkout <branch-name>` | Switch to an existing branch. |
| `git merge <branch-name>` | Merge a branch into the current branch. |
| `git branch -d <branch-name>` | Delete a local branch. |
| `git remote add origin <repo-url>` | Add a remote repository. |
| `git fetch` | Download objects and refs from another repository. |
| `git reset --hard HEAD` | Discard all changes and reset the working directory to the last commit. |

## Custom Scripts

| Command | Description |
|---------|-------------|
| `npm run lint` | Run linter to check for code style issues (if configured). |
| `npm run lint:fix` | Run linter and automatically fix code style issues (if configured). |
| `npm run format` | Format the code using a tool like Prettier (if configured). |
| `npm run test` | Run tests using the testing framework configured with Vite. |
| `npm run test:coverage` | Run tests and generate a code coverage report (if configured). |
| `npm run <custom-script>` | Run a custom script defined in the `scripts` section of `package.json`. |


