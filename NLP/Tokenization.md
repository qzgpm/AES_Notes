- Tokenization is a fundamental step in Natural Language Processing ([[NLP]]).
- It involves dividing a Textual input into smaller units known as tokens.

### **Types of tokens:

#### 1. **Word Tokenization:
-  **Text** is divided into individual **Words**
-  Via **word_tokenize** in **nltk** package in **python**
#### 2. **Character Tokenization:
- **Text** is split and converted to a **sequence of individual characters**.
- This is beneficial for tasks that require a detailed analysis, such as **spelling correction** or for tasks with unclear boundaries.
- It can also be useful for modelling character-level language.
#### 3. **Sub-word Tokenization:
- This strikes a balance between **word** and **character** tokenization by breaking down text into units that are **larger than a single character but smaller than a full word**.
- This is useful when dealing with morphologically rich languages or rare words.
#### 4. **Sentence Tokenization:
- Sentence tokenization converts a paragraphs or large set of sentences into separated sentences as tokens.
- This is useful for tasks requiring individual sentence analysis or processing.
- Via **sent_tokenize** in **nltk** package in **python**
#### 5. **N-gram Tokenization:
- N-gram tokenization splits words into **fixed-sized chunks** (size = n) of data.