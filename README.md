# Objective Questions Generation Using GPT-3
## Introduction
This project aims to generate objective questions with multiple correct answers based on a given chapter from a subject. The questions are designed to assess the reader's understanding of the chapter, encourage critical thinking, and have more than one possible correct answer to increase complexity.

## Prerequisites
Before using this project, make sure you have the following:

* An OpenAI GPT-3 API key.
* Python installed on your system.
* The openai Python library.
## Overview
This project utilizes the power of the OpenAI GPT-3 model to generate objective questions dynamically. It provides a user-friendly way to create questions for educational purposes.

## Usage
API Key Configuration: Set your GPT-3 API key in the script's configuration section.

Function: The project defines a function named generateMCQs(objective, context) for generating questions. It takes two parameters:

objective: A string representing the objective or title of the questions.
context: A string representing the chapter or subject content.
Example Usage: An example of how to use the generateMCQs function is provided. You can input your specific objective and context to generate questions.

Output: The function returns the generated questions as a string.

## Handling Exceptions
The project includes error handling to manage any exceptions that may occur during the API call, ensuring robust functionality.

## Additional Information
The ultimate goal of this project is to facilitate educators in creating engaging and challenging assessments for their students. By generating questions with multiple correct answers, it encourages students to think beyond the surface level and explore different perspectives and possibilities.

Please ensure that the provided context is clear, relevant, and aligned with the desired educational objectives for optimal results.
