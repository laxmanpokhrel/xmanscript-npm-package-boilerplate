
[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli/)

# NPM Package Template

Use this template to quickly set up and release npm packages with ease. This template is configured to automate the release process using semantic-release and provides commitizen support for standardized commit messages.

## Getting Started

To get started with this template, follow these steps:

1. Click the "Use this template" button at the top of the repository to create a new repository based on this template.

2. Clone the newly created repository to your local machine:

   ```bash
   git clone https://github.com/your-username/your-package.git
   ```

3. Change into the project directory:

   ```bash
   cd your-package
   ```

4. Install the project dependencies:

   ```bash
   yarn install
   ```

### Initializing Husky

Husky is a tool that helps you set up Git hooks easily. These hooks can run checks or tasks before you commit or push changes. This template uses Husky to enforce commit message conventions.

To initialize Husky, run the following command:

```bash
npx husky-init && yarn
```

### Initializing Commitizen

Commitizen is a tool that helps you write consistent and conventional commit messages. It prompts you to fill in the required commit message fields, ensuring your commits are well-structured.

To initialize Commitizen with this template, run the following command:

```bash
npx commitizen init cz-conventional-changelog --yarn --dev --exact --force
```

## Development Workflow

Once you have initialized Husky and Commitizen, you can start developing your package. Here are some key commands and tools available in this template:

- **Linting and Code Formatting**: This template uses ESLint and Prettier for linting and code formatting. You can run linting checks using:

  ```bash
  yarn lint
  ```

- **Testing**: Jest is set up for testing. You can run your tests using:

  ```bash
  yarn test
  ```

- **Automatic Type Checking**: TypeScript is used for type checking. You can run type checking using:

  ```bash
  yarn type-check
  ```

- **Automatic Release**: Semantic-release is configured to automatically manage versioning and package releases. When you make commits following the conventional commit message format, semantic-release will determine the version number and publish your package to npm automatically.

- **Development Server**: If you are developing a web-based project, you can use Nodemon to automatically restart your development server on code changes. Customize the Nodemon configuration in `nodemon.json`.

- **Custom TypeScript Configuration**: You can modify the TypeScript configuration in `tsconfig.json` to suit your project's needs.

## Contributing

We welcome contributions to this project. If you have any bug fixes, feature additions, or improvements, please open an issue or submit a pull request. Make sure to follow the commit message conventions for your pull requests.

## License

This project is licensed under the MIT License.
## Acknowledgments

- [Semantic Release](https://semantic-release.gitbook.io/semantic-release/)
- [Commitizen](http://commitizen.github.io/cz-cli/)
- [Husky](https://typicode.github.io/husky/)
- [ESLint](https://eslint.org/)
- [Prettier](https://prettier.io/)
- [Jest](https://jestjs.io/)
- [TypeScript](https://www.typescriptlang.org/)

## Support

meIf you have any questions or need assistance, please feel free to reach out through the GitHub Issues section of this repository.

Happy coding! 🚀