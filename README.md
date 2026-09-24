# --TJ-Tasks-2026--soumya_srivastava-
technojam 
Approach-by using a stack to track opening brackets.A stack is ideal because the most recently opened bracket must be closed first.
Algorithm-
Create an empty stack.
Traverse the string from left to right.
For each character:
If it is (, [, or {, push it onto the stack.
If it is a closing bracket:
If the stack is empty, return NO.
Remove the top opening bracket.
Check whether it matches the closing bracket.
If it does not match, return NO.
After processing all characters:
If the stack is empty, return YES.
Otherwise, return NO because some opening brackets remain unmatched.
output-
<img width="1897" height="961" alt="Screenshot 2026-09-24 224419" src="https://github.com/user-attachments/assets/b8194f55-79f6-4c7f-966f-1f6556230684" />
<img width="1917" height="976" alt="Screenshot 2026-09-24 224727" src="https://github.com/user-attachments/assets/1440e2b8-81e3-4dfd-9738-8c7ab796c2bf" />


