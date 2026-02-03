# Matrix Statistics Calculator
A **Python GUI program** to calculate **mean, variance, standard deviation, median, max, min, sum, range, and z-score** for **square matrices**.


## Project Overview
The **Matrix Statistics Calculator** was developed to help users **understand and analyze numeric data** in a simple, interactive way. Many times, we have a set of numbers and want to see patterns, averages, deviations, or other statistical measures, but manually calculating them is time-consuming and error-prone.  
This program allows the user to **enter numbers**, automatically converts them into a **square matrix n×n**, and calculates **all the key statistics** in one click. It’s designed to be **educational, interactive, and easy to use**.


## Why This Code Was Created
- To give users **a visual and interactive way** to explore matrix statistics.
- To **automate calculations** for matrices of any perfect square size (2x2, 3x3, 4x4, etc.).
- To **teach basic statistical concepts** (mean, variance, standard deviation, etc.) in a **clear, step-by-step manner**.
- To provide a **GUI** that is simple and user-friendly, so anyone can use it without prior programming knowledge.


## GUI (Graphical User Interface)
The GUI was built using **Tkinter**, Python's standard library for creating graphical interfaces.  

### Key Features of the GUI:
1. **Input Field**:  
   - Users enter numbers separated by commas (e.g., `0,1,2,3,4,5,6,7,8`).
   - The program will check if the number of values is a **perfect square** (e.g., 4, 9, 16) so they can form a square matrix.

2. **Instructions & Notes**:  
   - The GUI shows clear instructions and an example to guide the user.

3. **Calculate Button**:  
   - Once pressed, it calculates all statistics **per column, per row, and for the entire matrix**.

4. **Output Box**:  
   - Displays results in a **clear, readable format**.
   - Includes all calculated statistics: mean, variance, standard deviation, median, min, max, sum, range, and z-score.

5. **Error Handling**:  
   - If the user enters a number of values that is not a perfect square, or invalid input, the GUI shows a **friendly error message**.


## Example Workflow
User input: 0,1,2,3,4,5,6,7,8

Step 1: Count numbers = 9
Step 2: n = sqrt(9) = 3
Step 3: Convert to a 3x3 matrix
Matrix:
0 1 2
3 4 5
6 7 8
Step 4: Calculate mean, variance, standard deviation, etc.
Step 5: Output results in GUI

## Sample Output (mean & sum only)
mean:
Columns: [3.0, 4.0, 5.0]
Rows : [1.0, 4.0, 7.0]
All : 4.0

sum:
Columns: [9, 12, 15]
Rows : [3, 12, 21]
All : 36

## Why GUI is Useful
- **Visual & Interactive**: Users can immediately see the results without writing code.
- **Educational**: Helps learners understand how statistics change depending on the input numbers.
- **Flexible**: Works for any square matrix size.

## How to Run
1. Make sure **Python 3.x** is installed on your system.
2. Install the required library:
```bash
pip install numpy

Run the program:
python matrix_calculator.py
Enter numbers separated by commas in the input field and click Calculate.

Examples to Try
3x3 matrix: 2,4,6,8,10,12,14,16,18
4x4 matrix: 1,3,5,7,2,4,6,8,9,11,13,15,10,12,14,16
2x2 matrix: 7,8,9,10
5x5 matrix: 1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16,17,18,19,20,21,22,23,24,25

## License
This project is open-source under the MIT License. You can use it for learning, personal projects, and educational purposes.
