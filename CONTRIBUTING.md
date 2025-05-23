# Contributing to Australian Comparison Platform

## Development Workflow

1. **Branch Naming Convention**
   - Feature branches: `feature/feature-name`
   - Bug fixes: `fix/bug-name`
   - Documentation: `docs/update-name`

2. **Commit Message Format**
   ```
   type(scope): description
   
   [optional body]
   [optional footer]
   ```
   Types: feat, fix, docs, style, refactor, test, chore

3. **Pull Request Process**
   - Create PR from your branch to main
   - Fill out the PR template
   - Request review from at least one team member
   - Ensure all CI checks pass
   - Address review comments
   - Get approval before merging

4. **Code Review Guidelines**
   - Check for code quality
   - Verify functionality
   - Ensure tests pass
   - Review documentation updates
   - Check for security issues

## Getting Started

1. Fork the repository
2. Clone your fork
3. Add upstream remote:
   ```bash
   git remote add upstream https://github.com/ozswitchh/australian-comparison-platform.git
   ```
4. Create your feature branch
5. Make your changes
6. Push to your fork
7. Create a pull request

## Development Setup

1. Install dependencies:
   ```bash
   npm install
   ```

2. Start development server:
   ```bash
   npm run dev
   ```

3. Run tests:
   ```bash
   npm test
   ```

## Communication

- Use GitHub Issues for bug reports and feature requests
- Use GitHub Discussions for general questions
- Use Pull Requests for code changes
- Tag relevant team members for reviews

## Code Style

- Follow the existing code style
- Use TypeScript for type safety
- Write meaningful comments
- Keep components small and focused
- Use proper error handling

## Testing

- Write tests for new features
- Update tests for modified features
- Ensure all tests pass before submitting PR

## Documentation

- Update README.md for major changes
- Document new features
- Update API documentation
- Add comments for complex logic 