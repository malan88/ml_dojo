# General Notes

- In supervised learning, a machine learning algorithm builds a model by
  examining many examples and attempting to find a model that minimizes loss;
  this process is called **empirical risk minimization**.

# Reducing Loss

- Derivative of (y-y')² with respect to the weights and biases tells us how loss
  changes for a given example.
- Repeatedly take small steps in the direction that minimizes loss
    - These are called (negative) Gradient Steps
    - This strategy is called Gradient Descent

If your batch is large, testing a lot of steps is extremely expensive, you could
test with one example at a time, or do batches of 10-1000 and average over time.
One example at a time is called **Stocahastic Gradient Descent** and small
batches is **Mini-Batch Gradient Descent**.
