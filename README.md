# LangChain Models Suite

A unified LangChain experimentation workspace integrating models across major providers: **OpenAI**, **Anthropic**, **Google Gemini**, and **Hugging Face**.

## Supported Integrations

- **LangChain Core**: `langchain`, `langchain-core`
- **OpenAI**: `langchain-openai`, `openai`
- **Anthropic**: `langchain-anthropic`
- **Google Gemini**: `langchain-google-genai`, `google-generativeai`
- **Hugging Face**: `langchain-huggingface`, `transformers`, `huggingface-hub`

## Getting Started

### 1. Set Up Environment

Create and activate a virtual environment:

```bash
python -m venv venv
# Windows:
venv\Scripts\activate
# macOS/Linux:
source venv/bin/activate
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Configure API Keys

Create a `.env` file in the project root:

```env
OPENAI_API_KEY=your_openai_key
ANTHROPIC_API_KEY=your_anthropic_key
GOOGLE_API_KEY=your_google_key
HUGGINGFACEHUB_API_TOKEN=your_hf_token
```

### 4. Verify Installation

```bash
python test.py
```
