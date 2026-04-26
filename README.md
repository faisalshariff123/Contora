# AccessCanvas
### Accessibility for Creators, Designed for Everyone.

**AccessCanvas** is a full stack web application made to help digital creators, designers, and developers ensure that their content is accessible before it goes live. It automates WCAG 2.2 compliance checks for color contrast and uses AI to generate high quality alt-text and long descriptions.

https://contora-app.onrender.com

---

## Key Features
* **Contrast Analysis:** Automatically calculates contrast ratios against WCAG 2.2 AA standards.
* **OCR Text Extraction:** Uses Tesseract OCR to detect text embedded within images.
* **AI Alt-Text Generation:** Leverages Gemini 2.0 Flash (via OpenRouter) to draft semantic alt text.
* **Plain English Fixes:** Translates complex accessibility errors into actionable design advice.
* **Long Descriptions:** Generates detailed descriptions for complex imagery to assist screen-reader users.

## Tech Stack
### Frontend
* **React**
* **CSS3** with custom variables and keyframe animations

### Backend
* **Python / Flask**
* **Docker**
* **Tesseract OCR** 
* **OpenCV & Pillow** 
* **OpenRouter API** 
* **Gunicorn** 

### DevOps & Deployment
* **Render** 
* **Docker Hub** 

---

## System Architecture
The project is split into two distinct services to optimize performance and scalability:
1.  **Frontend:** A static React application that handles user interactions and image previews.
2.  **Backend:** A containerized Flask API that handles heavy image processing and AI orchestration.

---

## Local Setup

### Prerequisites
* Python 3.11+
* Node.js & npm
* Tesseract OCR installed on your local machine

### 1. Clone the repository
```bash
git clone [https://github.com/faisalshariff123/AccessCanvas.git](https://github.com/faisalshariff123/AccessCanvas.git)
cd Contora
