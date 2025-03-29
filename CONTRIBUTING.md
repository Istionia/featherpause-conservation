# Contributing to FeatherPause Conservation

Thank you for your interest in contributing to the FeatherPause Conservation package! This package contains open-source conservation tools for ethical birding, including GPS obfuscation for endangered species and conservation status indicators.

## Development Process

This repository is a public mirror of the conservation package maintained in the private FeatherPause main repository. Changes to this package are synchronized from the private repository through GitHub Actions.

## How to Contribute

1. **Fork the repository**
   - Create a fork of this repository to your own GitHub account

2. **Clone your fork**
   ```
   git clone https://github.com/YOUR-USERNAME/featherpause-conservation.git
   cd featherpause-conservation
   ```

3. **Install dependencies**
   ```
   npm install
   # or
   yarn install
   ```

4. **Create a branch for your changes**
   ```
   git checkout -b feature/your-feature-name
   ```

5. **Make your changes**
   - Write tests for new functionality
   - Ensure your code follows the project's style guidelines

6. **Build and test your changes**
   ```
   npm run build
   npm test
   # or
   yarn build
   yarn test
   ```

7. **Commit your changes**
   ```
   git commit -m "Description of your changes"
   ```

8. **Push to your fork**
   ```
   git push origin feature/your-feature-name
   ```

9. **Submit a pull request**
   - Create a PR from your fork to the main repository
   - Describe your changes and why they should be included

## Code Style

- Follow TypeScript best practices
- Use meaningful variable and function names
- Write comments for complex logic
- Include JSDoc comments for public APIs

## License

By contributing to this project, you agree that your contributions will be licensed under the project's AGPL-3.0 License. 