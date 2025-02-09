# Log Classification System

This project is a **Hybrid Log Classification System** that classifies log messages based on their source and content. It uses a combination of machine learning models, pattern matching and combining three complementary approaches to handle varying levels of complexity in log patterns for effective classification processing predictable, complex, and poorly-labeled data patterns.

---
## Classification Approaches

1. **Regular Expression (Regex)**:
   - Handles the most simplified and predictable patterns.
   - Useful for patterns that are easily captured using predefined rules.

2. **Sentence Transformer + Logistic Regression**:
   - Manages complex patterns when there is sufficient training data.
   - Utilizes embeddings generated by Sentence Transformers and applies Logistic Regression as the classification layer.

3. **LLM (Large Language Models)**:
   - Used for handling complex patterns when sufficient labeled training data is not available.
   - Provides a fallback or complementary approach to the other methods.

![architecture](resources/arch.png)

---
## Setup Instructions

1. **Install Dependencies**:
   Make sure you have Python installed on your system. Install the required Python libraries by running the following command:

   ```bash
   pip install -r requirements.txt
   ```
