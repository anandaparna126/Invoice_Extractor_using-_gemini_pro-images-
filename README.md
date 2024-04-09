OCR Extractor: Generative AI Project
OCR Extractor is a cutting-edge application designed to leverage the power of generative AI for extracting detailed information from images. Using Gemini Pro's capabilities, this project aims to simplify the process of understanding and extracting text from various image formats, including invoices, letters, and documents.

Features
Image Upload: Users can upload images in formats such as JPG, JPEG, PNG, and PDF.
Custom Queries: Allows users to input custom questions or queries regarding the content of the uploaded image.
AI-Powered Analysis: Utilizes Gemini Pro for generative AI analysis, providing detailed responses based on the image content.
User-Friendly Interface: Built with Streamlit, offering a simple and interactive web interface.
Installation and Setup
Before you begin, ensure you have Python installed on your system. This project requires Python 3.7 or later.

Clone the Repository

bash
Copy code
git clone https://github.com/anandaparna126/ocr-extractor.git
cd ocr-extractor
Install Dependencies

Use pip to install the required Python packages.

bash
Copy code
pip install -r requirements.txt
Environment Variables

Set up your .env file with your Google API key:

makefile
Copy code
GOOGLE_API_KEY="your_google_api_key_here"
Run the Application

Start the Streamlit application.

bash
Copy code
streamlit run app.py
Open in Browser

Navigate to the URL provided by Streamlit, usually http://localhost:8501, to use the application.

Usage
Start the Application: Follow the installation steps to start the application.
Upload an Image: Click on the "Choose an image..." button to upload an image file.
Enter Your Query: Type in what detail you are looking for in the text input field.
Extract Details: Click on the "Click Me" button to process the image and query.
View Results: The application will display the extracted details based on your query.
Technologies Used
Python: The primary programming language used.
Streamlit: For creating the web interface.
Google Generative AI (Gemini Pro): For processing and analyzing the image data.
The Python Imaging Library (PIL): For handling image files.
Contributions
Contributions are welcome! If you have improvements or bug fixes, please feel free to fork the repository and submit a pull request.
