
[![Watch the video](https://raw.githubusercontent.com/codingwithASM/DigitDetect-AI/refs/heads/main/video.mp4)]

# Handwritten_digit_recognition
This is a repository for my project on Handwritten Digit Classification .


## If you want to run the project, you simply need to download the **"Handwritten_digit_classification_complete_file.ipynb"** and run it in google colab.
Files such as ipynb files used for training models ,trained models and images are placed in **InternshipProject** folder. 

**required_files.zip** contains these files in zip format.   

# Directory Structure Created on running **"Handwritten_digit_classification_complete_file.ipynb"**
```
your_project_folder/
├── app.py                      # Your main Flask application file
├── chatbot.py                  # Your chatbot logic file
├── requirements.txt            # Python dependencies for both the website and chatbot
│
├── fine_tuned_chatbot_model/   # Folder for chatbot's model files
│   ├── vocab.txt               # Tokenizer vocabulary
│   ├── special_tokens_map.json
│   ├── tokenizer_config.json
│   └── label_encoder.json      # Encoded labels for the chatbot model
│
├── mnist_cnn_model.h5          # Your handwritten digit recognition model
│   
│
├── quantized_chatbot_model.onnx # Your ONNX-format chatbot model
├── new_json.json               # JSON file containing chatbot responses
│
├── static/
│   ├── css/
│   │   └── style.css           # Your updated CSS file with chatbot pop-up styles
│   │
│   ├── js/
│   │   └── script.js           # Your updated JS file with the chatbot toggle logic
│   │
│   └── images/
│       ├── bot.gif             # Your chatbot icon GIF
│       └── favicon.ico         # Your website favicon
│
└── templates/
    ├── index.html              # Your updated HTML file with the chatbot pop-up structure
    └── result.html             # The HTML file for showing digit detection results
```
