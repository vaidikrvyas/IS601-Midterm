# Advanced Python Calculator - Midterm Project

## Project Overview

### Key Features

- Arithmetic operations: Add, Subtract, Multiply, Divide
- Calculation history management
- Plugin system for extended functionalities
- Professional logging system
- Dynamic configuration via environment variables

## Installation and Setup

1. Clone the repository:
   ```
   git clone https://github.com/vaidikrvyas/IS601-Midterm
   ```

2. Install required dependencies:
   ```
   pip install -r requirements.txt
   ```

## Usage

To start the calculator, run:
```
python calculator.py
```

Follow the on-screen prompts to perform calculations or access extended features.

## Design Patterns

- **Facade Pattern**: Simplifies complex operations with Pandas.
- **Command Pattern**: Manages calculation commands and history in the REPL.
- **Factory Method, Singleton, and Strategy Patterns**: Enhances scalability and maintainability.

## Environment Variables and Configuration

Environment variables are used for configuring logging levels and output destinations. Example:
```
export LOG_LEVEL=INFO
export LOG_FILE=calculator.log
```

## Logging

The application uses different logging levels (INFO, WARNING, ERROR) to capture various operational details. Logging configuration is dynamic, allowing changes via environment variables.

## Error Handling

Illustrates "Look Before You Leap" (LBYL) and "Easier to Ask for Forgiveness than Permission" (EAFP) principles in error management.

## Testing

Utilize Pytest for comprehensive testing, aiming for over 90% coverage. Ensure adherence to PEP 8 with Pylint.

## GitHub Actions

Automated testing with GitHub Actions ensures code quality and functionality before merging.

## Demonstration

Link to the video demonstration: [Video Link]
