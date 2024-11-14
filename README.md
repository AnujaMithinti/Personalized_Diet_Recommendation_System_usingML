Technologies
The project is created with:

Python: 3.10.8
fastapi 0.88.0
uvicorn 0.20.0
scikit-learn 1.1.3
Pandas: 1.5.1
Streamlit: 1.16.0
streamlit-echarts 1.24.1
Numpy: 1.21.5
beautifulsoup4 4.11.1
 

Project Overview: Diet Recommendation System
This Diet Recommendation System is designed to help users make informed decisions about their diet based on their preferences, with a focus on protein-rich vegan options. The goal is to provide personalized recommendations that promote healthy eating habits by leveraging machine learning and content-based filtering techniques.

Need for the Project
Health and Wellness Focus: With increasing awareness about health and fitness, many people are shifting to vegan diets for health, ethical, and environmental reasons. However, individuals following a vegan diet often struggle to ensure they are getting sufficient nutrients, particularly protein, from plant-based sources. This system aims to address this issue by suggesting protein-rich vegan diets tailored to individual preferences.

Personalized Recommendations: People have different dietary needs and taste preferences. A one-size-fits-all approach isn't effective. The system personalizes recommendations based on user inputs like preferences and nutritional goals (e.g., protein intake).

Convenience and Accessibility: As more people look to manage their diets with minimal effort, a web-based recommendation system provides easy access and user interaction, guiding users towards healthier meal options.



Why These Technologies Were Chosen
Python is a go-to language for data science and machine learning due to its vast ecosystem of libraries.
FastAPI and Uvicorn enable the system to scale efficiently with asynchronous capabilities, making it a great choice for handling multiple user requests concurrently.
Streamlit provides an easy-to-develop and interactive interface for displaying diet recommendations and visualizations, making it suitable for this project’s user-friendly approach.
scikit-learn allows for the implementation of the machine learning model for diet recommendation, while Pandas helps process and manipulate nutritional data.
streamlit-echarts adds interactivity to the frontend by allowing users to visualize their diet recommendations through charts.
BeautifulSoup facilitates easy data scraping, which can help enrich the system’s recommendations with up-to-date information from the web.
