## Overview

The `MCQA` folder contains a set of JSON files designed to evaluate the performance of Large Language Models (LLMs) on Open Radio Access Networks (O-RAN) related tasks. The files are divided into three difficulty levels: Easy, Medium, and Difficult.

## Files Description

- **Fin_E.json**: Contains multiple-choice questions categorized as "Easy". These questions focus on basic concepts and known facts about O-RAN.
- **Fin_M.json**: Contains multiple-choice questions categorized as "Intermediate". These questions require comprehension and application of concepts or involve moderate calculations or reasoning.
- **Fin_D.json**: Contains multiple-choice questions categorized as "Difficult". These questions demand a deep understanding of O-RAN standards or the ability to synthesize multiple pieces of information.

## File Structure

Each JSON file follows a consistent structure to facilitate ease of use. The JSON files are lists of questions, where each question is represented as a list:

```json
[
  [
    "Question text goes here",
    ["Option 1", "Option 2", "Option 3", "Option 4"],
    "Correct option index (1, 2, 3 or 4)"
  ],
  ...
]
```

- **Question text**: A string representing the multiple-choice question.
- **Options**: An array of strings, each representing a possible answer.
- **Correct option index**: A string representing the index of the correct answer within the options array.


### Example

Here's a Python example of how to load and use these JSON files:

```python
import json

# Load Easy questions
with open('MCQA/Fin_E.json', 'r') as file:
    easy_questions = json.load(file)

# Display first question
first_question = easy_questions[0]
print(f"Question: {first_question[0]}")
for i, option in enumerate(first_question[1]):
    print(f"{i+1}. {option}")
print(f"Answer: {first_question[1][int(first_question[2]) - 1]}")
```

This README file provides a comprehensive guide on the structure and usage of the JSON files within the `MCQA` folder, ensuring users can effectively utilize the resources for evaluating LLMs in O-RAN contexts.
