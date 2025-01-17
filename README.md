# AI Solver for Student Math Work

## **Overview**
This project aims to assist educators in solving and understanding math problems that lack clear solutions. The goal is to create a tool that can process images or documents of math problems, analyze them, and provide solutions or insights. By having a reliable reference, teachers like me can better guide students and improve their understanding of challenging math concepts.

## **Motivation**
As a teacher, I often encounter students' math problems that don't have ready solutions available. This tool is being developed to bridge that gap, allowing educators to:
- Quickly extract problems from uploaded files (images or PDFs).
- Obtain solutions or detailed references for teaching purposes.

The project is still **in progress**, and contributions are welcome to help shape its development into a more robust and effective tool.

## **Tools Used**
This project leverages the following tools and frameworks:
- **[FastAPI](https://fastapi.tiangolo.com/):** For building the backend API.
- **[React](https://reactjs.org/):** For creating the frontend user interface.
- **[Tesseract OCR](https://github.com/tesseract-ocr/tesseract):** For extracting text from uploaded images.
- **[PyPDF2](https://pypi.org/project/PyPDF2/):** For extracting text from PDF documents.
- **[Pillow](https://pillow.readthedocs.io/):** For image processing.
- **[Axios](https://axios-http.com/):** For handling HTTP requests between the frontend and backend.

## **Features**
- Upload images or PDF documents containing math problems.
- Extract text and process equations using OCR and document processing tools.
- Use AI to generate step-by-step solutions (future integration).

## **Current Status**
At this stage:
- Basic functionality to upload files and extract text is implemented.
- AI-based solution generation is under exploration and will be added in future updates.
- The system may have limitations with certain file types or handwritten inputs.

## **Future Plans**
- Enhance AI algorithms for generating step-by-step solutions.
- Improve support for handwritten math problems.
- Add a user-friendly interface for better accessibility.

## **How to Contribute**
Contributions are highly encouraged! Whether you're a developer, educator, or math enthusiast, feel free to:
- Fix bugs or improve existing features.
- Suggest and implement new features.
- Help optimize the solution generation process.

To get started, fork the repository and submit a pull request. If you have questions or suggestions, please open an issue.

## **Acknowledgments**
This project is inspired by the need to provide better support to students and educators in understanding challenging math problems. Thanks to all contributors and the open-source community for making this possible.
