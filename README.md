# Student Grade Calculator

## Project Description

Student Grade Calculator is a simple Python application
that calculates the average grade of a student and
determines whether the student passes or fails.

## Features

- Calculate the average of a list of grades.
- Determine if a student passes or fails.
- Raise an error if the grades list is empty.

## Requirements

- Python 3
- pytest
- flake8

## Installation

Clone the repository:

```bash
git clone https://github.com/chebabn58-ctrl/grade-calculator.git
cd grade-calculator
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

## Running Tests

Run the unit tests:

```bash
pytest
```

Check the Python code style:

```bash
flake8 .
```

## Passing Criteria

A student passes if the average grade is greater
than or equal to 10.

- Average >= 10: Pass
- Average < 10: Fail

## Continuous Integration

GitHub Actions automatically runs Python tests
and checks code quality when changes are proposed.
