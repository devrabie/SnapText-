# SnapText 📷➡️📝

**SnapText** is a powerful API project designed to extract text from images hosted via URLs. It utilizes the Tesseract OCR library with FastAPI to provide an easy and fast interface for converting images into text.

### Features ✨
- **Multilingual Support**: Can detect text from images in various languages.
- **Automatic Language Detection**: Processes images and detects text automatically without needing a specific language input.
- **User-Friendly**: Allows you to extract text easily by simply providing the image URL.
- **High Performance**: Built on FastAPI to ensure fast and reliable responses.

### Use Cases 🚀
You can use SnapText to extract text from images in applications such as:
- **Text processing** from documents and digital images.
- **Text recognition** in scanning and search applications.
- **Data analysis** from images in an automated manner.

### Getting Started 🛠️
1. **Install dependencies**: Install the required libraries using:
   ```bash
   pip install -r requirements.txt
   ```
2. **Run the application**: Start the server with:
   ```bash
   uvicorn main:app --reload
   ```
3. **Use the interactive documentation**: Visit `/docs` in your browser to interact with the API directly.

