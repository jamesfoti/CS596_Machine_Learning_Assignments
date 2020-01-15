# CS596_Machine_Learning_Assignments

## DISCLAIMER!
The work that appears in this repo was mostly put together by Professor Yang Xu. He simply allowed us to "fill in the blanks" found in sections of the jupyter notebook files that follow this format:

```python
#### START YOUR CODE ####
# Create a list of 50 even integer numbers, ranging from 2 to 100, e.g., [2, 4, 6, ..., 100]
# Hint: use the range() function
evens = [jj for jj in range(2, 101, 2)]

# Find all the numbers that can be divided by number 6 with 0 remainder, and store them in a list
# E.g., [6, 12, ..., 96]
# Hint: use list comprehensions to write just one line of code
divisibles = [jj for jj in evens if jj % 3 == 0]
#### END YOUR CODE ####


#### DO NOT CHANGE THE CODE BELOW ####
assert isinstance(evens, list)
print('len(evens) = {}'.format(len(evens)))
print('evens[20:30] = {}'.format(evens[20:30]))

assert(isinstance(divisibles, list))
print('len(divisibles) = {}'.format(len(divisibles)))
print('divibles = {}'.format(divisibles))
```

I uploaded these assignments simply just to show what kind of machine learning topics I was exposed to. You can learn more about Professor Xu here: https://clcs.sdsu.edu/

## Class Overview (taken from syllabus)
This course covers a set of basic concepts of machine learning (ML) algorithms and theories, and
introduce best practices for implementing robust ML models for common supervised (e.g.,
classification, regression etc.) and unsupervised (e.g., clustering, dimension reduction etc.) tasks.
Training, tuning, and evaluation techniques for tuning various types of deep neural network
models (including convolutional neural network, recurrent neural network) will be emphasized.
Fundamental algorithms covered in class and assessed in assignments will mostly be
implemented in Python programming language. Some knowledge in modern ML programming
frameworks (e.g., TensorFlow, PyTorch etc.) will be gently covered.

#### The learning goals of this course include:
* i) Understand the basic ML concepts and terms;<br />
* ii) Being able to implement common machine learning models, and properly train and evaluate the models.<br />
* iii) Being able to choose the most suitable algorithm and model architecture for given tasks. Know how implement, debug, and tune            complex models using modern ML programming frameworks. 
