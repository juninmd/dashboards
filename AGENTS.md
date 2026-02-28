```markdown
# AGENTS.md - AI Coding Agent Guidelines

These guidelines outline the principles and rules for development of AI coding agents within this repository.  Adherence to these principles is crucial for maintainability, scalability, and reliability.  All development must be productive, prioritizing code quality and test coverage.

**1. DRY (Don't Repeat Yourself)**

*   **Single Responsibility Principle:** Each agent module should have a single, well-defined purpose.
*   **Code Reuse:** Strive to identify and reuse existing components and logic whenever possible.
*   **Abstraction:**  Create abstractions where appropriate to simplify complex logic.

**2. KISS (Keep It Simple, Stupid)**

*   **Minimal Code:**  Keep code concise and focused on its primary task.
*   **Readability:** Prioritize clear and understandable code.
*   **Simple Logic:** Favor straightforward algorithms and data structures.
*   **Avoid Over-Engineering:** Resist adding unnecessary complexity.

**3. SOLID Principles**

*   **Single Responsibility Principle:** Each class/agent should have a single, well-defined responsibility.
*   **Open/Closed Principle:**  The agent should be extensible through public interfaces without modifying its internal implementation.
*   **Liskov Substitution Principle:** Subclasses should be substitutable for their base classes without altering the correctness of the program.
*   **Interface Segregation Principle:**  Clients should not be forced to implement interfaces they do not use.
*   **Dependency Inversion Principle:**  High-level modules should not depend on low-level modules.

**4. YAGNI (You Aren't Gonna Need It)**

*   **Avoid Unnecessary Features:** Don't implement functionality that is not currently required.
*   **Focus on Core Functionality:** Concentrate development on essential aspects of the agent's task.
*   **Refactor for Future Needs:**  Consider potential future requirements during design.

**5. Development Workflow & Practices**

*   **Code Reviews:** All changes require a thorough code review by at least one other developer.
*   **Version Control (Git):** Utilize Git for version control and collaborative development.
*   **Branching Strategy:** Employ a well-defined branching strategy (e.g., Gitflow) for feature isolation.
*   **Documentation:**  Add concise documentation to explain the purpose of functions and classes.
*   **Testing:**  Prioritize unit and integration testing to ensure code correctness.
*   **Code Style:** Adhere to a consistent code style guide (e.g., PEP 8).
*   **Error Handling:** Implement robust error handling and logging.

**6.  File Structure & Scope**

*   **File Size Limit:** Each file must be no more than 180 lines of code.
*   **Modular Design:** Break down large modules into smaller, manageable components.
*   **Clear Module Interfaces:** Define clear interfaces for agent modules to facilitate reuse.
*   **Data Structures:**  Use appropriate data structures for efficient data handling.
*   **Algorithm Design:** Implement algorithms with appropriate time and space complexity.

**7.  Test Coverage & Automation**

*   **Mocks Only for Testing:** All tests should rely solely on mocks and stubs.  No external implementations.
*   **Test-Driven Development:** Prioritize writing tests before writing code.
*   **Comprehensive Test Suite:** Aim for at least 80% test coverage across all modules.
*   **Automated Testing:** Implement a system for automated test execution.

**8.  Code Quality & Best Practices**

*   **Meaningful Names:** Use descriptive and meaningful names for variables, functions, and classes.
*   **Comments:**  Add clear and concise comments where necessary to explain complex logic.
*   **Naming Conventions:**  Follow established naming conventions (e.g., snake_case).
*   **Error Messages:** Implement informative error messages.

**9.  AGENTS.md File Content Guidelines:**

*   **Header:**  Include a header with the version of the AGENTS.md file.
*   **Introduction:** Provide a brief overview of the project goals and principles.
*   **Modules:** Organize the code into logical modules with clear responsibilities.
*   **Data Structures:**  Provide definitions for any crucial data structures used.
*   **Example Code:** Include a few simple example code snippets to illustrate key concepts.
*   **Configuration:** Include any necessary configuration files.
*   **Dependencies:** List any required dependencies (libraries, frameworks).

**10.  Specific Guidelines for Specific File Types**

*   **Agent Initialization:** Ensure initialization code is well-documented and isolated.
*   **Data Acquisition Module:** Define the data acquisition process and its output.
*   **Algorithm Implementation:** Detail the steps and logic for the core algorithm.
*   **Output Formatting:** Define clear formatting for the output.

These guidelines are intended to serve as a foundational framework for development.  Continuous refinement and adaptation are encouraged as the project evolves.
```