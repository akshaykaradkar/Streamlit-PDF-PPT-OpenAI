# Streamlit-OpenAI PDF to PPT Generator

Welcome to the **Streamlit-OpenAI PDF to PPT Generator** project! This application harnesses the power of Streamlit and OpenAI assistant API's to transform PDF files into visually engaging PowerPoint presentations. Perfect for educators, presenters, and anyone looking to convert dense documents into digestible slides!

## Features

- **Interactive Web Application**: Built with Streamlit for a seamless user experience.
- **OpenAI Integration**: Utilizes OpenAI to summarize and extract key points from your PDFs.
- **PDF Handling**: Extracts text from PDF files using PyPDF2.
- **PPTX Creation**: Generates professional PowerPoint slides with python-pptx.
- **Environment Management**: Manages sensitive information securely with python-dotenv.

## 🛠Installation

Follow these steps to set up and run the project locally:

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/akshaykaradkar/Streamlit-PDF-PPT-OpenAI.git
    cd Streamlit-OpenAI-PDF-PPT-Generator
    ```

2. **Create and Activate a Conda Environment**:
    ```bash
    conda create --name myenv python=3.9
    conda activate myenv
    ```

3. **Install Dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

4. **Set Up Environment Variables**:
    - Create a `.env` file in the project root and add your OpenAI API key:
        ```env
        OPENAI_API_KEY=your_openai_api_key
        ```

## Usage

1. **Run the Streamlit App**:
    ```bash
    streamlit run main.py
    ```

2. **Upload Your PDF**: Follow the on-screen instructions to upload a PDF file.
3. **Generate Presentation**: Let the app work its magic and generate a structured PowerPoint presentation from your PDF.

## Project Structure

- `main.py`: The main application script.
- `.env`: Environment variables file (ensure this is not included in version control for security).
- `requirements.txt`: A list of all dependencies.

## How It Works

1. **PDF Upload**: Users upload a PDF file through the Streamlit interface.
2. **Text Extraction**: The app extracts text from the PDF using PyPDF2.
3. **Content Summarization**: OpenAI processes the extracted text, summarizing the key points.
4. **Slide Generation**: The summarized content is then used to create PowerPoint slides with python-pptx.

## Dependencies

- **Streamlit**: For building the web interface.
- **OpenAI**: For text summarization and content generation.
- **PyPDF2**: For extracting text from PDF files.
- **python-pptx**: For creating PowerPoint presentations.
- **python-dotenv**: For managing environment variables.

## Contributing

Contributions are welcome! If you have any suggestions, improvements, or bug fixes, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License.

## Acknowledgements

- Inspired by the OpenAI Cookbook example on creating slides with the Assistant's API and DALL-E: [Creating Slides with Assistant's API and DALL-E](https://cookbook.openai.com/examples/creating_slides_with_assistants_api_and_dall-e3).
- Thanks to the developers of Streamlit, OpenAI, PyPDF2, and python-pptx for their fantastic libraries.
- Special thanks to the open-source community for their continuous support and contributions.

---

**Transform your PDFs into beautiful presentations effortlessly with the power of AI!**

