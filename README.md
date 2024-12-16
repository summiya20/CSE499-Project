# CSE499-Project
# Riddle Me: Evaluating Problem-Solving Abilities of Advanced LLMs

The **Riddle Me** project aims to evaluate and compare the problem-solving abilities of five advanced large language models (LLMs)—**Gemini**, **Cohere**, **Llama 2.7**, **Llama 3**, and **Llama 3.2 Instruct**—by testing them on various puzzles. The objective is to assess their performance both **with** and **without prompts**, comparing their capacity to solve diverese sets of puzzle, with a focus on:

- **Accuracy**
- **Completion Time**
- **Response Time**
- **Error Rates**

### Key Objectives

- Evaluate the problem-solving capabilities of the LLMs on a variety of puzzles.
- Compare the models' performance with and without prompting.
- Focus on different set of puzzle.
- Assess **accuracy**, **Response Time**, **Completion Time** and **error rates** in solving the puzzles.
- Contribute to understanding the models' strengths and weaknesses in handling reasoning tasks.
- Provide a distinct **taxonomy** for classifying puzzles and a **systematic assessment framework** to better understand LLMs' human-like reasoning capabilities.

### Project Structure

The repository contains directories and scripts for evaluating the puzzle-solving capabilities of various LLMs:

- **`gemini/`**: Contains scripts and configurations for testing the Gemini model's performance.
  - `gemini_prompting.py`: Script for solving puzzles with prompting.
  - `gemini_no_prompting.py`: Script for solving puzzles without prompting.

- **`cohere/`**: Contains scripts and configurations for the Cohere model.
  - `cohere_prompting.py`: Script for solving puzzles with prompting.
  - `cohere_no_prompting.py`: Script for solving puzzles without prompting.

- **`llama/`**: Contains scripts for Llama models.
  - `llama_2.7.py`: Script for the Llama 2.7B model.
  - `llama_3.py`: Script for the Llama 3B model.
  - `llama_3.2_instruct.py`: Script for the Llama 3.2B-Instruct model.
### Requirements

Ensure the necessary dependencies for each model are installed as mentioned in their respective directories.

---

## Model-Specific Requirements

Each model has its own specific requirements for running the scripts. Please make sure to install the necessary dependencies based on the model you wish to evaluate.

### 1. **Cohere Model**

- **Libraries/Requirements**:
  - `cohere`
  - `matplotlib`
  - `time`
  - `re`
  - You also need an API key for the **Cohere** model, which should be configured as `API_KEY`.


### 2. **Gemini Model**

- **Libraries/Requirements**:
  - `python-dotenv` 
  - `streamlit` 
  - `google-generativeai` 
  - You also need an API key for the **Gemini** model, which should be configured as an environment variable `GOOGLE_API_KEY`.
 
  ### 3. **Llama2.7, 3 and 3.2 Model**

- **Libraries/Requirements**:
  - `transformers` 
  - `torch` 
  - `bitsandbytes (for optimizing large models).`
  - `accelerate (for better performance with large models)`
  -You also need an API key for the **Gemini** model, which should be configured as an environment variable `HF_TOKEN`.

You can install the required libraries using the `requirements.txt` file.
