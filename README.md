# LinkedIn Profile Digital Twin Chatbot
##### **This project creates a digital twin chatbot based on a LinkedIn profile saved as a PDF. It uses OpenAI’s language model to generate responses that reflect the professional background and skills contained within the profile. The chatbot interface is built with Gradio for easy, interactive conversations.**

### Features
- Extracts and parses LinkedIn profile information from a PDF using pypdf
- Uses OpenAI API to generate human-like responses based on profile data
- Interactive chatbot web interface with Gradio
-Environment variable management with python-dotenv for API keys
- Easily customizable to work with other profile PDFs or documents

### Technologies Used
- Python 3.11
- openai Python SDK
- pypdf for PDF reading
- python-dotenv for environment variable management
- gradio for chatbot interface
- requests for network calls

### Customization
- To use a different profile PDF, update the file path in the script.
- Modify the prompt or OpenAI parameters in the code for better conversation tuning.

License
