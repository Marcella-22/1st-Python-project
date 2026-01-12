# Student Marks Analyzer 
Description : A aimple python programme that asks the user to enter the marks of few subjects and prints the marks,total and the average based on the marks stored in lists. 

Language : Python

How to run: Open an online python compiler. Copy and paste the code. Click the run button.Enter the marks when prompted.

Code:
```python
marks = []
count = int(input("how many subjects? "))
 
for i in range(count):
    mark=int(input(f"Enter mark {i+1}: "))
    marks.append(mark) 

total = sum(marks)
average =total / len(marks)

print("Marks: ", marks)
print("Total: ",total)
print("Average: ", average)
```
Output :<img width="1366" height="768" alt="Screenshot 2026-01-12 08 31 03" src="https://github.com/user-attachments/assets/c5c87894-26ef-45b5-af95-1572d9ca2644" 
