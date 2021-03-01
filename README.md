# Instacart-Market-Basket-Analysis
<h1>Business/Real-world Problem</h1>
Instacart, a grocery ordering and delivery app, aims to make it easy to fill your refrigerator and pantry with your personal favorites and staples when you need them. After selecting products through the Instacart app, personal shoppers review your order and do the in-store shopping and delivery for you.  Instacart’s data science team plays a big part in providing this delightful shopping experience. Currently they use transactional data to develop models that predict which products a user will buy again, try for the first time, or add to their cart next during a session.We need to use this anonymized data on customer orders over time to predict which previously purchased products will be in a user’s next order.

<h2> Real-world/Business objectives and constraints.</h2>
Objectives:
<ul>
 <li>We need to predict which previously purchased product will be in user's next order</li>
<li> Minimize mean F1 score.</li></ul>
<pre>Constraints:
1. Some form of interpretability
2. No strict latency constraints.</pre>
<h1>Data Overview</h1>
The dataset for this competition is a relational set of files describing customers' orders over time. The goal is to predict which products will be in a user's next order. The dataset is anonymized and contains a sample of over 3 million grocery orders from more than 200,000 Instacart users. For each user, we provide between 4 and 100 of their orders, with the sequence of products purchased in each order. We also provide the week and hour of day the order was placed, and a relative measure of time between orders. For more information, see the blog post accompanying its public release.
<h3>Performance metric</h3>
<ul>
<li> Mean F1 score : <b>Source: </b>https://www.kaggle.com/c/instacart-market-basket-analysis/overview</li>
<li> Confusion matrix : https://en.wikipedia.org/wiki/Confusion_matrix</li>  </ul>
  
## <span style="background-color: #FFFF00"> For more Detailed explanation you can visit to my medium blog.</span>
