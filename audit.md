# Code Audit — Lecture 8

## Initial Audit
- Found three logical bugs in the original student_utils.py.
- The average calculation used an incorrect denominator.
- The passing condition excluded the boundary mark of 40.
- The grade conditions were ordered incorrectly.

## Validation
- Created nine unit tests in test_student_utils.py.
- Ran the tests against the buggy implementation to identify failures.
- Corrected the three bugs.
- Re-ran all nine tests successfully.

## Final Result
All nine tests passed after the fixes.
