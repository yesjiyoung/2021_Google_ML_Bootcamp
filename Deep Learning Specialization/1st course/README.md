# 1st course: Neural Networks and Deep Learning


## 1주차 Indtroduction to Deep Learning 
1️⃣ **What is a Neural Network?**
- Q : True or false? As explained in this lecture, every input layer feature is interconnected with every hidden layer feature. 
- A : - [x]True - [ ] False

2️⃣ **Supervised Learning with Neural Networks**
- Q : Would structured or unstructured data have features such as pixel values or individual words?
- A : - [ ] structured data - [ ] unstructured data

3️⃣ **Why is Deep Learning taking off?**
- Q : What will the variable m denote in this course? 
- A : "Number of training examples"

## 2주차 Neural Networks Basics
### Logistic Regression as a Neural Network
1️⃣ **Logistic Regression**
- Q : What are the parameters of logistic regression? 
- A : W, an n_x dimensional vector, and b, a real number.

2️⃣ **Logistic Regression Cost Function**
- Q : What is the difference between the cost function and the loss function for logistic regression? 
- A : The loss function computes the error for a single training example; the cost function is the average of the loss functions of the entire training set.

3️⃣ **Gradient Descent**
- Q : True or false. A convex function always has multiple local optima.
- A : false

4️⃣ **Derivatives**
- Q : On a straight line, the function's derivative... 
- A : doesn't change 
- 
5️⃣ **Derivatives with a Computation Graph**
- Q : In this class, what does the coding convention dvar represent?
- A : The derivative of a final output variable with respect to various intermediate quantities.

6️⃣ **Logistic Regression Gradient Descent**
- Q : In this video, what is the simplified formula for the derivative of the losswith respect to z?
- A : a - y 

7️⃣ **Gradient Descent on m Examples**
- Q : In the for loop depicted in the video, why is there only one dw variable (i.e. no i superscripts in the for loop)?
- A : The value of dw in the code is cumulative.

### Python and Vectorization 
✔️ **Vectorization**
- Q : True or false. Vectorization cannot be done without a GPU.
- A : false

