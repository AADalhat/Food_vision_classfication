# 🍲 FoodVision – AI Food Recognition App

**FoodVision** is an AI-powered web application that classifies Nigerian foods from images and returns rich metadata like ingredients, nutritional values, ethnicity, and dietary advice.

![demo](assets/demo_screenshot.jpg)

## 🌍 Features

- ✅ Classifies 10 Nigerian dishes using images
- ✅ Displays food name, ethnicity, ingredients, calorie, protein, carbs, fat, and diet type
- ✅ Built with TensorFlow (EfficientNet), Gradio, and deployed on Hugging Face
- ✅ JSON metadata-powered food knowledge system

## 🚀 Try It Live

👉 [Launch on Hugging Face](https://huggingface.co/spaces/AADalhat/food_vision_classification)

## 🧠 Model Information

- Architecture: EfficientNetB3 via Transfer Learning
- Dataset: Custom-labeled Nigerian food images
- Framework: TensorFlow/Keras

## 🧑‍💻 How to Use

```bash
# Clone repo and install dependencies
pip install -r requirements.txt

# Run the Gradio app
python app.py
