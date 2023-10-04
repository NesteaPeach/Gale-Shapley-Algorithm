# Gale-Shapley-Algorithm

## Description

This repository contains a Python implementation of the Gale-Shapley algorithm, also known as the Stable Marriage Problem solver. The Gale-Shapley algorithm finds stable matches between two sets of elements with preferences for each other, such as matching men and women based on their preferences.

## Algorithm Description

The Gale-Shapley algorithm works by iteratively proposing and matching individuals based on their preferences until a stable matching is achieved. It ensures that there are no blocking pairs, meaning no two individuals would prefer each other over their current matches.

## Usage

You can use this Python script to find stable matches between two groups. It includes example preferences for demonstration purposes.

## How to Run

1. Clone this repository to your local machine.
2. Run the `gale_shapley()` function to find stable matches.
3. The output will display the resulting matches between men and women.

## Example

```python
matches = gale_shapley()
for i in range(len(matches)):
    print(men[i], "married", women[matches[i]])
