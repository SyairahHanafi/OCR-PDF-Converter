OCR to PDF Converter
by Syairah Hanafi

This mini project is a Jupyter Notebook-based OCR (Optical Character Recognition) to PDF converter. It extracts text from images using Tesseract OCR and converts them into a searchable PDF. This is useful for digitizing scanned documents, receipts, or handwritten notes.

Features
- Converts images to text using `pytesseract`.
- Supports JPG, PNG, and PDF input files.
- Generates a searchable PDF from extracted text.
- Uses `pdf2image` to handle PDFs with images.

Installation
1. Make sure you have Python installed, then install the required dependencies:

pip install pytesseract pdf2image opencv-python fpdf

2. Install Tesseract-OCR:  
[Download Here](https://github.com/UB-Mannheim/tesseract/wiki)

How to Use
1. Open `OCR_to_PDF.ipynb` in Jupyter Notebook or Google Colab.  
2. Upload an image or a scanned PDF.  
3. Run the notebook to extract text and save it as a searchable PDF.  

Future Improvements  
- Add a simple GUI  
- Support multiple pages in PDFs  

## License  
This project is open-source under the MIT License.  

