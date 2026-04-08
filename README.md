# SQE-lab-task-1-MZ
# Software Testing & Development Lab Tasks
This repository contains three lab tasks focused on Object-Oriented Programming (OOP) in Java and the fundamental concepts of Software Testing, specifically identifying Errors, Faults, and Failures.
# Lab Task 1: Course Result System 
Objective: To evaluate software execution by observing the relationship between programmer mistakes and system behavior.
Implementation: A CourseResult class to store student names, course names, and grades.
Concepts Covered: * Error: Syntax mistakes (e.g., case-sensitivity in variable names).
Fault: Logic bugs (e.g., lack of input validation for grades).Failure: Runtime issues (e.g., NullPointerException or incorrect output).
# Lab Task 2: Point & Line Geometry
Objective: Designing a system using Composition (a class containing objects of another class) and testing it for mathematical accuracy.
Implementation: * Point class: Handles x and y coordinates with constructors, getters, and setters.
Line class: Uses two Point objects to calculate the length of a line using the distance formula:$$d = \sqrt{(x_2 - x_1)^2 + (y_2 - y_1)^2}$$
Testing Scenarios:
Failures: Passing null objects, division by zero, or incorrect formula implementation.
Non-Failures: Verifying standard distances (e.g., Pythagorean triplets) and zero-length lines.
# Lab Task 3: Defect Reporting (CUOnline System)
Objective: To identify, document, and report defects in a real-world Academic Management System (CUOnline).
Focus Areas: Functional testing, Security (URL manipulation), and Usability.
Deliverables: * A comprehensive Defect Report detailing Bug IDs, Severity, Steps to Reproduce, and Expected vs. Actual results.Identification of critical security flaws and logical calculation errors in GPA management.
