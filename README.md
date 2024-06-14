git clone https://github.com/YOUR_USERNAME/huggingface-model-test.git
cd huggingface-model-test
from transformers import pipeline

classifier = pipeline('sentiment-analysis')
result = classifier("I love using Hugging Face models!")
print(result)
git add test_model.py
git commit -m "Add initial test script for Hugging Face model"
git push origin main
