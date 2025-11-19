{
  "title": "A Lightweight Neural Network for Arabic Sign Language Recognition Using Mediapipe Landmarks",
  "date": "2024-11-01",
  "pubtype": "Preprint",
  "featured": true,
  "description": "A study presenting a lightweight machine learning model for Arabic Sign Language recognition using Mediapipe hand-landmark features, achieving high accuracy on both public and newly collected Lebanese-dialect gesture datasets while requiring far fewer parameters than YOLO-based methods.",
  "tags": ["Arabic Sign Language", "Machine Learning", "Artificial Intelligence", "Computer Vision"],
  "link": "/files/sign_language.pdf",
  "weight": 500,
  "sitemap": {
    "priority": 0.8
  }
}

Hearing impairment affects approximately 6% of the global population, creating significant barriers to communication and social integration for millions of people. Sign language offers a crucial means of communication for the deaf and hard-of-hearing community; however, its widespread adoption and understanding remain limited. This gap is particularly evident in Arabic-speaking regions, where multiple dialects further complicate sign language translation. Additionally, research on Arabic Sign Language (ArSL) has traditionally lagged behind more commonly studied sign languages such as American Sign Language (ASL).
In this work, we propose a lightweight neural network for ArSL recognition that requires only a fraction of the parameters used by state-of-the-art models. Our approach leverages Mediapipe to generate feature vectors using extracted hand landmarks. We evaluate our model on both static hand symbols (using the ArSL21L dataset) and dynamic hand gestures (using a newly collected Lebanese dialect dataset). Crucially, our new in-house dataset fills a gap in public datasets for dynamic ArSL gestures, and we make it available for future research upon request. Experimental results show that our symbols model achieves 97% accuracy, precision, recall, and F1-score on ArSL21L, while the gestures model reaches 100% accuracy on our in-house dataset. These results are competitive with YOLO (You Only Look Once)- based architectures (YOLOv5 and YOLOv7), yet our model requires significantly fewer parameters—on the order of 0.078Mversus millions in YOLO networks. Our findings contribute to the expanding research on sign language recognition for underrepresented languages like ArSL.