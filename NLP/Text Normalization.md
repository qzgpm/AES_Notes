- It is necessary to clean up the text before logical processes for accurate results.
### **They are:
#### 1. Case Conversion:
- Convert to lower case
- Improves consistency in text data
- Helps standardize similar words like “Python” and “python”
- Via **lower()** in python
- *eg*:
```python
text.lower()
```
#### 2. Cleaning up Non-alphabets:
- Removes unnecessary numerical values from text
- Removes punctuation symbols from text
- Helps simplify text preprocessing
- Commonly performed using regular expressions (Regex)
- Via **sub()** in **re** package in **python**
- *eg:*

```python
re.sub(r'[^a-z\s]', '', text)
```
#### 3. Cleaning Extra Spaces:
- Removes leading and trailing spaces
- Helps clean and standardize text
- Improves text preprocessing consistency
- Via **sub()** in **re** package in **python**
- *eg*:
```python
re.sub(r'\s+', ' ', text).strip()
```
#### 4. Removing Stop Words:
- Removes commonly used unnecessary words
- Helps focus on meaningful words in text
- Improves efficiency of NLP tasks
