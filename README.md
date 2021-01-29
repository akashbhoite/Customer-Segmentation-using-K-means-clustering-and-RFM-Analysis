# Customer-Segmentation-using-K-means-clustering-and-RFM-Analysis

Customers who use a company's platform/service have different needs depending on their own different characteristics/Personas. Your business should taylor it's products/services depending on the customer's needs. You can do many different segmentations according to what you are trying to achieve. For example if you want to increase retention rate, you can do a segmentation based on churn probability and take suitable actions. However, there are some common and useful segmentation methods as well. One of them which I have implemented in this case is  RFM.

### RFM stands for Recency - Frequency - Monetary Value. 

Theoretically we will have segments like below:

##### Low Value: Customers who are less active than others, not very frequent buyer/visitor and generates very low - zero - maybe negative revenue.
##### Mid Value: In the middle of everything. Often using our platform (but not as much as our High Values), fairly frequent and generates moderate revenue.
##### High Value: The group we don’t want to lose. High Revenue, Frequency and low Inactivity.

As the methodology, we need to calculate Recency, Frequency and Monetary Value (we will call it Revenue from now on) and apply unsupervised machine learning to identify different groups (clusters) for each. The Jupyter notebook will provide you with the entire python code for RFM Clustering.
