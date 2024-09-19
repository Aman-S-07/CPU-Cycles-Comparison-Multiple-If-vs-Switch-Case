- The table compares the efficiency of two programming constructs — `Multiple-If` and `Switch-Case` — in terms of `CPU cycles`. 
- The number of CPU cycles refers to the amount of processing power required to execute each type of statement. 
- The goal is to minimize the CPU cycles, as fewer cycles mean the program runs more efficiently.

| Method        | CPU Cycles (Lower is Better) | Example Scenario                         |
| ------------- | ---------------------------- | ---------------------------------------- |
| Multiple-If   | Higher                       | Checking many unrelated conditions       |
| Switch-Case   | Lower                        | Checking a single variable               |

#### 1. CPU Cycles (Lower is Better):
- CPU cycles indicate how much time the processor needs to execute the instructions in the method. 
- A lower number of cycles is preferred because it means the method runs more efficiently and requires fewer processor resources.

##### Multiple-If: 
- This method generally uses more CPU cycles because it evaluates multiple, possibly unrelated conditions. 
- The CPU has to check each if or elif statement until it finds the right one, leading to more checks and longer processing times.

##### Switch-Case: 
- This method tends to use fewer CPU cycles because it usually works by evaluating a single variable and comparing it against multiple cases. 
- Switch-Case is more efficient when checking different values of the same variable, making it better for performance in such scenarios.