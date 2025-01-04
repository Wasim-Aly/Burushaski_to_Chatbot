# Burushaski-to-English Chatbot

## Project Overview
The **Burushaski-to-English Chatbot** is a Natural Language Processing (NLP) project designed to bridge the communication gap for speakers of the Burushaski language. This chatbot is capable of translating conversations from Burushaski to English and vice versa, facilitating seamless interaction and preserving the richness of the Burushaski language.

## Features
- **Language Translation**: Translates text from Burushaski to English and English to Burushaski.
- **User-Friendly Interface**: Simple and intuitive design for easy interaction.
- **Machine Learning Powered**: Utilizes advanced NLP techniques and machine learning models to ensure accurate translations.
- **Scalability**: Can be expanded to include more languages in the future.

## Technologies Used
- **Programming Language**: Python
- **Libraries**: 
  - TensorFlow/PyTorch (for model training)
  - Transformers (Hugging Face)
  - Flask (for backend API)
  - Streamlit/React (for frontend interface)
- **Data**: Annotated Burushaski-English datasets
- **Version Control**: Git and GitHub

## Installation
Follow these steps to set up the project locally:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Wasim-Aly/Burushaski_to_Chatbot.git
   ```

2. **Navigate to the Project Directory**:
   ```bash
   cd Burushaski_to_Chatbot
   ```

3. **Create a Virtual Environment**:
   ```bash
   python -m venv myenv
   source myenv/bin/activate  # On Windows: myenv\Scripts\activate
   ```

4. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

5. **Run the Application**:
   ```bash
   python app.py
   ```

6. **Access the Application**:
   Open your browser and go to `http://127.0.0.1:5000`.

## Project Structure
```plaintext
Burushaski_to_Chatbot/
├── data/               # Dataset files
├── models/             # Pretrained and fine-tuned models
├── app.py              # Main application file
├── static/             # Static assets (CSS, JS, images)
├── templates/          # HTML templates
├── README.md           # Project documentation
├── requirements.txt    # Dependencies
└── ...
```

## Usage
1. Launch the chatbot application.
2. Input text in Burushaski or English.
3. Receive translations in the desired language.

## Future Scope
- Expand support for additional languages.
- Implement speech-to-text and text-to-speech functionalities.
- Improve translation accuracy through continuous model training.

## Contributors
- **Wasim Ali** ([GitHub](https://github.com/Wasim-Aly))
- Other team members

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments
We acknowledge the support of:
- Karakoram International University Gilgit
- Data sources and contributors
- The open-source community for providing the tools and libraries necessary for this project.
