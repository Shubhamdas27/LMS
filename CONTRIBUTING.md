# Contributing to LMS (Learning Management System)

First off, thank you for considering contributing to our LMS project! 🎉

## 📋 Table of Contents

- [Code of Conduct](#code-of-conduct)
- [How Can I Contribute?](#how-can-i-contribute)
- [Development Setup](#development-setup)
- [Pull Request Process](#pull-request-process)
- [Style Guidelines](#style-guidelines)
- [Reporting Bugs](#reporting-bugs)
- [Suggesting Features](#suggesting-features)

## 📜 Code of Conduct

This project and everyone participating in it is governed by our Code of Conduct. By participating, you are expected to uphold this code.

## 🤝 How Can I Contribute?

### 🐛 Reporting Bugs

Before creating bug reports, please check the issue list as you might find out that you don't need to create one. When you are creating a bug report, please include as many details as possible:

- **Use a clear and descriptive title**
- **Describe the exact steps to reproduce the problem**
- **Provide specific examples to demonstrate the steps**
- **Describe the behavior you observed after following the steps**
- **Explain which behavior you expected to see instead and why**
- **Include screenshots if applicable**

### 💡 Suggesting Features

Feature suggestions are welcome! Please provide:

- **Use a clear and descriptive title**
- **Provide a step-by-step description of the suggested feature**
- **Provide specific examples to demonstrate the feature**
- **Describe the current behavior and explain which behavior you expected to see instead**
- **Explain why this feature would be useful**

### 🔧 Development Setup

1. **Fork the repository**
2. **Clone your fork**
   ```bash
   git clone https://github.com/YOUR_USERNAME/LMS.git
   cd LMS
   ```

3. **Backend Setup**
   ```bash
   cd backend
   npm install
   cp .env.example .env
   # Fill in your environment variables
   npm run dev
   ```

4. **Frontend Setup**
   ```bash
   cd frontend
   npm install
   cp .env.example .env
   # Fill in your environment variables
   npm run dev
   ```

### 🔄 Pull Request Process

1. **Create a new branch**
   ```bash
   git checkout -b feature/your-feature-name
   ```

2. **Make your changes**
   - Write clear, concise commit messages
   - Follow the coding style guidelines
   - Add tests if applicable
   - Update documentation if needed

3. **Test your changes**
   ```bash
   # Backend tests
   cd backend
   npm test

   # Frontend tests
   cd frontend
   npm test
   ```

4. **Commit your changes**
   ```bash
   git add .
   git commit -m "Add: your feature description"
   ```

5. **Push to your fork**
   ```bash
   git push origin feature/your-feature-name
   ```

6. **Create a Pull Request**
   - Use a clear and descriptive title
   - Describe what changes you made
   - Reference any related issues
   - Include screenshots if applicable

## 🎨 Style Guidelines

### JavaScript/React Code Style

- Use **ES6+** features
- Use **functional components** with hooks
- Follow **camelCase** for variables and functions
- Use **PascalCase** for components
- Use **meaningful variable names**
- Add **comments** for complex logic
- Keep functions **small and focused**

### CSS/Styling

- Use **Tailwind CSS** classes
- Follow **mobile-first** responsive design
- Use **semantic class names**
- Maintain **consistent spacing**

### Git Commit Messages

- Use the present tense ("Add feature" not "Added feature")
- Use the imperative mood ("Move cursor to..." not "Moves cursor to...")
- Limit the first line to 72 characters or less
- Reference issues and pull requests liberally after the first line

**Format:**
```
Type: Brief description

Detailed description if needed

Fixes #123
```

**Types:**
- `Add`: New features
- `Fix`: Bug fixes
- `Update`: Changes to existing features
- `Remove`: Removing features/code
- `Docs`: Documentation changes
- `Style`: Code style changes
- `Refactor`: Code refactoring
- `Test`: Adding or updating tests

## 🔍 Code Review Process

- All submissions require review before merging
- Maintainers will review PRs in a timely manner
- Address feedback promptly
- Be respectful in discussions

## 📝 Documentation

- Update README.md if needed
- Add inline comments for complex code
- Update API documentation if applicable
- Include examples for new features

## 🧪 Testing

- Write tests for new features
- Ensure all tests pass before submitting
- Include both unit and integration tests
- Test on different devices/browsers

## 📞 Getting Help

If you need help, you can:

- Open an issue with the "question" label
- Reach out to the maintainer: [Shubham Das](mailto:subhdas272004@gmail.com)
- Check existing issues and discussions

## 🙏 Recognition

Contributors will be recognized in:

- README.md contributors section
- Release notes for significant contributions
- Special mentions in project documentation

---

Thank you for contributing to making online education better! 🚀

**Happy Coding!** 💻✨
