```markdown
# AGENTS.md File Guidelines

These guidelines are designed to ensure high-quality, maintainable, and robust AI coding agent development within the AGENTS repository. Adherence to these principles is mandatory for all development activities.

## 1. DRY (Don't Repeat Yourself)

*   All code should be modular and reusable.
*   Avoid duplicating logic across multiple files.
*   Leverage existing components and libraries where appropriate.
*   Implement clear separation of concerns.

## 2. KISS (Keep It Simple, Stupid)

*   Strive for the simplest solution that meets the requirements.
*   Minimize complexity; avoid over-engineering.
*   Focus on essential functionality; avoid unnecessary features.
*   Code should be easy to understand and debug.

## 3. SOLID Principles

*   **Single Responsibility Principle:** Each class/component should have one, and only one, reason to change.
*   **Open/Closed Principle:** The system should be open for extension but closed for modification.
*   **Liskov Substitution Principle:**  Subclasses should be able to replace their base classes without altering the correctness of the program.
*   **Interface Segregation Principle:** Client code should not need methods from interfaces they do not use.
*   **Dependency Inversion Principle:**  High-level modules (interfaces/abstract classes) should be replaced by low-level modules (concrete implementations).

## 4. YAGNI (You Aren't Gonna Need It)

*   Implement only what is absolutely necessary for the current task.
*   Avoid premature optimization; focus on core functionality.
*   Refactor code iteratively; only add features when they are required.

## 5. Testing & Coverage

*   **Unit Tests:** 80% of code must be covered by unit tests.
*   All functions, classes, and methods must be individually tested.
*   Test cases should cover edge cases and potential failure scenarios.
*   Use a consistent testing framework (specified in the `tests/` directory).

## 6. File Size & Length

*   Each file must be no more than 180 lines of code.
*   Code should be well-formatted and readable.
*   Use meaningful variable and function names.

## 7. Code Structure & Organization

*   Modules should have a clear purpose and logically grouped components.
*   Use descriptive comments to explain complex logic.
*   Maintain a consistent coding style (e.g., using a linter).

## 8. API Design

*   All APIs should be well-defined and documented.
*   Use clear naming conventions.
*   Provide proper error handling.

## 9. Data Handling

*   Data should be handled responsibly and securely.
*   Avoid storing sensitive data unnecessarily.
*   Use appropriate data structures for efficiency.

## 10. Dependency Management

*   Dependencies should be managed and versioned.
*   Use a dependency management system (e.g., Poetry, Pipenv).

## 11.  Logging & Monitoring

*   Log all significant events and errors.
*   Implement basic monitoring for key metrics.

## 12.  Code Review Process

*   All code changes must undergo a mandatory code review before merging.
*   Code reviews should focus on adherence to the principles outlined here.

## 13.  Documentation

*   Provide clear and concise documentation for each component and function.
*   Include API documentation as needed.
```