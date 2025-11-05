# StyleBlend
AI-Powered Virtual Hairstyle Try-On & Personalized Hairstyle Recommendations

StyleBlend is a generative-AI powered web application that allows users to
✅ Upload a photo
✅ Detect their face shape
✅ Get top personalized hairstyle recommendations
✅ Try on hairstyles virtually in real-time
✅ View trending hairstyles extracted from social media
-------------------------------------------------------------------------------------------------------------
| Feature                  | Description                                                                    |
| ------------------------ | ------------------------------------------------------------------------------ |
| Face Shape Detection     | CNN-based model classifying face shapes (oval, round, square, heart, diamond)  |
| Hairstyle Recommendation | StyleGAN + similarity analysis for personalized top-5 hairstyle matches        |
| Virtual Try-On           | High-quality hairstyle blending using latent space manipulation & segmentation |
| Trend Extraction         | Pulls trending hairstyles from social platforms to suggest modern looks        |
| User Interaction         | Upload image → Analyze → Recommend → Try-On                                    |
-------------------------------------------------------------------------------------------------------------

-----------------------------------------------------------------------
| Area            | Tech                                              |
| --------------- | ------------------------------------------------- |
| Deep Learning   | PyTorch / TensorFlow, StyleGAN2                   |
| Face Processing | Dlib, DeepFace, OpenCV                            |
| Web App         | Streamlit / Flask (your implementation)           |
| Deployment      | Google Colab GPU, Drive for model storage         |
| Libraries       | NumPy, Matplotlib, Selenium (for trends scraping) |
-----------------------------------------------------------------------

Dataset
FFHQ Face dataset
Custom curated hairstyle dataset (400 images)
Trending hairstyles scraped from Instagram

StyleBlend/
 ┣ src/
 ┃ ┣ models/
 ┃ ┣ face_shape_classifier/
 ┃ ┣ stylegan/
 ┃ ┣ trend_scraper/
 ┃ ┗ utils/
 ┣ assets/
 ┣ notebooks/
 ┣ results/
 ┣ requirements.txt
 ┣ README.md
 ┗ LICENSE

