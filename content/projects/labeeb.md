{
  "title": "Labeeb",
  "date": "2024-08-11T12:41:05-05:00",
  "link": "https://zeinshehab.github.io/Labeeb/",
  "image": "/img/labeeb.png",
  "description": "Labeeb is the first Lebanese Sign Language translation app, providing real-time offline translation for the Arabic alphabet and common Lebanese signs using lightweight landmark-based machine learning models.",
  "tags": [
    "Machine Learning",
    "TensorFlow",
    "MediaPipe",
    "Computer Vision",
    "Python",
    "Flask",
    "REST APIs",
    "Flutter",
    "Android",
    "iOS",
    "Mobile Development"
  ],
  "fact": "",
  "featured": true,
  "weight": 200
}

Labeeb is the first Lebanese Sign Language translation app, developed to help bridge communication between sign language users and people who do not understand Lebanese Sign Language. The app provides **real-time offline translation** for the Arabic alphabet and common Lebanese signs.

I built the system end-to-end, including **data collection, machine learning models, backend API, and mobile application**. The recognition pipeline uses **MediaPipe landmarks** with lightweight **TensorFlow** models, enabling efficient sign recognition without relying directly on raw image data.

The application combines:

- **Real-time offline sign recognition**, allowing translation without requiring a continuous internet connection.
- **Landmark-based recognition** using MediaPipe and TensorFlow.
- **Static and dynamic sign classification** for different types of signs.
- **Flask REST API** for backend functionality and communication with the application.
- **Flutter mobile frontend** for Android and iOS.
- **Custom sign-language data collection and preprocessing** used to develop the recognition models.

The work on Labeeb also led to a research preprint on **lightweight Arabic Sign Language recognition using landmark-based representations**, exploring efficient models for both static and dynamic sign recognition.