# Contributing to This Project

Thank you for your interest in contributing! 🎉 This project is open to improvements and collaboration. Please follow the guidelines below to ensure a smooth contribution process.

## 🚀 How to Contribute

1. **Fork** the repository.
2. **Clone** your fork:
   ```sh
   git clone https://github.com/your-username/repository-name.git
   ```
3. **Create a new branch** for your changes:
   ```sh
   git checkout -b feature-or-bugfix-name
   ```
4. **Make your changes** and commit them:
   ```sh
   git commit -m "Add a meaningful commit message"
   ```
5. **Push to your fork**:
   ```sh
   git push origin feature-or-bugfix-name
   ```
6. **Create a Pull Request (PR)** on GitHub and provide a clear description of your changes.

## 📌 Contribution Guidelines

- Follow the [Code of Conduct](CODE_OF_CONDUCT.md) (if applicable).
- Keep pull requests **small and focused**.
- Write **clear commit messages** that explain the changes made.
- Document changes where necessary (e.g., update the README if applicable).
- Ensure **compatibility** with the project's existing setup.
- **Run tests** before submitting a PR, if applicable.

## 🛠 Issue Reporting

- **Search before posting**: Check if the issue has already been reported.
- **Provide detailed information**: Include steps to reproduce, screenshots (if applicable), and expected behavior.
- **Suggest possible fixes** if you have any ideas.
- Use **clear and concise titles** for new issues.

## 📝 Code Style & Standards

### The Basics

- Follow the existing **coding style**.
- Use **meaningful variable and function names**.
- Format code **consistently**.
- Write **self-explanatory** and **well-structured** code.

### Guidelines

Please follow [i18next best practices](https://www.i18next.com/principles/best-practices) for translations.

### Translation Files

Translation files are stored in the `locales` folder, with each language having its own directory.

Following [i18next principles](https://www.i18next.com/principles/translation-resolution), the translation resolution order is:

- **`common.json`**: Frequently used words, such as "Confirm" and "Cancel" on buttons.
- **`glossary.json`**: Key terms that should remain consistent across the app.
- **`translation.json`**: Main translation file for the app.
- **`validation.json`**: Contains validation messages (e.g., "Email address not valid").

### Translation Tools

- Use **VSCode** with [Sherlock](https://marketplace.visualstudio.com/items?itemName=inlang.vs-code-extension) for managing translations.
- Check **translation coverage** with [Lunaria Dashboard](./README.md#translation-coverage-with-lunaria-dashboard).
- Edit translation files directly using [Fink](https://fink.inlang.com/).

## 💬 Need Help?

If you have any questions or need guidance, feel free to:

- **Open an issue** on GitHub.
- Join the **discussions** section to engage with the community.

We appreciate your contributions! 🎉
