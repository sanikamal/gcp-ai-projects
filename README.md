# AI Applications with Google Cloud & Vertex AI 🚀

Explore and implement powerful **AI and Machine Learning** solutions using **Google Cloud Platform (GCP)**. This repository demonstrates how to build end-to-end solutions using GCP's comprehensive tools for both **machine learning** and **generative AI**.

`Vertex AI`, `Document AI`, `Optical Character Recognition (OCR)`, `Form Parsing`, `Gemini`, `Text Generation`, `Image and Video Analysis`, `Function Calling Techniques`, `Multimodal Content Generation`, `LangChain`, `Retrieval Augmented Generation (RAG)`, `Large Language Models (LLMs)`, `Search and Retrieval Workflows`, `Imagen`, `Image Recognition`, `Natural Language Processing (NLP)`, `Image Generation`

## Contents 📚

| 🏷 **Title**       | 📄 **Description**     | 🛠 **Technology/Library**    | 🔗 **Link**     |
|--------------------|------------------------|-----------------------------|-------------------|
| **Classifying Images with a Linear Model** |Classifying flower images using a linear model with the `tf.keras` API, covering data examination, model implementation, and prediction visualization. | `Vertex AI`, `TensorFlow`, `Numpy`,`Matplotlib` | [Notebook Link](notebook/classifying_images_with_a_linear_model.ipynb)|
| **Classifying Images with a NN and DNN Model** | Classify the flowers images using a Neural Network (NN) and a Deep Neural Network (DNN) model. Define helper functions, training, and evaluating both a NN and a DNN. | `Vertex AI`,`TensorFlow`, `NN`, `DNN`| [Notebook Link](notebook/classify_images_nn_dnn.ipynb) |
| **Classifying Images using Dropout and Batchnorm Layer** | Demonstrates building a neural network to classify the flowers images using dropout and batch normalization layers. Covers defining helper functions and applying dropout and batch normalization layers in the network. | `Vertex AI`, `TensorFlow`, `Dropout`, `Batch Normalization`| [Notebook Link](notebook/classify_images_dropout_batchnorm.ipynb) |
| **MNIST Image Classification with TensorFlow** | Implementing a simple linear image model on the MNIST dataset using `tf.keras`. | `Vertex AI`,`TensorFlow`,`Matplotlib`,`Numpy` | [Notebook Link](notebook/mnist_linear.ipynb) |
| **MNIST Image Classification with TensorFlow on Vertex AI** | Demonstrating the implementation of various image models on the MNIST dataset using the `tf.keras` API. Covering building a Dense Neural Network (DNN) for image classification, utilizing dropout in DNNs, applying Convolutional Neural Networks (CNN), and deploying an image classification model using Google Cloud's `Vertex AI`. | `Vertex AI`, `TensorFlow`,`Numpy`, `Matplotlib` | [Notebook Link](notebook/mnist_image_classification_vertex_ai.ipynb) |
| **Classifying Structured Data using Keras Preprocessing Layers** | Classifying structured data by loading a CSV file with `Pandas`, creating an input pipeline for batching and shuffling rows using `tf.data`, mapping CSV columns to features with Keras Preprocessing layers, and building, training, and evaluating a model using `Tensorflow`.| `Vertex AI`, `Scikit-learn`, `TensorFlow`,`Pandas`,`Numpy` | [Notebook Link](notebook/preprocessing_layers.ipynb) |
| **TensorFlow Dataset API** | Using `tf.data` to read data from memory and disk, apply it in a training loop, and build production input pipelines with feature engineering techniques such as batching and shuffling. | `Numpy`, `TensorFlow`,`Vertex AI` | [Notebook Link](notebook/tf_dataset_api.ipynb) |
| **Exploratory Data Analysis Using Python and BigQuery** | Analyzing a Pandas DataFrame, creating Seaborn plots for Exploratory Data Analysis in Python, writing SQL queries to extract specific fields from a BigQuery dataset, and performing exploratory analysis in BigQuery. | `BigQuery`, `SQL`,`Pandas`, `Seaborn` | [Notebook Link](notebook/explore_data_BQ_python.ipynb) |
| **Using Machine Learning APIs** | Demonstrating the use of various Google Cloud ML APIs, including Translate API for language translation, Vision API for sign translation, Sentiment Analysis with the Language API, and Speech API for speech-to-text conversion. | `Translate API`, `Vision API`, `Language API`, `Speech API` | [Notebook Link](notebook/ml_apis_usage.ipynb) |
| **Content-Based Filtering using Low Level TensorFlow Operations** | Demonstrates creating and computing a user feature matrix, determining user positions in the feature embedding space, and generating movie recommendations based on similarity measures between user and movie feature vectors. | `TensorFlow`, `Vertex AI Workbench`, `Content-Based Filtering`| [Notebook Link](recommendation-systems/content_based_filtering_tensorflow_operations.ipynb) |
| **Prompt Design - Best Practices** | Covers best practices for prompt engineering to enhance response quality. Includes techniques such as being concise, specific, asking one task at a time, converting generative tasks into classification tasks, and improving response quality by including examples. | `Prompt Engineering` | [Notebook Link](notebook/prompt_design_best_practices.ipynb) |
| **Getting Started with the Vertex AI PaLM API & Python SDK** | Overview of using the Vertex AI PaLM API with the Python SDK. Includes testing with the [Generative AI Studio](https://cloud.google.com/generative-ai-studio), executing cURL commands in Cloud Shell, and using the Python SDK in a Jupyter notebook. Covers installing the Python SDK, using the Vertex AI PaLM API for text generation with `text-bison@001`, chat with `chat-bison@001`, and embeddings with `textembedding-gecko@001`. | `Vertex AI`, `PaLM API`, `Python SDK`, `Generative AI Studio` | [Notebook Link](notebook/intro_palm_api.ipynb) |
| **Getting Started with Text Embeddings + Vertex AI Vector Search** | Introduction to embeddings and their role in solving business challenges. Covers understanding text with Vertex AI Text Embeddings, using Vertex AI Vector Search for fast embedding retrieval, and grounding LLM outputs with Vector Search. | `Vertex AI Workbench`, `Vector Search`, `LLMs`,`BigQuery`,`Cloud Storage` | [Notebook Link](notebook/intro-textemb-vectorsearch.ipynb) |
| **Text Embeddings for a Vector Store using LangChain** | Demonstrates storing documents in a vector store database using LangChain. Covers the use of various LangChain classes to split, chunk, and embed documents, and querying the vector store with Retrievers. | `LangChain`, `Vector Store`, `Retrievers`,`Chroma` | [Notebook Link](langchain-vertex-ai/create_text_embeddings_using_langchain.ipynb) |
| **Text Generation with RAG, LangChain, and Vertex AI** | Demonstrating content generation using the Gemini Python SDK. Covers preparing a private knowledge base using DocArray for indexing document embeddings, generating embeddings with Gemini's `embedding-001` model, creating a query-based retrieval system, and implementing Retrieval-Augmented Generation (RAG) with the `gemini-pro` model to enhance generated results. | `Gemini`, `RAG`, `LangChain`, `Vertex AI`, `DocArray` | [Notebook Link](langchain-vertex-ai/gemini_langchain_rag.ipynb) |
| **Knowledge Based System with Vertex AI Vector Search, LangChain, and Gemini** | Demonstrates generating embeddings for a dataset, adding them to Cloud Storage, and creating an index in Vertex AI Vector Search. Leverages similarity metrics to evaluate and retrieve relevant knowledge base results, and utilizes LangChain to query Vertex AI Vector Search to provide context for prompts submitted to Gemini. | `Vertex AI`, `Vector Search`, `LangChain`, `Gemini`, `Cloud Storage` | [Notebook Link](langchain-vertex-ai/gemini_langchain_vector_search_rag.ipynb) |

## Credits 🙌

## Contributing 🤝

Contributions are welcome! If you have any ideas or improvements, feel free to submit a pull request.

## License 📄

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.