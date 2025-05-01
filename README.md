# 🖥️ Code-Editor-and-Generator API 🚀

Welcome to the **Code-Editor-and-Generator** API! This FastAPI project integrates state-of-the-art transformer models from Hugging Face to **generate**, **debug**, **optimize**, and **write unit tests** for code. Powered by models like `Salesforce/codegen-350M-mono`, this API is designed to assist developers by automating tasks that would traditionally require deep knowledge of the programming language.

## 🌟 Features

1. **Generate Code**: 📝 Generate code based on a natural language prompt.
2. **Debug Code**: 🐞 Automatically detect issues and suggest fixes for buggy code.
3. **Optimize Code**: ⚡ Suggest performance improvements or refactorings for the provided code.
4. **Write Unit Tests**: 🧪 Automatically generate unit tests for a given code snippet.

## ⚙️ Getting Started

### 📦 Prerequisites

To get started with this project, you need:

- Python 3.7+ installed on your machine.
- `pip` to install required dependencies.

### 🛠 Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/coderyash-ai/Code-Editor-and-Generator.git
    cd Code-Editor-and-Generator
    ```

2. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

### 🚀 Run the API Server

You can run the FastAPI server using **Uvicorn**:

```bash
uvicorn main:app --reload
