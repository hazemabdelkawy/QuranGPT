# Quran GPT

Quran GPT is a project that leverages the power of the GPT-4 language model to generate meaningful embeddings for Quran verses. This project not only generates embeddings for the verses but also visualizes the distribution of these embeddings using t-SNE in a 3D scatter plot. By doing so, it helps to explore and analyze the relationships between Quran verses, providing a new perspective on the Holy Quran.

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


