# Name Searching Program

## Overview

Welcome to the Name Searching Program! This C++ program is designed to help users find the position of a name in a list provided by the user. The program returns the position of the name and, if more than one name matches the search criteria, it prints all matching names and their locations in the list.

## Features

- **Case-Insensitive Search:**
  - The program performs a case-insensitive search for names.

- **Multiple Matches:**
  - If there are multiple occurrences of the searched name, the program prints all matching names and their positions in the list.

## Code Organization

All the code for this project is located in the accompanying PDF file named `Barron-Jose-ns1.pdf`. The document is structured to be read from left to right, providing a detailed explanation of the code, 
its functions, and the rationale behind design decisions.

All the code for this project is divided into several files:

- `strextra.h` and `strextra.cpp`: These files contain functions for string manipulation and searching, providing essential utilities for the main program.

- `suffix.h` and `suffix.cpp`: These files handle the generation of suffixes based on an integer value, contributing to a more user-friendly presentation of the position of names in the list.

- `ns.cpp`: The main program file where the user interacts with the program. It reads names from a file, allows users to search for names, and displays the results.

## Test Runs

The program has been tested with various scenarios to ensure correct functionality:

1. **Basic Name Search:**
   - User searches for a name present in the list.
   - Program displays the position of the name.

2. **Case-Insensitive Search:**
   - User performs a case-insensitive search for a name.
   - Program accurately handles case variations and displays the correct position.

3. **Multiple Occurrences:**
   - User searches for a name with multiple occurrences in the list.
   - The program displays all positions of the matching names.

4. **Name Not Found:**
   - User searches for a name not present in the list.
   - Program informs the user that the name was not found.

## Skills Showcase

This project demonstrates proficiency in several key areas:

- **C++ Programming:**
  - Implements the Name Searching Program using C++, leveraging object-oriented principles and language features.
  - Demonstrates competence in working with C++ functions, standard libraries, and string manipulation.

- **Problem Solving:**
  - Addresses the challenge of efficiently searching for names within a given list.
  - Implements solutions for handling case-insensitive searches, multiple occurrences, and providing accurate output.

- **Modular Code Design:**
  - Organizes code into separate files (`strextra.h`, `strextra.cpp`, `suffix.h`, `suffix.cpp`, `ns.cpp`) for improved modularity and maintainability.
  - Utilizes inline functions for string manipulation and searching in `strextra.h`.

- **User Interaction:**
  - Develops a user-friendly interface for interacting with the program, including input for file names and search queries.

- **File Handling:**
  - Effectively reads names from a file to create a list for searching in the main program (`ns.cpp`).

- **String Manipulation:**
  - Implements string manipulation functions for case-insensitive searches (`tolower_str`) and substring checks (`str_is_incl`) in `strextra.h`.

- **Testing:**
  - Conducts comprehensive testing with various scenarios to ensure the correctness and robustness of the program.
  - Test scenarios include basic name searches, case-insensitive searches, handling multiple occurrences, and scenarios where the name is not found.

- **Documentation:**
  - The accompanying PDF provides clear and detailed documentation, explaining the code's functionality, usage, and design choices.

These skills collectively showcase the ability to design, implement, and document a C++ program that effectively addresses the specific problem domain of searching for names in a list.


