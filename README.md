Project Overview:

This project is inspired by the 1996 research paper "Facial Dominance of West Point Cadets as a Predictor of Later Military Rank" by Mueller and Mazur. Their pioneering study identified a potential link between subtle facial features and long-term career success. However, the original analysis relied on subjective assessments by human judges and did not utilize modern machine learning or generative AI techniques.

To advance this line of inquiry, this project employs Llama 3.3—a generative AI model developed by Meta—to extract hidden features from the facial expressions of 50 British Royal Navy Officers from the 18th century. Using these features, a Logistic Regression model is constructed to explore the relationship between facial characteristics and career outcomes.

Key Contributions:

1. Deployment of GenAI via Ollama: The project demonstrates how to use Llama 3.3 locally with the Ollama platform to extract meaningful facial features from historical portrait images.

2. Application of Machine Learning: A Logistic Regression model is used to classify officers as successful or unsuccessful based on their career outcomes, using the extracted facial features.

Data Pipeline: 

The project includes functions to:

1. Convert portrait images into structured data capturing facial descriptors,

2. Process and clean the dataset,

3. Evaluate feature importance using the Bootstrap method,

4. Select key features based on a predefined threshold for model training.

This project not only replicates the spirit of Mueller and Mazur’s original work but also integrates contemporary AI tools to provide a more scalable and reproducible approach to facial feature analysis.

