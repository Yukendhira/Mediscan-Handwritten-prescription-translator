# Mediscan-Handwritten-prescription-translator

As part of my project titled MediScan Handwritten Prescription Translator, I extensively utilized Python for implementing deep learning models, image processing, and database management. The project aimed to automate the interpretation of handwritten medical prescriptions using YOLOv5 for object detection and Recurrent Neural Networks (RNN) for text recognition.

Python played a crucial role in multiple stages of the project. I used OpenCV for image preprocessing, including resizing, noise reduction, and contrast adjustment, to enhance the accuracy of text recognition. The YOLOv5 model, implemented in Python, was trained to detect medicine names from prescription images, significantly reducing human errors in manual interpretation.

For text recognition, I leveraged Recurrent Neural Networks (RNN) to process detected text regions and convert them into machine-readable format. To improve accuracy, we compared the recognized words with a medicine database (CSV file) using Python’s fuzzy matching techniques. This helped in correcting potential misinterpretations and ensuring accurate results.

Additionally, the project integrated Google Translate API to provide multilingual support, translating detected medicine names into Tamil, Hindi, Malayalam, and Kannada. This feature enhances accessibility for non-English speakers, making prescription details more understandable.

For data handling, I used Pandas to manage and process large datasets containing medicine names, prices, and company details. The combination of machine learning, natural language processing (NLP), and image processing made this system highly efficient in handling handwritten prescription data.

Through this project, I gained hands-on experience in deep learning, computer vision, and data management using Python, reinforcing my ability to develop AI-driven healthcare solutions.
