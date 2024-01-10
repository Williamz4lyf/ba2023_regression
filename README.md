# BA2023-Regression
[BA2023 class competition](https://www.kaggle.com/competitions/ba2023-regression/overview).

### Description
Within the context of Eleme delivery service, at every moment the command platform of “Smart Logistics” sends orders from customers to delivery-men for instant delivery. The decisions being made by the delivery-men are mainly two-fold: (i) pick-up from a store, and delivery to a customer. At any specific moment, a delivery-man may receive new orders assigned to him, while he has some unfinished orders which were previously assigned. In this situation, he needs to decide what to do next (to pick up a new order or to deliver an old one), based on his order status and geographical location.

There are two main tasks for this project. The first task is a classification problem, in which you are asked to build a model to predict whether the delivery-man’s next move is to pick up an order or to deliver an order. The second task is a regression problem, in which you are asked to build a model to predict the expected time of the delivery-man's next action. For both tasks, you will use his historical decisions and current status as features.

The evaluation metric for this competition is MAE-Score.
