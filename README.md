Lecture 8: Fixing a Buggy Python Script Using AI

Objective

Identify and fix logical bugs in a Python script using unit testing and AI-assisted code review.

Project Files

* student_utils_buggy.py — Reconstructed buggy version for the RED stage.
* student_utils.py — Corrected Python utility functions.
* test_student_utils.py — Nine unit tests.
* bug_notes.md — Description of the identified bugs and fixes.
* audit.md — Code audit and final validation report.

Bugs Identified

1. Incorrect average calculation due to an incorrect denominator.
2. Incorrect passing-mark boundary condition.
3. Incorrect grade-checking order.

Debugging Workflow

1. RED: Run tests against the buggy implementation and record the failures.
2. FIX: Correct the three logical bugs.
3. GREEN: Run the tests against the corrected implementation.

Validation

All nine unit tests passed against the corrected implementation in Google Colab.

Tools Used

* Python
* Google Colab
* unittest
* ChatGPT for AI-assisted debugging and code review

Evidence

Screenshots of the failing and passing test outputs should be retained with the practical submission.
