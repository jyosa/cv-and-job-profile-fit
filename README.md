# CV job profile fit


[<img src="https://img.youtube.com/vi/q90sRselN94/hqdefault.jpg" width="800" height="600"
/>](https://www.youtube.com/embed/q90sRselN94)



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

## Usage

To start the application, run the cv_analyzer.py script:

```bash
python cv_analyzer.py
```

The application window will open. Follow these steps to analyze a CV:

- Enter the job profile in the text box provided.
- Click the "Upload CV PDF" button to select and upload the candidate's CV in PDF format.
- Click the "Submit Analysis" button to generate the analysis.

The results will be displayed in the text area at the bottom of the application window.

## Configuration

Before running the application, you need to set your OpenAI API key. Replace 'here your openai key' with your actual key in the cv_analyzer.py script:

```python
openai.api_key = 'your-openai-api-key'
```

## Contributions

Contributions are welcome. If you would like to contribute to the project, please fork the repository and submit a pull request with your proposed changes.

##Support

If you encounter any issues or have questions about the application, please submit an issue on the GitHub repository.

## License

CV Analyzer is released under the MIT License. See the LICENSE file in the repository for full details.

## Contact

For further contact, you can reach out to the repository maintainer via GitHub.
