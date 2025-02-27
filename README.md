# MediLens

## Overview
MediLens is a cross-platform web application designed to streamline medical prescription analysis in Bangla. It integrates OCR for medical report reading, a chatbot for medical knowledge retrieval, and a fine-tuned Gemini model for enhanced information retrieval. The system is built with a FastAPI backend and a React-based frontend.

## Features
- **Medical Dataset Creation:** A custom dataset was built from scratch and used for training.
- **OCR-Based Report Analysis:** Extracts text from PDFs and images accurately.
- **Bangla Chatbot:** Responds to user queries in Bangla and Banglish.
- **Fine-tuned Gemini Model:** Enhances chatbot responses with additional medical insights.
- **PDF Export:** Allows users to save chats and analysis results in PDF format.

## Technology Stack
### Backend
- **FastAPI** (REST API framework)
- **MongoDB** (Database via `motor` and `pymongo`)
- **Python-dotenv** (Environment management)
- **Uvicorn** (ASGI server)

### Frontend
- **React.js** (UI framework)
- **React Router** (Navigation)
- **Tesseract.js** (OCR integration)
- **Firebase** (Authentication & storage)
- **Framer Motion & DaisyUI** (UI enhancements)

## Installation and Setup

### Prerequisites
- Python (>=3.8)
- Node.js & npm
- MongoDB (local or Atlas)

### Backend Setup
1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo/medilens.git
   cd medilens/backend
   ```
2. Create a virtual environment:
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
4. Run the FastAPI server:
   ```sh
   uvicorn main:app --reload
   ```

### Frontend Setup
1. Navigate to the frontend directory:
   ```sh
   cd ../frontend
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the development server:
   ```sh
   npm run dev
   ```

## Usage
1. Upload a medical prescription as an image or PDF.
2. Extracted text is analyzed and translated into Bangla.
3. Users can query the chatbot for further explanations.
4. Chat history and analysis can be exported as PDFs.

## Contributors
- **Team AI_Sceptic**
  - **Sabbir (1333)**
  - **Niloy (1315)**  
  *Institution: IIT, University of Dhaka*

## License
This project is open-source and available under the MIT License.

