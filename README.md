# Food Recommendation Powered by Multimodal RAG

A multimodal food recommendation system using **LangChain**, **GPT-4 Vision**, and **retrieval-augmented generation (RAG)**. This application combines image data (in base64) and textual descriptions to provide personalized dish suggestions based on user queries, making it a powerful tool for restaurant personalization or marketing.

---

## Features

* ✅ **Multimodal RAG Integration**: Combines image and text data for more engaging recommendations.
* ✅ **Personalized Food Suggestions**: Answers user-specific questions like "spicy dishes" or "kid-friendly meals".
* ✅ **Image-Enhanced Responses**: Dishes are shown with images and descriptions to improve visual appeal.
* ✅ **LangChain Runnable Chains**: Modular and extensible pipeline using LangChain chaining.
* ✅ **OpenAI GPT-4 Vision Support**: Leverages multimodal LLM to understand both image and textual context.

---

## Example Queries

* `Are there any sweet dishes that include nuts?`
* `Recommend a dish that's perfect for a light lunch.`
* `Some of the spiciest dishes.`
* `Are there any dishes that are kid-friendly or less spicy?`

---

## Tech Stack

| Component             | Description                                        |
| --------------------- | -------------------------------------------------- |
| Python                | Core programming language                          |
| LangChain             | Framework for building LLM pipelines               |
| OpenAI GPT-4 (Vision) | Multimodal model for understanding images and text |
| Google Colab          | Execution environment                              |
| Base64                | Used for embedding images in responses             |
| IPython Display       | For rendering HTML and images in notebooks         |

---

## Setup Instructions

1. **Clone the repo**:

   ```bash
   git clone https://github.com/mutiaracitrasari/food-recommendation-multimodal.git 
   cd food-recommendation-multimodal
   ```

2. **Install dependencies**:

   ```bash
   pip install openai langchain
   ```

3. **Set your OpenAI API Key**:

   Replace in the code or set environment variable:

   ```python
   os.environ["OPENAI_API_KEY"] = "your_openai_api_key"
   ```

4. **Run the notebook**:

   Use Google Colab or Jupyter Notebook to execute the code.

---

## How It Works

1. **Query Parsing**
   User provides a natural language query (e.g., "sweet dishes with nuts").

2. **Retrieval via LangChain Retriever**
   Retrieves relevant dish descriptions and images stored in a vectorstore.

3. **Multimodal Prompt Construction**
   Combines retrieved base64 images and text into a GPT-4-Vision compatible message format.

4. **Generation**
   GPT-4 Vision model processes the prompt and returns a contextual and personalized response.

5. **Display**
   Results are rendered using HTML and IPython for interactive exploration.

---

## 🚀 Use Cases

* 🍴 Restaurant recommendation engines
* 🧑‍🍳 Personalized digital menus
* 📈 Food marketing campaigns
* 🍕 Dietary or cultural food filtering

---


