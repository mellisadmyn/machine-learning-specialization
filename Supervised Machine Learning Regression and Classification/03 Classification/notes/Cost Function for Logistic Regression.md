## Cost function for logistic regression

- The cost function gives you a way to measure how well a specific set of parameters fit the the training data
- It gives a way to choose better parameters
- Squared error cost function is not ideal for logistic regression
- Give training set, how can we choose parameters _w_ and _b_?

![alt text](./images/10.png)

- For linear regression, we used the _squared cost function_
- With logistic regression, there are lots of local minimums if we use the squared error cost function

![alt text](./images/11.png)

- _Loss function_ measures how well you are doing on one training example
- By summing up the _loss_ on all of the training examples

<br>

- Below is an example of what happens to Loss as f(x) -> 1 and f(x) -> 0 when y^(i) = 1
  - As f(x) -> 1, loss approaches 0
  - The tumor is malignant, so as our prediction gets closer to 1, loss gets closer to 0 (0 means no loss)
  - If the tumor is malignant, as our prediction gets closer to 0, loss gets closer to 1 (1 meaning completely wrong)

![alt text](./images/12.png)

- Next is an example when y^(i) = 0

![alt text](./images/13.png)

- Cost function for logistic regression formula

![alt text](./images/14.png)

### Simplified Cost Function for Logistic Regression

- There is a simplified loss function and cost function that exists for binary classification problems where `y` can only be 0 or 1, cannot take on any value other than 0 or 1
- This is the simplified loss function and cost function, a the logic to get to that

1. Simplified loss function

![alt text](./images/15.png)

2. Simplified cost function using the simplified loss function

![alt text](./images/16.png)
