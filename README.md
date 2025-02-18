# AI Applications with Google Cloud & Vertex AI 🚀

Explore and implement powerful **AI and Machine Learning** solutions using **Google Cloud Platform (GCP)**. This repository demonstrates how to build end-to-end solutions using GCP's comprehensive tools for both **machine learning** and **generative AI**.

`Vertex AI`, `Document AI`, `Optical Character Recognition (OCR)`, `Form Parsing`, `Gemini`, `Text Generation`, `Image and Video Analysis`, `Function Calling Techniques`, `Multimodal Content Generation`, `LangChain`, `Retrieval Augmented Generation (RAG)`, `Large Language Models (LLMs)`, `Search and Retrieval Workflows`, `Imagen`, `Image Recognition`, `Natural Language Processing (NLP)`, `Image Generation`

## Contents 📚

| 🏷 **Title**            | 📄 **Description**                                   | 🛠 **Technology/Tool**    | 🔗 **Link**      |
|-------------------------|------------------------------------------------------|---------------------------|-------------------|
| **Classifying Images with a Linear Model** |Classifying flower images using a linear model with the `tf.keras` API, covering data examination, model implementation, and prediction visualization. | `Vertex AI`, `TensorFlow`, `Numpy`,`Matplotlib` | [Notebook](notebook/classifying_images_with_a_linear_model.ipynb)|
| **Classifying Images with a NN and DNN Model** | Classify the flowers images using a Neural Network (NN) and a Deep Neural Network (DNN) model. Define helper functions, training, and evaluating both a NN and a DNN. | `Vertex AI`,`TensorFlow`, `NN`, `DNN`| [Notebook](notebook/classify_images_nn_dnn.ipynb) |
| **Classifying Images using Dropout and Batchnorm Layer** | Demonstrates building a neural network to classify the flowers images using dropout and batch normalization layers. Covers defining helper functions and applying dropout and batch normalization layers in the network. | `Vertex AI`, `TensorFlow`, `Dropout`, `Batch Normalization`| [Notebook](notebook/classify_images_dropout_batchnorm.ipynb) |
| **MNIST Image Classification with TensorFlow** | Implementing a simple linear image model on the MNIST dataset using `tf.keras`. | `Vertex AI`,`TensorFlow`,`Matplotlib`,`Numpy` | [Notebook](notebook/mnist_linear.ipynb) |
| **MNIST Image Classification with TensorFlow on Vertex AI** | Demonstrating the implementation of various image models on the MNIST dataset using the `tf.keras` API. Covering building a Dense Neural Network (DNN) for image classification, utilizing dropout in DNNs, applying Convolutional Neural Networks (CNN), and deploying an image classification model using Google Cloud's `Vertex AI`. | `Vertex AI`, `TensorFlow`,`Numpy`, `Matplotlib` | [Notebook](notebook/mnist_image_classification_vertex_ai.ipynb) |
| **Classifying Structured Data using Keras Preprocessing Layers** | Classifying structured data by loading a CSV file with `Pandas`, creating an input pipeline for batching and shuffling rows using `tf.data`, mapping CSV columns to features with Keras Preprocessing layers, and building, training, and evaluating a model using `Tensorflow`.| `Vertex AI`, `Scikit-learn`, `TensorFlow`,`Pandas`,`Numpy` | [Notebook](notebook/preprocessing_layers.ipynb) |
| **TensorFlow Dataset API** | Using `tf.data` to read data from memory and disk, apply it in a training loop, and build production input pipelines with feature engineering techniques such as batching and shuffling. | `Numpy`, `TensorFlow`,`Vertex AI` | [Notebook](notebook/tf_dataset_api.ipynb) |
| **Exploratory Data Analysis Using Python and BigQuery** | Analyzing a Pandas DataFrame, creating Seaborn plots for Exploratory Data Analysis in Python, writing SQL queries to extract specific fields from a BigQuery dataset, and performing exploratory analysis in BigQuery. | `BigQuery`, `SQL`,`Pandas`, `Seaborn` | [Notebook](notebook/explore_data_BQ_python.ipynb) |
| **Introducing the Keras Sequential API on Vertex AI Platform** | Demonstrates building a DNN model using the Keras Sequential API and utilizing feature columns. Includes training the model, saving/loading, deploying on Google Cloud Platform, and making predictions with the deployed model on Vertex AI. | `Keras Sequential API`, `Vertex AI`, `Deep Neural Networks`, `Google Cloud Platform` | [Notebook](notebook/keras_sequential_api_vertex_ai.ipynb) |
| **Performing Basic Feature Engineering in Keras** | Covers creating an input pipeline using `tf.data` and engineering features to construct categorical, crossed, and numerical feature columns. | `Keras`, `Feature Engineering`, `tf.data` | [Notebook](notebook/basic_feature_engineering_keras.ipynb) |
| **Advanced Feature Engineering in Keras** | Explores advanced feature engineering techniques, including processing temporal feature columns, using Lambda layers for geolocation feature engineering, and creating bucketized and crossed feature columns. | `Keras`, `Feature Engineering`, `Lambda Layers` | [Notebook](notebook/advanced_feature_engineering_keras.ipynb) |
| **Training at Scale with the Vertex AI Training Service** | Demonstrates how to scale model training using Google Cloud Vertex AI Training Service. Covers organizing training code into a Python package, training models with cloud infrastructure, and optionally running training packages in Docker containers and pushing Docker images to a registry. | `Vertex AI`, `Cloud Training`, `Docker`, `Google Cloud` | [Notebook](notebook/training_at_scale_vertex_ai.ipynb) |
| **Deploying an Explainable Image Model with Vertex AI** | Train a classification model on image data and deploy it to Vertex AI to serve predictions with explanations, including feature attributions. Covers exploring the dataset, building and training a custom image classification model, deploying the model to an endpoint, serving predictions with explanations, and visualizing feature attributions using Integrated Gradients. | `Vertex AI`, `Image Classification`, `Integrated Gradients`, `Explainability` | [Notebook](notebook/xai_image_vertex_ai.ipynb) |
| **Feature Store: Streaming Ingestion SDK** | Demonstrates ingesting features from a `Pandas DataFrame` into Vertex AI Feature Store using the `write_feature_values` method from the Vertex AI SDK. Covers creating a `Feature Store`, adding a new `Entity Type`, and ingesting feature values into the `Feature Store`'s `Entity Types`. | `Vertex AI Feature Store`, `Pandas`, `Streaming Ingestion` | [Notebook](notebook/feature_store_streaming_ingestion_sdk.ipynb) |
| **Using Machine Learning APIs** | Demonstrating the use of various Google Cloud ML APIs, including Translate API for language translation, Vision API for sign translation, Sentiment Analysis with the Language API, and Speech API for speech-to-text conversion. | `Translate API`, `Vision API`, `Language API`, `Speech API` | [Notebook](notebook/ml_apis_usage.ipynb) |
| **Content-Based Filtering using Low Level TensorFlow Operations** | Demonstrates creating and computing a user feature matrix, determining user positions in the feature embedding space, and generating movie recommendations based on similarity measures between user and movie feature vectors. | `TensorFlow`, `Vertex AI Workbench`, `Content-Based Filtering`| [Notebook](recommendation-systems/content_based_filtering_tensorflow_operations.ipynb) |
| **Collaborative Filtering on the MovieLens Dataset** | Demonstrates collaborative filtering with the MovieLens dataset, including data exploration in BigQuery, generating user-specific recommendations, and recommending items to a group of users. | `BigQuery`, `Collaborative Filtering`, `Recommendations`, `MovieLens Dataset` | [Notebook](recommendation-systems/collaborative_filtering_movielens.ipynb) |
| **Hybrid Recommendations with the MovieLens Dataset** | Covers extracting user and product factors from a BigQuery Matrix Factorization Model and formatting inputs for a BigQuery Hybrid Recommendation Model. | `BigQuery`, `Matrix Factorization`, `Hybrid Recommendations`, `MovieLens Dataset` | [Notebook](recommendation-systems/hybrid_recommendations_movielens.ipynb) |
| **Contextual Bandits for Recommendations with TensorFlow and TF-Agents** | Builds a Contextual Bandits agent to recommend movies from the MovieLens dataset. Includes steps for installing libraries, configuring the MovieLens environment, initializing the agent, linking evaluation metrics, configuring the replay buffer, setting up and training the model, and observing results using Vertex AI TensorBoard. | `TensorFlow`, `TF-Agents`, `Contextual Bandits`, `MovieLens Dataset`, `Vertex AI TensorBoard` | [Notebook](recommendation-systems/contextual_bandits_recommendations_movielens.ipynb) |
| **Prompt Design - Best Practices** | Covers best practices for prompt engineering to enhance response quality. Includes techniques such as being concise, specific, asking one task at a time, converting generative tasks into classification tasks, and improving response quality by including examples. | `Prompt Engineering` | [Notebook](notebook/prompt_design_best_practices.ipynb) |
| **Getting Started with the Vertex AI PaLM API & Python SDK** | Overview of using the Vertex AI PaLM API with the Python SDK. Includes testing with the [Generative AI Studio](https://cloud.google.com/generative-ai-studio), executing cURL commands in Cloud Shell, and using the Python SDK in a Jupyter notebook. Covers installing the Python SDK, using the Vertex AI PaLM API for text generation with `text-bison@001`, chat with `chat-bison@001`, and embeddings with `textembedding-gecko@001`. | `Vertex AI`, `PaLM API`, `Python SDK`, `Generative AI Studio` | [Notebook](notebook/intro_palm_api.ipynb) |
| **Getting Started with Text Embeddings + Vertex AI Vector Search** | Introduction to embeddings and their role in solving business challenges. Covers understanding text with Vertex AI Text Embeddings, using Vertex AI Vector Search for fast embedding retrieval, and grounding LLM outputs with Vector Search. | `Vertex AI Workbench`, `Vector Search`, `LLMs`,`BigQuery`,`Cloud Storage` | [Notebook](notebook/intro-textemb-vectorsearch.ipynb) |
| **Text Embeddings for a Vector Store using LangChain** | Demonstrates storing documents in a vector store database using LangChain. Covers the use of various LangChain classes to split, chunk, and embed documents, and querying the vector store with Retrievers. | `LangChain`, `Vector Store`, `Retrievers`,`Chroma` | [Notebook](langchain-vertex-ai/create_text_embeddings_using_langchain.ipynb) |
| **Text Generation with RAG, LangChain, and Vertex AI** | Demonstrating content generation using the Gemini Python SDK. Covers preparing a private knowledge base using DocArray for indexing document embeddings, generating embeddings with Gemini's `embedding-001` model, creating a query-based retrieval system, and implementing Retrieval-Augmented Generation (RAG) with the `gemini-pro` model to enhance generated results. | `Gemini`, `RAG`, `LangChain`, `Vertex AI`, `DocArray` | [Notebook](langchain-vertex-ai/gemini_langchain_rag.ipynb) |
| **Knowledge Based System with Vertex AI Vector Search, LangChain, and Gemini** | Demonstrates generating embeddings for a dataset, adding them to Cloud Storage, and creating an index in Vertex AI Vector Search. Leverages similarity metrics to evaluate and retrieve relevant knowledge base results, and utilizes LangChain to query Vertex AI Vector Search to provide context for prompts submitted to Gemini. | `Vertex AI`, `Vector Search`, `LangChain`, `Gemini`, `Cloud Storage` | [Notebook](langchain-vertex-ai/gemini_langchain_vector_search_rag.ipynb) |
| **Question Answering with LangChain and Vertex AI** | Demonstrates using `gemini-pro` to answer questions. Documents are indexed as embeddings in a Vector Store using Chroma. Implements a Retrieval Augmented Generation (RAG) application with LangChain to answer questions by grounding responses using the indexed documents. | `Vertex AI`, `LangChain`, `Gemini`, `Chroma`, `RAG` | [Notebook](langchain-vertex-ai/qa_retrieval_augmentation_generation.ipynb) |
| **Call Gemini using the OpenAI Library** | Explains how to configure the OpenAI SDK for the Gemini Chat Completions API. Covers sending chat completions requests, streaming chat completions responses, sending multimodal requests, and making function-calling requests, including those with the `tool_choice` parameter. | `OpenAI SDK`, `Gemini`, `Chat Completions`, `Function Calling` | [Notebook](notebook/call_gemini_openai_library.ipynb) |
| **Differential Privacy in Machine Learning with TensorFlow Privacy** | Demonstrates the use of differential privacy in machine learning with TensorFlow Privacy. Covers wrapping existing optimizers into their differentially private counterparts, checking hyperparameters specific to differential privacy, and measuring privacy guarantees with TensorFlow Privacy analysis tools. | `TensorFlow Privacy`, `Differential Privacy`, `Machine Learning` | [Notebook](privacy-safety/privacy_dpsgd.ipynb) |
| **Safeguarding with Vertex AI Gemini API** | Demonstrates inspecting safety ratings from the Vertex AI Gemini API and setting a safety threshold to filter responses. Covers calling the Vertex AI Gemini API, reviewing safety ratings, and defining a custom threshold for filtering responses based on specific needs. | `Vertex AI Gemini`, `Safety Ratings`, `API Filtering` | [Notebook](privacy-safety/gemini_safety_ratings.ipynb) |
| **Getting Started with Gemini for Pair Programming** | Introduction to using Gemini for pair programming. Covers setup, collaborative coding features for development tasks. | `Gemini`, `Pair Programming`, `AI Assistance` | [Notebook](pair-programming/getting_started_gemini_pair_programming.ipynb) |
| **Using a String Template with Gemini for Pair Programming** | Explore the use of string templates with Gemini to enhance pair programming workflows. Customize templates to streamline interactions and improve collaboration. | `Gemini`, `String Templates`, `Pair Programming` | [Notebook](pair-programming/string_template_gemini_pair_programming.ipynb) |
| **Pair Programming Scenarios with Gemini** | Utilize Gemini for various pair programming tasks, including improving existing code, simplifying code, writing test cases, enhancing efficiency, and debugging. | `Gemini`, `Pair Programming`, `Code Optimization`, `Debugging` | [Notebook](pair-programming/pair_programming_scenarios_gemini.ipynb) |
| **Technical Debt with Gemini** | Leverage Gemini to address technical debt by explaining and documenting complex codebases, simplifying maintenance and understanding. | `Gemini`, `Technical Debt`, `Code Documentation`, `Code Explanation` | [Notebook](pair-programming/technical_debt_gemini.ipynb) |
| **Getting Started with Vertex AI Text Embeddings API** | Introduction to using the Vertex AI Text-Embeddings API for generating embeddings. | `Vertex AI`, `Text Embeddings`| [Notebook](text-embeddings/getting_started_text_embeddings_vertex_ai.ipynb) |
| **Vertex Forecasting and Time Series** | Covers building forecasting solutions with Google Cloud. Focuses on sequence models and time series foundations, following an end-to-end workflow from data preparation to model development and deployment with Vertex AI. Includes a retail use case for applying forecasting models. | `Vertex AI`, `Time Series`, `Forecasting`, `Google Cloud` | [Notebook](forecasting) |







## Credits 🙌

## Contributing 🤝

Contributions are welcome! If you have any ideas or improvements, feel free to submit a pull request.

## License 📄

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.