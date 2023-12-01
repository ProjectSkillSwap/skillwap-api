# Coding Standards

These coding standards outline the conventions and best practices to be followed when contributing to the SkillSwap
project. Consistent coding standards help maintain code readability and collaboration across the development team.

## Language and Framework

* SkillSwap is developed using TypeScript and the Express.js framework.

## Code Formatting

* We use ESLint with Prettier, following
  the [eslint-config-universe](https://www.npmjs.com/package/eslint-config-universe) configuration for code formatting.
* Please refer to the [eslint-config-universe documentation](https://www.npmjs.com/package/eslint-config-universe) for
  detailed configuration settings.

## Variable Naming

* Follow camelCase for variable naming.

## Function and Method Naming

* Functions and methods should be named in camelCase.

## Comments and Documentation

* Code should be written in a way that does not require comments. We prioritize simplicity and readability over complex
  code that requires explanation.

## File Organization

* Folders should be named in underscore\_case.
* Files should be named in PascalCase.

## Error Handling

* All errors should be handled and propagated as HTTP Errors.

## Testing

* Tests are highly recommended but not mandatory for contributing.

## Version Control

* We follow the Conventional Commits specification for version control. Please refer
  to [Conventional Commits](https://www.conventionalcommits.org/) for guidelines on commit messages.

## Concurrency and Asynchronous Code

* Favor the use of async functions over `.then()` promises.

## Any Other Specific Requirements

* There are no additional specific requirements or guidelines for security practices, performance optimization,
  continuous integration, or external libraries and dependencies.

These coding standards aim to create a consistent and maintainable codebase. Contributors are encouraged to follow these
guidelines to ensure a seamless collaborative development process.
