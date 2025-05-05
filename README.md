Prescription Label Reader with Voice Output is an innovative project aimed at making healthcare more accessible, especially for elderly and visually impaired patients. Many individuals in these groups struggle to read prescription labels due to small fonts, unclear handwriting, or poor eyesight. Misinterpretation of medication instructions can lead to dangerous outcomes. To solve this problem, this project uses modern deep learning techniques to extract text from prescription labels and convert it into speech. This allows patients to simply listen to their medication instructions, ensuring safety and ease of use.

The solution is built using PaddleOCR, a powerful optical character recognition tool based on PaddlePaddle's deep learning framework. It effectively detects and extracts printed text from images of prescriptions. Once the text is extracted, the Google Text-to-Speech (gTTS) library is used to transform this text into an audio message. The final output is a clear voice reading that informs the user about the medicine name, dosage, and other important instructions.

The system workflow is simple and efficient. First, the user provides an image of the prescription by uploading it or capturing it through a camera. Next, PaddleOCR processes the image and retrieves the text information. This text is then passed to gTTS, which converts it into speech and plays it for the user. This voice output can be particularly useful for those who have difficulty reading or are not comfortable with written language.

This project is especially beneficial in the healthcare domain as it empowers vulnerable patients to take control of their medication without confusion. It reduces dependency, increases confidence, and ensures that medication is taken correctly. However, challenges like poor image quality, handwritten prescriptions, or abbreviated medical terms may affect OCR accuracy. These can be addressed in future improvements.

Future enhancements to the project could include support for regional languages, integration with mobile health apps, and features like dosage tracking, alerts, or caregiver notifications. Overall, this project offers a practical, real-world application of AI and machine learning to solve a critical problem in healthcare accessibility.

Approach: You need to apply OCR techniques to extract the text data from the prescriptions and convert them into speech.

installations done: paddleOCR paddlepaddle gTTS

Project Title: Real Time Prescription Label Reading

Technologies: Deep Learning Technology (Computer Vision)

Domain: Healthcare

Project Difficulties level: Intermediate
