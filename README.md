## Gemini Pro Chatbot

A conversational AI chatbot powered by Google's Gemini Pro language model, built with Streamlit and Google's GenerativeAI API.

### **Features**

* Engaging in conversational experiences with Gemini Pro
* Clean and intuitive Streamlit-based user interface
* Clear message history and the distinction between user and model (assistant) roles

### **Prerequisites**

1. **Google Cloud Platform (GCP) Project:** A GCP project with the Google GenerativeAI API enabled.
2. **Google API Key:** A valid Google API key with access to the GenerativeAI API.
3. **Python and Dependencies:** 
    * Python 3.6 or later
    * Install the following packages via pip:
        ```bash
        pip install streamlit google-generativeai dotenv
        ```

### **Setup**

1. **Obtain Google API Key:** Follow the instructions on the Google Cloud Platform console to get your API key.
2. **Create `.env` file:** Create a file named `.env` in the project's root directory and add the following line:
   ```
   GOOGLE_API_KEY=your_api_key 
   ```
   *Replace `your_api_key` with your actual API key.

3. **Install Dependencies:** 
   ```bash
   pip install streamlit google-generativeai dotenv
   ```

### **Running the Chatbot**

1. **Start the Streamlit App:**
   ```bash
   streamlit run app.py 
   ```
   * Replace 'app.py' with the actual name of your main Python file.
2. **Access in Your Browser:** The chatbot will open in your web browser, typically at http://localhost:8501.
### **Notes**

* The `chat_message` component provided in a previous version has been replaced with Streamlit's native support. For further customization, explore Streamlit's documentation on custom components.
* To enhance the chatbot, consider adding features like saving/exporting conversations, error handling, and UI improvements.

### **Code Structure**

* **`app.py` (or similar):** Contains the main Python code with Streamlit components and logic to interface with Gemini Pro.
* **`.env`:** Stores your Google API key securely.

**Please let me know if you'd like any modifications or additional sections to be included in your README file!** 
