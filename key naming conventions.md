Follow PEP8

Key Items 

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
   - Avoid extraneous whitespace in expressions and statements, especially immediately inside parentheses, brackets, or braces.
   - Example:

     ```python
     # Correct
     import os
     import sys

     # Incorrect
     import os, sys

     # Correct
     result = (value1 + value2) * (value3 - value4)

     # Incorrect
     result = ( value1 + value2 ) * ( value3 - value4 )
     ```

10. **Indentation:**
    - Use 4 spaces per indentation level.
    - Avoid using tabs for indentation.
    - Example:

      ```python
      def example_function():
          if condition:
              statement
      ```

   Proper indentation is crucial for code readability, and using consistent spaces helps maintain a clean and organized codebase.
