# CV job profile fit


## Description

CV Analyzer is a desktop application built with Python and Tkinter, designed to assist HR professionals and recruiters in the process of analyzing resumes/CVs. It automates the comparison of a candidate's CV against a job profile using OpenAI's language model. This tool extracts text from a PDF CV, formulates an analysis prompt, and generates insights on the candidate's strengths, weaknesses, and overall fit for the role.

## Features

- **PDF CV Parsing**: The application can read PDF files and extract text content for analysis.
- **OpenAI Integration**: Utilizes OpenAI's language model to intelligently analyze CVs in the context of a provided job profile.
- **User Interface**: Offers a simple and intuitive GUI to upload CVs, enter job profiles, and display the analysis.
- **Error Handling**: Includes basic error handling for missing inputs to ensure the user uploads a CV and enters a job profile before submission.

## Installation

To use CV Analyzer, you must have Python installed on your computer. If you do not have Python installed, please follow the instructions on [Python's official website](https://www.python.org/downloads/).

Once Python is installed, you will need to install the required dependencies:

```bash
pip install PyPDF2 openai tkinter
```

