<h1 align="center">Korepi</h1>

<p align="center">
  A versatile, feature-rich, and user-friendly tool designed to enhance your gaming experience.
</p>

<p align="center">
  <a href="https://discord.gg/cottonbuds"><img src="https://img.shields.io/discord/1069057220802781265?color=5865F2&logo=discord&logoColor=white" alt="Discord"></a>
</p>

---

## About Korepi

Korepi is a third-party toolkit designed to augment the gameplay experience with a wide range of functionalities, from Quality-of-Life improvements to powerful exploration aids.

---

## Quick Links

- **[Official Documentation](https://korepi.com/)**: The complete guide for installation, configuration, and feature usage.
- **[Backup Documentation](https://docs.korepi.com/)**: Use this if the main site is unavailable.
- **[Contributing Guide](./CONTRIBUTING.md)**: Learn how to contribute to the project.

---

## Local Development & Testing

Want to run the documentation locally for testing or to contribute? Follow the steps below.

<details>
<summary><strong>1. Prerequisites</strong></summary>

Before you begin, ensure you have the following software installed on your system:

-   **Node.js**: Version `18.x` or higher is required.
    -   To check your version, open a terminal and run: `node -v`
    -   If you don't have it, download it from the [official Node.js website](https://nodejs.org/).

-   **pnpm**: This project uses `pnpm` as its package manager for speed and efficiency.
    -   Install `pnpm` globally by running this command in your terminal: `npm install -g pnpm`

-   **Git**: Required for cloning the repository.
    -   Download from the [official Git website](https://git-scm.com/).
</details>

<details>
<summary><strong>2. Setup and Running</strong></summary>

With the prerequisites installed, you can now set up the project locally.

1.  **Clone the Repository**
    Open your terminal and clone the repository:
    ```bash
    git clone https://github.com/Korepi/korepi-docs.git
    ```
    *(Alternatively, use [GitHub Desktop](https://desktop.github.com/) for a graphical interface.)*

2.  **Navigate to the Project Directory**
    Change your current directory to the newly cloned folder:
    ```bash
    cd korepi-docs
    ```

3.  **Install Dependencies**
    Use `pnpm` to install all required packages from the lock file. This may take a few minutes.
    ```bash
    pnpm install
    ```

4.  **Run the Development Server**
    Start the local server, which will build the site and watch for file changes.
    ```bash
    pnpm run docs:dev
    ```
    Once running, your terminal will show a message like `VuePress dev server is listening at http://localhost:8080/`.

5.  **View the Documentation**
    Open your browser and go to `http://localhost:8080`. You will see the local version of the documentation site, which will auto-update as you save changes.
</details>

---

## Contributing

We welcome all contributions from the community! If you're looking to help, please read our **[Contributing Guide](./CONTRIBUTING.md)**. It contains information on submitting pull requests, reporting bugs, and our standards for content and style (including icon usage).

All community interactions are governed by our **[Code of Conduct](./CODE_OF_CONDUCT.md)**.

---

## Additional Resources

### Icon Selection

For selecting icons to use within the Korepi documentation or projects, explore the vast collection available at [FontAwesome](https://fontawesome.com/search).

---

## License

This project is licensed under the **[MIT License](./LICENSE)**.