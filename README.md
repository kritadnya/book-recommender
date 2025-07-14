# Semantic Book Recommender
This is a book recommender project using LLMs - HuggingFaceEmbeddings for LLM and Gradio for front end.
This image shows the front end of the project.
<img width="1920" height="858" alt="image" src="https://github.com/user-attachments/assets/64fdb9ac-2159-4b78-970d-c715cdd5c9c7" />
Each book also displays the description.
<img width="1920" height="787" alt="image" src="https://github.com/user-attachments/assets/2c2d565b-3061-490d-b9bf-9a753fd4e318" />

## 🧠 How It Works

1. Loads and embeds book descriptions using HuggingFace sentence transformers.
2. Splits and stores the text in a vector database (Chroma).
3. Accepts a natural language query from the user.
4. Retrieves semantically similar books using vector similarity.
5. Applies optional filtering based on category and emotional tone.
6. Displays top results with titles, thumbnails, and descriptions.


