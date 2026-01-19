# Username formatter

Description : A python programme that converts a user's name into a clean usename using string methods

Language : Python

How to run : Open an online python compiler. copy and paste the code. click the run button. Enter the full name when prompted.

Code :
```python
name = input("Enter your full name: ")
clean_name = name.strip(). lower()
username = clean_name.replace(" ", "_")

print("Generated username:", username)
```
Output :![Uploading Screenshot 2026-01-19 09.34.18.png…]()
