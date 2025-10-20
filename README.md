# SmartUrine Dashboard

This is a user-friendly dashboard to display urine test results and health insights for caregivers, doctors, and patients. It provides at-a-glance health indicators, trend charts, and detailed result tables using simulated data.

This project is a React application built with TypeScript and styled with Tailwind CSS. It is configured to run out-of-the-box in cloud development environments like CodeSandbox.

## How to Run This Project on CodeSandbox.io

CodeSandbox provides a cloud-based IDE that allows you to run this project directly in your browser without any local setup. The recommended way is to import it from a GitHub repository.

---

### Method 1: Importing from GitHub (Recommended)

This is the fastest and easiest way to get started. It automatically configures the entire project for you.

#### Prerequisites
- You must have a GitHub account.
- The entire project, including configuration files (`package.json`, `vite.config.ts`, etc.), must be pushed to a GitHub repository.

#### Steps
1.  **Navigate to CodeSandbox**: Go to [codesandbox.io](https://codesandbox.io) and log in.

2.  **Import Repository**: On your dashboard, click the **"Import repository"** button.

3.  **Provide the URL**: Paste the URL of your GitHub repository (e.g., `https://github.com/your-username/smarturine-dashboard`) into the input field and click **"Import"**.

4.  **Automatic Setup**: CodeSandbox will now:
    *   Clone your repository.
    *   Read the `package.json` file.
    *   Automatically install all required dependencies (`npm install`).
    *   Automatically run the `dev` script (`npm run dev`) to start the Vite server.

5.  **View the Application**: The application will start, and you will see the **SmartUrine Dashboard login page** appear in the preview window on the right side of the editor.

---

### Method 2: Manual Setup (Alternative)

If you do not want to use GitHub, you can set up the project manually from a template.

#### Steps
1.  **Create a New Sandbox**:
    *   Navigate to [codesandbox.io](https://codesandbox.io).
    *   Click **"Create Sandbox"**.
    *   Select the official **Vite** template, then choose **React + TypeScript**.

2.  **Clean Up the Template**: Delete the default files and folders from the template's `src` folder (like `App.css`, `index.css`, `assets`, etc.).

3.  **Copy Project Files**:
    *   **`package.json`**: Open the `package.json` file in the sandbox and replace its entire content with the content of this project's `package.json` file. CodeSandbox will automatically start installing the new dependencies.
    *   **`vite.config.ts`**, **`tsconfig.json`**, **`tsconfig.node.json`**: Create or overwrite these files in the root directory with the content from this project.
    *   **`index.html`**: Replace the content of the `index.html` file in the root directory.
    *   **`src` folder**: Re-create the folder structure of this project (`src/components/`). Then, copy the content of every `.ts` and `.tsx` file from your local project into the corresponding files in the CodeSandbox editor.

4.  **Run the Application**:
    *   The Vite server should start automatically after the dependencies are installed.
    *   If it doesn't, you can open the built-in **Terminal** and manually run `npm run dev`.
    *   The dashboard will appear in the preview window.

This setup allows you to develop, test, and share the project entirely from your browser.
