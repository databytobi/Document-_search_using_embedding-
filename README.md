# Document Search Using Embeddings

This project demonstrates how to leverage the **Gemini API** to create embeddings for performing document search. Using the Python client library, the project builds word embeddings to compare search strings or questions to document contents. By applying embeddings, it enables efficient and accurate document search over a set of documents, particularly for queries related to prompting techniques.

---

## Overview

The project showcases:
- Building word embeddings using **Gemini API**.
- Comparing search strings or questions to document contents using embeddings.
- Performing document search to extract relevant information from a set of documents.
- Addressing questions related to **prompting techniques**.

---

## Libraries and Tools Used

The following libraries were utilized in this project:
- **Core Libraries**:
  - `textwrap`: For text formatting and wrapping.
  - `numpy` (`np`): For numerical computations and array processing.
  - `pandas` (`pd`): For data manipulation and analysis.
- **Google Generative AI**:
  - `google.generativeai` (`genai`): For interacting with the Gemini API.
- **Google Colab**:
  - `google.colab.userdata`: For handling user data.
- **IPython Display**:
  - `IPython.display.Markdown`: For rendering Markdown output.

---

## Features

- **Embedding Creation**: Build word embeddings using the Gemini API for document comparison.
- **Document Search**: Efficiently search and extract relevant information from documents.
- **Question Answering**: Answer questions related to **prompting techniques** based on document contents.
- **Scalable Analysis**: Handle multiple documents with flexibility and accuracy.

---

## Installation

### Prerequisites

Before running the project, ensure you have:
1. Access to the **Gemini API**.
2. Necessary API keys or permissions to interact with the Gemini service.

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/databytobi/document-search-using-embeddings.git
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Configure your Gemini API key in the environment variables:
   ```bash
   export GEMINI_API_KEY="your_api_key_here"
   ```

---

## Usage

1. Run the main script to perform document search:
   ```bash
   python main.py --documents_path path/to/documents --query "Your search question here"
   ```
2. For example, to ask a question about prompting techniques:
   ```bash
   python main.py --documents_path ./data/documents/ --query "Explain prompting techniques in detail"
   ```

---

## Project Structure

```
document-search-using-embeddings/
│
├── data/                  # Sample documents for testing
├── notebooks/             # Jupyter notebooks for exploration and visualization
├── src/                   # Source code
│   ├── embedding_utils.py # Utilities for creating and processing embeddings
│   ├── search_engine.py   # Logic for document search
│   ├── query_handler.py   # Handles user queries
│   ├── visualization.py   # Code for visualizing search results
│   └── api_client.py      # Wrapper for interacting with the Gemini API
├── tests/                 # Unit tests
├── main.py                # Main script to run the project
├── README.md              # Project documentation
└── requirements.txt       # Python dependencies
```

---

## Example

Search for specific information in a set of documents:
```bash
python main.py --documents_path ./data/documents/ --query "What are prompting techniques?"
```

---

## Contributing

Contributions are welcome! If you have ideas for new features or improvements, feel free to submit a pull request or open an issue.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Acknowledgements

- **Gemini API** for enabling embedding creation and document search.
- **NumPy** and **Pandas** for data processing.
- **Google Generative AI** for providing tools to enhance the search experience.
- **IPython Display** for Markdown rendering.
