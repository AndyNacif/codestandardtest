# codestandardtest
Review cursor docs feature
Code Review Standards Document
Purpose: This document outlines the rules and standards to ensure all code submissions align with best practices and specific library requirements. These standards will guide both manual and automated code reviews.
Code Standards and Rules:
General Coding Best Practices:
Code must be modular and reusable.
Variables and functions should have meaningful and descriptive names.
Comments should be used to clarify complex logic but avoided for self-explanatory code.
Consistent indentation and formatting (e.g., 4 spaces for Python, standard conventions for other languages).
Error Handling:
All critical functions must have proper error handling (e.g., try-catch blocks in Python).
Avoid suppressing errors without logging (e.g., except Exception: pass).
Library-Specific Standards:
Use recommended methods and classes of a library unless there is a valid reason not to.
Ensure proper initialization and teardown when using context managers (e.g., with in Python).
Avoid using deprecated or non-recommended libraries, such as the random module in Python for cryptographic purposes (use secrets or os.urandom instead).
Performance and Optimization:
Avoid redundant computations and ensure that algorithms are optimized.
Use list comprehensions instead of loops where applicable in Python.
Security Standards:
Do not hardcode sensitive information (e.g., API keys, credentials).
Sanitize all inputs to prevent injection attacks.
Testing and Validation:
All code should have associated test cases to ensure expected functionality.
Use assertions to validate critical assumptions.
