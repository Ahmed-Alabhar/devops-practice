***Follow PEP8***

https://peps.python.org/pep-0008/ 

**Key Items** 

1. **Variable Names:**
   - Use lowercase with underscores for variable names (snake_case).
   - Example: `user_name`, `total_count`

2. **Function Names:**
   - Use lowercase with underscores for function names (snake_case).
   - Example: `calculate_total`, `validate_input`

3. **Class Names:**
   - Use CamelCase for class names (CapWords).
   - Example: `CarModel`, `CustomerOrder`

4. **Constants:**
   - Use all uppercase letters with underscores for constants (e.g., MAX_LENGTH).
   - Example: `MAX_VALUE`, `PI_VALUE`

5. **Modules:**
   - Use lowercase with underscores for module names.
   - Example: `utils.py`, `data_processing.py`

6. **Packages:**
   - Avoid using underscores in package names.
   - Example: `mypackage`, `tools`

7. **Global Variables:**
   - Limit the use of global variables; prefer function parameters or class attributes.
   - Example: Avoid global variables when possible.

8. **Function and Method Parameters:**
   - Use lowercase with underscores for function and method parameters (snake_case).
   - Example: `def calculate_area(radius):`, `def print_details(name, age):`
  
9. **Imports and Whitespace in Expressions/Statements:**
   - Imports should usually be on separate lines.
   - Example:

     ```python
     # Correct
     import os
     import sys

     # Incorrect
     import os, sys

     ```

10. **Whitespace in Expressions and Statements:**
    - Avoid extraneous whitespace in expressions and statements, especially immediately inside parentheses, brackets, or braces.
    - Example:

      ```python
      # Correct
      result = (value1 + value2) * (value3 - value4)

      # Incorrect
      result = ( value1 + value2 ) * ( value3 - value4 )
      ```

   Proper spacing enhances code readability and helps maintain a consistent style throughout the codebase.

11. **Indentation:** 
    - Use 4 spaces per indentation level.
    - Avoid using tabs for indentation.
    - Example:

      ```python
      def example_function():
          if condition:
              statement
      ```

   Proper indentation is crucial for code readability, and using consistent spaces helps maintain a clean and organized codebase.

12. **Maximum Line Length:**
    - Limit all lines to a maximum of 79 characters for code and 72 for docstrings.
    - Example: Keep code lines within the specified character limit.

   It's important to maintain a reasonable line length to ensure readability and prevent horizontal scrolling in code editors.

13. **Blank Lines:**
    - Use two blank lines before top-level function and class definitions.
    - Use one blank line between methods in a class.
    - Example:

      ```python
      def function1():
          # code

      def function2():
          # code
      ```

   Proper usage of blank lines contributes to the clarity and organization of your code.

14. **Encoding:**
    - Include the following line at the top of Python files for specifying the source code encoding:

      ```python
      # -*- coding: utf-8 -*-
      ```

   This line ensures that the correct character encoding is used for the source code, especially when dealing with non-ASCII characters.

15. **Comments:**
    - Keep comments concise and avoid unnecessary comments.
    - Use docstrings for documenting modules, classes, and functions.
    - Example:

      ```python
      # Correct
      def calculate_total(price, quantity):
          """Calculate the total cost."""
          return price * quantity

      # Incorrect
      # This function multiplies two numbers
      def multiply_numbers(a, b):
          return a * b
      ```

   Comments should provide meaningful information without stating the obvious, and docstrings are preferred for documenting functionality.

16. **Shebang Line:**
    - Include a shebang line at the top of the script for Unix-like systems.
    - Example:

      ```python
      #!/usr/bin/env python3
      ```

   The shebang line specifies the interpreter for the script and is important for Unix-like systems to execute the script using the correct interpreter.

17. **Naming Conventions for Special Situations:**
    - Use a single leading underscore for weak "internal use" indicators.
      - Example: `_internal_variable = 10`

    - Use double leading underscores for "name mangling" in classes.
      - Example: `__mangled_name`

   These conventions help convey the intended use of variables and attributes, emphasizing whether they are meant for internal use or are subject to name mangling within classes.


