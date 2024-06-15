
# ResWork

Our Resume Prediction ML project leverages machine learning algorithms to analyze and predict the suitability of resumes for specific job positions. By employing natural language processing techniques, it parses resumes to extract relevant information such as skills, experience, and education. The model then compares these details against job descriptions to determine the role to which the candidate is most compatible. Through continuous learning and optimization, our system provides accurate and efficient resume screening, saving time and resources for candidates ensuring a better match between candidates and job openings.


## Scope

1. By providing recommendations, predictions and overall score user can improve their resume and can keep on testing it on our tool

2. It can be used by colleges to get insight of students and their resume before placements

3. Also, to get analytics for roles which users are mostly looking for



## Pre-requisites

1. [Python](https://www.python.org/downloads/)
2. [Google Colab](https://colab.research.google.com)
3. [Jupyter Notebook](https://jupyter.org/install)

***You can choose between colab or Jupyter**
## Dependencies

+ [Pandas](https://pandas.pydata.org/docs/) :- Python pandas is a powerful data analysis library, offering data structures and tools for handling structured data efficiently and effectively.  
+ [Numpy](https://numpy.org/doc/1.26/) :- NumPy is a powerful library for numerical computing in Python, providing multidimensional arrays, mathematical functions, and linear algebra operations.
+ [Seaborn](https://seaborn.pydata.org/) :- Seaborn is a Python data visualization library based on Matplotlib, offering high-level interface for attractive statistical graphics.
+ [Matplotlib](https://matplotlib.org/stable/index.html) :- Matplotlib is a comprehensive plotting library for Python, offering a wide range of visualization tools for creating diverse plots. 
+ [sklearn](https://scikit-learn.org/stable/) :- Scikit-learn (sklearn) is a machine learning library in Python. It includes algorithms like **KNeighborsClassifier**, **OneVsRestClassifier**, and utilities like **classification_report** for **evaluating model performance**, making it a versatile tool for classification tasks in various domains and industries.
+ [Pickle](https://docs.python.org/3/library/pickle.html) :- Python's pickle module allows for object serialization, converting objects into byte streams for storage or transmission. Pickle can serialize and deserialize complex Python objects, including custom classes, preserving their structure. It's widely used for data persistence, caching, and inter-process communication. However, caution is advised when unpickling data from untrusted sources due to potential security risks from executing arbitrary code embedded in pickled objects.
+ [Tika](https://www.geeksforgeeks.org/parsing-pdfs-in-python-with-tika/) :- Apache Tika is a library that is used for document type detection and content extraction from various file formats. Using this, one can develop a universal type detector and content extractor to extract both structured text and metadata from different types of documents such as spreadsheets, text documents, images, PDF’s, and even multimedia input formats to a certain extent. Tika-Python is Python binding to the Apache TikaTM REST services allowing tika to be called natively in python language.





## Execution

![](https://github.com/kumar20vinay/Resume_Prediction/blob/main/images/flowchart.png)
 
For Executing this whole project yoou must have the pre-requisites stated above-

+ **Load the Dataset** for the purpose of training of model
+ **Clean the dataset** using NLP.
+ Label the data using **Tf-Idf Vectorizer.**
+ Splitting the data for **Training the Model.**
+ Evaluates the model performance by the use of metrics like **confusion Matrix and Accuracy.**
+ Parse the Resume through for **data Extraction.**
+ Clean the parsed data
+ Now finally pass the extracted data to the model for **Category Prediction.**
### How to run locally
+ clone the repo
```
git clone https://github.com/kumar20vinay/Resume_Prediction.git

```
+ open Google Colab or Jupyter Notebook
+ run the **.ipynb** file


