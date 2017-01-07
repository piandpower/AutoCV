# AutoCV
formats a given CV with general info/work experience/skills to specifications of Top Notch Finders, Inc. - A recruiting firm. 

Uses Python with Flask to scrape Microsoft Word and PDF files for keywords on work experience, skills. Inputs information into a template Top Notch Finders Inc. resume. 

In the future, if possible, I wish to build a neural network or other machine learning algorithm to detect spelling, grammar, and translation errors to minimze the final editing work
#idea:
Use TextBlob spelling correction to iterate over all sentences
Ex: 
print(TextBlob('henlo').correct())
>>>hello
#idea2:
Use py-translate to translate from spanish to english
