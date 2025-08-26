# Experiment-4
## ARMSTRONG NUMBER 
# Aim: Write a python program to check the number is Armstrong number or not and inspect for failures. 

# Algorithm
1.	Start the program.
2. Read an integer input number.
3. Initialize the variables current_digit, sum = 0, and num = number.
4. Repeat Steps 5 to 7 until num > 0
5. current_digit = (num % 10).
6. sum = sum + (current_digit * current_digit * current_digit). 7. Stop the program.
7. num = num / 10.
8. Check if sum == number. If true, print "It is an Armstrong Number." Otherwise, print "It is not an Armstrong Number."
9. Stop the program. 

# Program
```python
num=int(input("Ente a anumber :"))
power=len(str(num))
total=sum(int(digit)**power for digit in str(num))
if num==total:
    print(num,"is an Armstrong number")
else:
    print(num,"is not an Armstrong number")
```

# Output
<img width="1498" height="186" alt="image" src="https://github.com/user-attachments/assets/6b41e4db-f477-4a6d-9154-acf3782c1412" />


# Result 
Thus, the python program to find an Armstrong number has been executed successfully.
