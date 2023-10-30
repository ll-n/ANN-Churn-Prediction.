# ANN-Churn-Prediction.

<img width="460" alt="Screenshot 2023-10-30 at 10 15 36 PM" src="https://github.com/ll-n/ANN-Churn-Prediction./assets/127438773/5f5cc1a0-43e5-449e-8b4c-0f9c806644c8">

Customer churn refers to the phenomenon where customers discontinue their relationship with a business or company.  

I use an Artificial Neural Network (ANN) to predict customer churn
The ANN has three layers: the first two layers help the model understand patterns in customer data, and the last layer predicts whether a customer will churn or not.

To make accurate predictions, the model is trained using historical data on customer behavior. It learns to recognize patterns that indicate potential churn, such as changes in customer activity or purchase patterns.

To improve the model's performance, the training process is optimized using class weights. This ensures that the model pays more attention to the minority class (churned customers) and avoids biases towards the majority class.

The model is trained using the provided training data and evaluated using a separate validation dataset. Training continues until the model stops improving or reaches a maximum of 1000 training cycles. If the model doesn't show improvement for 20 consecutive cycles, training is stopped early to save time.

By using an ANN for customer churn prediction, businesses can proactively identify customers at risk of churn and take appropriate actions to retain them.

