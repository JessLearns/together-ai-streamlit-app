# Python Code Generator with CodeLlama

## Overview

This project is a **Python Code Generator** powered by **Streamlit** and **Together's CodeLlama-34b-Instruct-hf model**. It allows users to generate Python code by providing a natural language description of the desired functionality. The app utilizes **Together AI's API** to interact with the CodeLlama model for generating high-quality, well-commented Python code.

Upon completion of this project, users will be able to request the application to create a Python script based on their specific requirements. The application is built in **Streamlit Cloud** using **CodeLlama** and **Together AI**.

## Background

This repository is a requirement for the completion of **MDC Course CAP 4767, Data Mining**, Module 5.  
The Professor, **Dr. Ernesto Lee**, taught us in class how to create a Python Code Generator with CodeLlama. This assignment followed all the guidelines provided by the Professor.

## Features

- **User-Friendly Interface**: Built with Streamlit for simplicity and ease of use.
- **AI-Powered Code Generation**: Leverages the power of CodeLlama to generate Python code based on plain-text descriptions.
- **Customizable Inputs**: Users can input any description to receive relevant Python code.
- **Error Handling**: Provides meaningful error messages if the code generation process fails.

## Usage

1. Open the Streamlit application in your browser (it will usually run on `http://localhost:8501`).
2. Enter a description of the Python application or code you want to generate in the text area.
3. Click the **"Generate Code"** button.
4. View and copy the generated Python code displayed in the output section.

### Example

- **Input**:  
  _"Write a function to calculate the factorial of a number using recursion."_

- **Generated Code**:
  ```python
  # Function to calculate factorial using recursion
  def factorial(n):
      """
      Calculate the factorial of a given number using recursion.

      Parameters:
      n (int): The number to calculate the factorial for.

      Returns:
      int: The factorial of the number.
      """
      if n == 0 or n == 1:
          return 1
      else:
          return n * factorial(n - 1)

  # Example usage
  print(factorial(5))  # Output: 120

## Acknowledgment

Special thanks to Dr. Ernesto Lee for teaching us how to create this project and for his guidance throughout the course.

## References

1. [Building a Python Code Generator with CodeLlama in Streamlit Cloud](https://drlee.io/building-a-python-code-generator-with-codellama-in-streamlit-cloud-4a78886918eb) by Dr. Ernesto Lee
2. [Streamlit documentation](https://docs.streamlit.io/)
3. [Together AI Documentation](https://docs.together.ai/docs/introduction)
4. [GitHub Guide](https://docs.github.com/en)



