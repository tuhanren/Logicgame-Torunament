# Logicagme Tournament Simulator

This project is a Python-based simulation and analysis tool designed for a tournament-style logic game. It includes functionality for generating and evaluating game scenarios, tracking player performance, and analyzing outcomes under various conditions.

## Features

- **Core Functionalities**:
  - Generate a valid secret number for the game.
  - Evaluate guesses based on specific rules.
  - Simulate a tournament and leaderboard management.
- **Performance Analysis**:
  - Measure the worst-case scenario for guessing algorithms.
  - Evaluate computational efficiency across all valid scenarios.
- **Data Visualization** (if applicable): Visualize tournament results and player performance.

## Project Structure

The project consists of the following key modules and functions:

### Imports

The project relies on the following libraries:

```python
import random
import time
from dataclasses import dataclass, field
from typing import List
from itertools import permutations
from unittest.mock import patch
```

### Main Functions

- `generate_secret_number`: Generate a valid secret number following the game rules.
- `is_valid_guess`: Validate player guesses based on unique digits and game constraints.
- `evaluate_guess`: Compare a player's guess to the secret number and return the result.
- `main`: Orchestrate the overall flow of the game or tournament.
- `find_worst_case`: Analyze and identify the worst-case scenario for the guessing algorithm.

## Installation

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/your-username/logicagme-tournament.git
   cd logicagme-tournament
   ```

2. **Set Up the Environment**:
   Ensure Python 3.8+ is installed. Install required libraries (if any):

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Jupyter Notebook**:
   Launch the notebook for interactive analysis:
   ```bash
   jupyter notebook logicagme_tournament_en.ipynb
   ```

## Usage

1. Open the Jupyter Notebook.
2. Run the cells sequentially to simulate the tournament and analyze results.
3. Modify parameters (e.g., player numbers, scoring rules) directly in the notebook to explore different scenarios.

## Comments and Notes

- This project uses Python's `dataclass` for efficient player and tournament management.
- Mock testing is included to simulate player guesses and ensure repeatable results.
- Performance analysis is conducted by iterating through all possible scenarios, ensuring robust testing of algorithms.

## Contributing

Contributions are welcome! Feel free to fork this repository, make changes, and submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
