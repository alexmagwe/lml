## LML 

a field of study that gives the computers an ability to learn without being programmed explicitly.
a computer program that gets better at a task through more experience.

### Machine learning main categories

- Supervised Learning
- Unsupervised Learning

#### Supervised Learning

the algorithm is fed some dataand its outputs and trains itself based on that to produce the best input output relationship.

supervised learning is categorized into classification and regression problems
#### Classification
Here the system is trying to predict results in a descrete output,in otherwords its trying to map variables into discrete categories.
#### Regression
here we are trying to predict results in a continous output.in other wordsmapping input variables to some continous function

### Unsupervised learning

the algorithm is fed large amounts of data and it tries to find patterns in the data


## Linear regression

use to map an input to a continous output,e.g, predicting housing prices
x->h(x)->y
h(x) is the function that maps x to y it is called a hypothesis,
h(x)=Ax+c
where a is a scalar and c is a constant

#### Cost function

it is a function that helps us to choose c and A so that h(x) is as close to y as possible
we choose c and A that minimizes the cost function
the cost function for linear regression is called 'SQUARED ERROR COST FUNCTION'
it is found by summing over the squares of the difference between h(x)<sub>i</sub> and y<sub>i</sub>

