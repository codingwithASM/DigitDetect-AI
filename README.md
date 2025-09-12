# Handwritten_digit_recognition
This is a repository for my project on Handwritten Digit Classification .

#Directory Structure for running code
# ***Directory Structure***
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
├── ml_model/                   # Folder for your DigitDetect ML model
│   └── mnist_cnn_model.h5      # Your handwritten digit recognition model
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
