# Axe Analytics

Axe Analytics is a web application that leverages the power of Google's Gemini AI to analyze medical images, particularly X-rays, for potential bone fractures and abnormalities. 

## Features

- **AI-Powered Analysis:** Utilizes the Gemini Pro model for accurate and detailed analysis of uploaded X-ray images.
- **User-Friendly Interface:**  Provides a simple and intuitive interface built with Streamlit, allowing users to easily upload images and receive analysis results.
- **Comprehensive Reports:**  Generates detailed reports outlining identified findings, including fracture locations and potential abnormalities.
- **Treatment Recommendations:** Offers recommendations for potential next steps, including suggested treatments based on the analysis.

## Screenshot

![Axe Analytics Screenshot](https://raw.githubusercontent.com/arnab-4/xray_assistant/main/demo.png) 

## Getting Started

1. **Clone the repository:** `git clone https://github.com/your-username/axe-analytics.git`
2. **Install dependencies:** `pip install -r requirements.txt`
3. **Obtain a Gemini API key:** [https://developers.generativeai.google](https://developers.generativeai.google)
4. **Update `configs.py`:**
   - Replace `{Enter Your Gemini API key}` with your actual API key.
   - Customize model parameters and prompts as needed.
5. **Run the application:** `streamlit run app.py`

## Disclaimer

This application is intended for informational and educational purposes only. It is not a substitute for professional medical advice, diagnosis, or treatment.
