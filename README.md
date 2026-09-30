# Student Performance Tracker and Academic Risk Predictor

A beginner-friendly Python project that calculates a student's academic performance and estimates their academic risk level using their attendance and marks.

## Features

- Collects a student's name, attendance percentage, and marks in Maths, Science, and English.
- Checks that the name is not empty.
- Validates that attendance and marks are numbers between 0 and 100.
- Calculates total and average marks.
- Assigns a grade based on the average.
- Predicts a risk level and provides a suggestion.

## Grade Criteria

| Average | Grade |
|---:|:---|
| 90–100 | A+ |
| 75–89.99 | A |
| 60–74.99 | B |
| 50–59.99 | C |
| 40–49.99 | D |
| Below 40 | Fail |

## Risk Criteria

- **High Risk:** Average below 40 or attendance below 50%.
- **Medium Risk:** Average below 60 or attendance below 75%.
- **Low Risk:** Otherwise.

## Requirements

- Python 3
- Jupyter Notebook, if you want to run the `.ipynb` file

The project uses Python's built-in functions and does not require additional packages.

## How to Run

1. Open `student_performance_tracker.ipynb` in Jupyter Notebook or JupyterLab.
2. Run the notebook cells in order.
3. Enter the requested student details when prompted.

## Example

```text
Enter student name: Rahul
Enter attendance percentage: 80
Enter Maths marks out of 100: 85
Enter Science marks out of 100: 94
Enter English marks out of 100: 92

--- Performance Result ---
Student Name: Rahul
Total Marks: 271.0
Average Marks: 90.33
Grade: A+

--- Risk Prediction ---
Risk Status: Low Risk
Suggestion: Keep up the good work.
```

## Project File

- `student_performance_tracker.ipynb` — notebook containing the project code.
