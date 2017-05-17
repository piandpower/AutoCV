# AutoCV
https://automatetheboringstuff.com/chapter13/
formats a given CV with general info/work experience/skills to specifications of a recruiting firm. 

Uses Python with Flask to scrape Microsoft Word and PDF files for keywords on work experience, skills. Inputs information into a template resume. 

In the future, if possible, I wish to build a neural network or other machine learning algorithm to detect spelling, grammar, and translation errors to minimze the final editing work
#idea:
Use TextBlob spelling correction to iterate over all sentences
Ex: 
print(TextBlob('henlo').correct())
>>>hello
#idea2:
Use Google Cloud Translate to go from Spanish -> English?
Use Tensorflow
