# Machine Learning & Data Science Course

An organized 120-day challenge to build practical skills in Machine Learning (ML) and Data Science (DS). This repository contains daily exercises, resources, and mini-projects to accelerate learning and portfolio building.

## Overview
- **Curriculum length:** 120 days
- **Focus areas:** Python, data handling, statistics, ML algorithms, model evaluation, and deployment basics
- **Source of materials:** Intelligence Academy (curated resources and adapted exercises)
- **License:** MIT — see [LICENSE](LICENSE)

## Repository Structure
- `01_day/` — Day 01 exercises and notes
    - `Challenge_01.py`
    - `Challenge_02.py`
    - `Challenge_03.py`
    - `Challenge_04.py`
    - `day_01.md`

## Day 01 — Challenges
The first day introduces Python fundamentals and numeric operations essential for data work.

- **Challenge 01: The Identity Swap**
    - **File:** `Challenge_01.py`
    - **Description:** Swap two variables using tuple unpacking without a temporary variable.
    - **Input:** Initial values `x=100`, `y=50`
    - **Output:** Displays before/after swap: `Before Swap: x=100 y=50` → `After Swap: x=50 y=100`
    - **Key Concepts:** Variable assignment, tuple unpacking, swap patterns.

- **Challenge 02: The Type Auditor**
    - **File:** `Challenge_02.py`
    - **Description:** Inspect type of user input and convert from string to float.
    - **Input:** User enters a number (initially as string)
    - **Output:** Shows type before (`<class 'str'>`) and after conversion (`<class 'float'>`)
    - **Key Concepts:** Type inspection with `type()`, type casting with `float()`, input validation.

- **Challenge 03: The Precision Banker**
    - **File:** `Challenge_03.py`
    - **Description:** Handle floating-point precision and format currency output.
    - **Input:** Calculation `bill = 100/3.0`
    - **Output:** Formatted to 3 decimal places: `$33.333`
    - **Key Concepts:** Float precision, string formatting with f-strings, rounding control.

- **Challenge 04: The Modulo Architect**
    - **File:** `Challenge_04.py`
    - **Description:** Convert seconds into hours, minutes, and remaining seconds using modulo and floor division.
    - **Input:** Time in seconds (user input)
    - **Output:** Breakdown: `H hours and M minutes and S seconds`
    - **Example:** 3661 seconds → `1 hours and 1 minutes and 1 seconds`
    - **Key Concepts:** Integer division (`//`), modulo operator (`%`), time arithmetic.

## Getting Started
1. Ensure you have Python 3.10+ installed.
2. Clone the repository:
     ```bash
     git clone https://github.com/anikasadiaOPT/Machine_Learning-Data_Science-Course.git
     cd Machine_Learning-Data_Science-Course
     ```
3. Explore Day 01:
     ```bash
     tree 01_day
     python3 01_day/Challenge_01.py
     python3 01_day/Challenge_02.py
     python3 01_day/Challenge_03.py
     python3 01_day/Challenge_04.py
     ```

## Contributing
Contributions are welcome under the terms of the MIT License.

- Please open an issue describing the improvement or bug.
- Use clear commit messages and keep changes focused.
- Follow existing naming conventions and folder structure.

## License
This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

Copyright (c) 2024–2025 anikasadiaOPT

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
