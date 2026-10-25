# Bug Notes — Lecture 8

## Bug 1: Incorrect Average Calculation
- Problem: The total was divided by len(marks) - 1.
- Impact: The calculated average was incorrect, and a single mark caused division by zero.
- Fix: Divide the total by len(marks).

## Bug 2: Incorrect Passing Boundary
- Problem: The condition used mark > PASS_MARK.
- Impact: A mark equal to 40 was incorrectly treated as failing.
- Fix: Use mark >= PASS_MARK.

## Bug 3: Incorrect Grade Check Order
- Problem: The First and Second grade conditions were checked before Distinction.
- Impact: High marks such as 95 were classified as First.
- Fix: Check average >= 90 before the lower grade ranges.
