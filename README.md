# AI/Machine Learning Intern Challenge: Simple Content-Based Recommendation

**Deadline**: Sunday, Feb 23th 11:59 pm PST

---

## Overview

The current program is a **content-based movie recommendation system** that, given a **short text description** in **English** of a user’s preferences, suggests top 5 **similar items** from a small dataset which has 100 movies. The system uses **TF-IDF vectorization** and **cosine similarity** to compare the user's query with movie overviews and return the most relevant recommendations.

---

1. **About Dataset**  
The dataset used in this project is **Top 100 Movies Dataset** from [IMDB](https://www.imdb.com/list/ls053251213/). The dataset contains information about movies including their genres, which will be used for similarity comparison.

2. **Approach**  
- ***Load the dataset*** - Read the movie data from a CSV file.
- ***Preprocess the text*** - Clean movie descriptions by converting text to lowercase, removing special characters, tokenize words, and remove stopwords.
- ***Convert text into numerical vectors*** - Use TF-IDF to transform text descriptions into numerical format.
- ***Compute similarity and Return top 5 recommendations*** - Calculate cosine similarity between the user query and all movie descriptions, and retrieve the most relevant movie titles.

3. **Code Organization**  
   - You may use a **Jupyter Notebook** or **Python scripts**.  
   - Keep it **readable** and **modular** (e.g., one section for loading data, one for building vectors, one for computing similarity, etc.).  
   - Briefly comment or docstring your key functions/sections.

4. **Output**  
   - When given an input description (e.g., `"I like action movies set in space"`), your system should print or return a list of recommended items (e.g., 3–5 titles).  
   - Include the similarity score or rank if you’d like.

5. **Summary & Instructions**  
   - A short `README.md` that includes:
     - **Dataset**: Where it’s from, any steps to load it.  
     - **Setup**: Python version, virtual environment instructions, and how to install dependencies (`pip install -r requirements.txt`).  
     - **Running**: How to run your code (e.g., `python recommend.py "Some user description"` or open your notebook in Jupyter).  
     - **Results**: A brief example of your system’s output for a sample query.

---

## Deliverables

1. **Fork the Public Repository**  
   - **Fork** this repo into your own GitHub account.

2. **Implement Your Solution**  
   - Load and preprocess your dataset (e.g., read CSV, handle text columns).  
   - Convert text data to vectors (e.g., TF-IDF).  
   - Implement a function to compute similarity between the user’s query and each item’s description.  
   - Return the top matches.
   - Salary expectation per month (Mandatory)

3. **Short Video Demo**  
   - In a `.md` file (e.g., `demo.md`) within your fork, paste a link to a **brief screen recording** (video link).  
   - Demonstrate:
     - How you run the recommendation code.  
     - A sample query and the results.

4. **Deadline**  
   - Submit your fork by **Sunday, Feb 23th 11:59 pm PST**.

> **Note**: This should be doable within ~3 hours. Keep it **straightforward**—you do **not** need advanced neural networks or complex pipelines. A simple TF-IDF + cosine similarity approach is sufficient.

---

## Evaluation Criteria

1. **Functionality**  
   - Does your code run without errors?  
   - When given an input query, does it successfully output relevant items?

2. **Code Quality**  
   - Clear, commented code (where it counts).  
   - Logical steps (load data → transform → recommend).

3. **Clarity**  
   - Is your `README.md` straightforward about setup, how to run, and what to expect?

4. **ML/Recommendation Understanding**  
   - Basic implementation of a content-based recommendation approach (vectorization, similarity measure).

**We look forward to seeing your solution!** Good luck!
