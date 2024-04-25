# Singing Tournament Scoring System

## Overview
This code was developed for a zonal coding exam to implement a scoring system for a singing tournament. The system calculates points for contestants based on their performance range within specified lower and upper bounds.

## Functionality
- **Input Parameters**
  - Number of test cases (`test case`)
  - Number of contestants (`contestant`)
  - Lower and upper bounds for each contestant's performance range
  
- **Scoring Algorithm**
  - Calculates points for each contestant based on the overlap of their performance range with other contestants.
  - Assigns points using a weighted system based on performance range comparisons.

## Implementation
- Uses NumPy for array operations.
- Validates input to ensure lower bounds are not greater than upper bounds.
- Iteratively calculates points for each contestant and test case.
  
## Execution
- Run the code and input the number of test cases followed by the number of contestants and their respective performance ranges.
- The code will output the points assigned to each contestant for each test case.

## Note
This code was created as a solution for a zonal coding exam and is designed to efficiently calculate scores for a singing tournament based on the provided performance ranges.
