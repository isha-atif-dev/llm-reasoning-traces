Task:
A Python function crashes when certain inputs are provided.

Plan:
1. Understand the expected behaviour of the function
2. Identify inputs that cause failure
3. Locate the source of the error

Actions:
- Run the function with edge case inputs
- Inspect the logic that processes those inputs

Tool Use:
Tool: Python
Input:
def divide(a, b):
    return a / b

Output:
ZeroDivisionError

Final Answer:
The function fails when the divisor is zero. Adding a conditional check prevents the crash.

Reflection:
Input validation is important to avoid runtime errors and improve robustness.