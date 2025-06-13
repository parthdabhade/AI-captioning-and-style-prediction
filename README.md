# AI-captioning-and-style-prediction
This project leverages OpenAI’s CLIP (Contrastive Language-Image Pretraining) model to generate intelligent, style-aware captions for input images. By combining visual understanding, text matching, and aesthetic classification, this system produces contextually aligned and stylistically relevant image descriptions.

✨ Key Features
1. Aesthetic Style Detection: Automatically classifies an image into one of several design styles (e.g., Minimalist, Vintage, Bohemian, etc.) using CLIP’s visual-text alignment capabilities.
2. Style-Based Caption Filtering: Filters a curated list of caption candidates based on keywords tied to the predicted style, increasing semantic and emotional alignment.
3. CLIP-Based Caption Matching: Uses cosine similarity between image and text embeddings to rank and return the top-matching captions.
4. User-Defined Caption Pool: Allows flexible extension by customizing or expanding the pool of candidate captions.
5. Image Display Support: Displays the input image alongside the predicted style and top caption matches.

🚀 Why This Project Stands Out
Unlike traditional caption generators that rely purely on object recognition or fixed templates, this system:
1. Understands aesthetics and mood, not just contents.
2. Uses multi-modal deep learning (vision + language) to make captioning intelligent and flexible.
3. Supports a human-in-the-loop design where curated captions reflect branding, tone, or thematic goals (great for marketing, travel, or lifestyle content).
4. Can be extended for personalized captioning, recommendation systems, or visual storytelling tools.


🔧 Technologies Used

OpenAI CLIP (ViT-B/32)

HuggingFace Transformers

PyTorch

PIL (Pillow)

scikit-learn (cosine similarity)

Jupyter or VS code execution


📁 Use Cases

Social media content creation

Lifestyle product promotion

Aesthetic-based image sorting or cataloging

Visual mood boards or galleries

Creative writing or journaling prompts


🧠 Future Ideas

Integrate real-time image upload & UI using Streamlit or Gradio.

Auto-generate new captions via language models based on the detected aesthetic.

Incorporate more fine-grained or user-trainable style categories.

Extend to video frame captioning or image storytelling.
