# Abstract

QuranGPT is a natural language processing (NLP) project aimed at generating textual embeddings for Quran verses using OpenAI's GPT-4 model. The project is designed to provide researchers and developers with a comprehensive and structured dataset of Quranic verses, complete with accurate Arabic and English translations, and GPT-4 embeddings. We believe that QuranGPT represents a significant step forward in the field of NLP and Islamic studies, providing researchers with a powerful tool for analyzing and understanding the Holy Quran.

# Introduction

The Holy Quran is the central religious text of Islam, providing guidance and insights into the teachings of Islam. Despite its importance, the Quran can be challenging to study and analyze, particularly given the complexity of the Arabic language. In recent years, natural language processing (NLP) has emerged as a powerful tool for analyzing text data, offering researchers new ways to uncover insights and patterns in large datasets.

QuranGPT is a project that leverages NLP techniques to generate textual embeddings for Quran verses using OpenAI's GPT-4 model. This provides researchers with a powerful tool for studying and analyzing the Quran. The project also offers a comprehensive and structured dataset of Quranic verses, complete with accurate Arabic and English translations, and GPT-4 embeddings.

QuranGPT represents a significant step forward in the field of NLP and Islamic studies, providing researchers with a powerful tool for analyzing and understanding the Holy Quran. We believe that this project has significant potential for advancing research in this area and facilitating new insights into the teachings of Islam and the Quranic text.

## Features

- Generate embeddings for Quran verses using GPT-4
- Visualize the distribution of the embeddings in a 3D scatter plot
- Group verses by Surah and assign unique colors for easier identification
- Export the visualization as an interactive HTML file

## Libraries:
- pandas: A library for data manipulation and analysis.
- numpy: A library for numerical operations and working with arrays.
- sklearn.manifold.TSNE: A module containing the t-SNE algorithm for dimensionality reduction and visualization.
- transformers: A library containing state-of-the-art natural language processing models.
- plotly.graph_objs: A library for creating interactive and customizable visualizations.
- torch: A library for scientific computing and deep learning.
- openai: The official OpenAI library for working with the GPT-4 model.
- time: A built-in Python module for working with time-related functions.
- logging: A built-in Python module for tracking events in the application.
- os: A built-in Python module for interacting with the operating system.

## Configuration:
- openai.api_key: Set the OpenAI API key for authentication. Make sure to replace "Use your own key here" with your personal API key.
- logging.basicConfig(level=logging.INFO): Configure the logging level. In this case, the logging level is set to INFO, which will provide more detailed output than the default WARNING level. Other logging levels include DEBUG, ERROR, and CRITICAL.

## Data
Kindly find the collected data in this folder : 
- QuranGPT : https://drive.google.com/drive/folders/1VyMTs6_H07RMRYM8jn-SFtM7XbeiSFEU?usp=share_link

## Acknowledgements

- This project utilizes the OpenAI GPT-4 language model for generating embeddings.
- The t-SNE algorithm is used for dimensionality reduction and visualization, provided by the scikit-learn library.
- Plotly is used for creating interactive 3D scatter plots.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.


