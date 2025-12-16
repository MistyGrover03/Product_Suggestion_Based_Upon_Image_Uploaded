📌 Overview

This project is an image-based fashion product recommendation system.
Users upload a product image, and the system retrieves visually similar products using image embeddings and a vector database, with optional filters for price and rating.

🧠 Tech Stack

Python

OpenCLIP – Image embedding generation

LanceDB – Vector similarity search

Streamlit – Interactive web interface

⚙️ How It Works

Product images are converted into vector embeddings

Embeddings are stored in LanceDB along with price and rating metadata

Uploaded images are matched using similarity search

Results are filtered based on:

💰 Maximum budget

⭐ Minimum rating

🚀 Features

Image-based fashion product search

Fast and scalable vector similarity retrieval

Budget and rating-based filtering

Clean and interactive Streamlit UI

🎯 Use Case

Fashion product discovery

Visual search for e-commerce platforms

Recommendation systems using computer vision
