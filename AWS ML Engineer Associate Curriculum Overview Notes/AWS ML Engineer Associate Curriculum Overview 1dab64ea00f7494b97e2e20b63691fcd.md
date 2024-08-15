# AWS ML Engineer Associate Curriculum Overview

[**AWS ML Engineer Associate Curriculum Overview**](https://explore.skillbuilder.aws/files/a/w/aws_prod1_docebosaas_com/1723647600/Y4cNhUK8ES1JG0-7jI9yog/tincan/1795780_1721675945_o_1i3dtud0ea7gp2g1ejlshml4vb_zip/index.html?enhanced_signature=ARyY6MKVug5aZrpYLoL6JOPr5up6rltcs2TlNql5QtA&endpoint=https%3A%2F%2Fexplore.skillbuilder.aws%2Flrs-api%2F&auth=Basic%20OTQ3YjEzYTktMTIyMy00MTM2LWE0MGUtOWFmM2Y5MTEwMGJhOmY4ODhjZTdkYmY5ZmQ2NTQ1N2I0MDg2MGQ3YjJhNWU5&actor=%7B%22name%22%3A%22Mark+Spencer+Jordan%22%2C%22mbox%22%3A%22mailto%3Amarkspencerjordan%40gmail.com%22%7D&registration=6a8a9c6a-ad84-47a8-81e4-7c9589cb63f7&activity_id=http%3A%2F%2FHuV9n56OKdwowqvSnNZvoJ7iSQOjsu59_rise&Accept-Language=en&course_id=20380&content_token=6a8a9c6a-ad84-47a8-81e4-7c9589cb63f7&session_context=lms&host=kfase3bzbc.execute-api.us-east-1.amazonaws.com&path=/v1/xApi/&rs=66bc9fb391d0b&crct=6a9b381e0df9b7131b36cdd06d5f47fd727abb3307f33549dfa9272721624859f6c95bb3f30d567c2ec5c55083aa12364e7947783e4fd4a0278bb7a23a16a329&course_code=TCCA-DIG-300-MLEACO-0100-EN-US&course_id=20380&username=3d0b86b3-d0b2-4c80-bdba-f54e0b0766c8&user_id=5867733&hash=c7e2e54eb50a2f016e2d8147eb3f96a6fd892f0df0e1a0c82b8474abf00c8bfc#/)

## Machine Learning Life Cycle

![image.png](AWS%20ML%20Engineer%20Associate%20Curriculum%20Overview%201dab64ea00f7494b97e2e20b63691fcd/image.png)

## Common Unsupervised Learning Business Problems

### Dimension Reduction

This technique reduces high-dimensional datasets to a more manageable size while preserving the most significant features of the original data. Dimension reduction mitigates the curse of dimensionality, where the performance of a model degrades as the number of features increases. Lower dimensionality leads to faster training times, lower costs, and potentially more accurate predictions.

For example, training may uncover that the color dimension is not significant for predicting gas mileage. The resulting model would not include the color feature.

### Density Estimation

This is a fundamental problem in ML, where the goal is to estimate the underlying probability distribution of a dataset. The estimate is used to model the distribution of the data and make predictions on new, unseen data. Density estimates can be useful for anomaly detection, data generation, and improving model performance.

For example, you can use density estimation to estimate the probability of a user liking a product based on their preferences. This can help improve the accuracy of recommendations.

Now that you have reviewed density estimates, move to the next tab to learn about cluster analysis.

### Cluster Estimation

To better understand the attributes of a specific cluster, this technique groups data into clusters based on similar features. It attempts to find discrete groupings within the dataset. Within these groupings, members are as similar as possible to one another and as different as possible from members of other groups.

Cluster analysis has many applications in the areas of pattern recognition, image analysis, customer analytics, market segmentation, and more.

For example, imagine that you need to create a model to recognize handwritten digits. You might choose to create 10 clusters, one for each digit (0, 1, …, 9). As part of model training, the algorithm groups the input images into these 10 clusters.

## Next Generation ML

### **Deep Learning**

Deep learning algorithms learn using artificial neural networks (ANNs), which were inspired by the human brain. These ANNs contain layers of artificial neurons (math functions) that mimic real human neurons. Each layer of artificial neurons summarizes and feeds information to the next layer until a final model is produced. During this training process, the algorithm derives the features itself.

**Deep learning use cases**

- Computer vision
- Speech recognition
- Natural language processing
- Recommendation engines

![image.png](AWS%20ML%20Engineer%20Associate%20Curriculum%20Overview%201dab64ea00f7494b97e2e20b63691fcd/image%201.png)

### **Generative AI**

Generative AI is a type of deep learning that can create new content and ideas, including the following:

- Conversations
- Stories
- Images
- Videos
- Music

Generative AI is powered by very large machine learning models that are pre-trained on vast collections of unlabeled data. These are commonly called foundation models (FMs).

![image.png](AWS%20ML%20Engineer%20Associate%20Curriculum%20Overview%201dab64ea00f7494b97e2e20b63691fcd/image%202.png)

**Instead of gathering labeled data for each model and training multiple models, you can use the same pre-trained foundation model to adapt to multiple tasks. You can customize FMs to perform domain-specific functions, using only a small fraction of the data and compute power required to train a model from scratch.**

### **Large language models**

Large language models (LLMs) are a popular type of foundation model. LLMs are trained on a vast amount of text data, such as books, websites, and conversations. This input data helps foundation models learn how language works so they can generate human-like text.

There are multiple use cases for large language models. They include the following:

**Copywriting:** LLMs can write original copy or improve the style and voice of existing sentences.

**Knowledge base answering:** LLMs can answer specific questions related to knowledge bases.

**Text classification:** LLMs can classify text with similar meanings or sentiments, such as measuring customer sentiment.

**Code generation:** LLMs are proficient in code generation from natural language prompts. For example, Amazon Q Developer can generate code in multiple languages, such as Python, TypeScript, and Java.

**Text generation:** LLMs can generate new text. Examples include finishing incomplete sentences, creating product documentation, and writing stories.

## **Eight key dimensions of responsible AI/ML**

![image.png](AWS%20ML%20Engineer%20Associate%20Curriculum%20Overview%201dab64ea00f7494b97e2e20b63691fcd/image%203.png)

## **Formulating Business Problems**

### **Problem formulation phase**

The first and most critical step when developing a machine learning solution is clearly defining the business problem you want to solve. A well-defined problem statement sets the foundation for the entire ML project lifecycle.

The problem formulation phase involves the following steps:

- Define the business problem
- Choose your data
- Identify your ML success criteria

## **Define the business problem**

![image.png](AWS%20ML%20Engineer%20Associate%20Curriculum%20Overview%201dab64ea00f7494b97e2e20b63691fcd/image%204.png)

![image.png](AWS%20ML%20Engineer%20Associate%20Curriculum%20Overview%201dab64ea00f7494b97e2e20b63691fcd/image%205.png)

## **Choose your data**

Before developing a machine learning model, consider which data is needed to properly train and evaluate the model. The quality of the model—and, ultimately, whether it can adequately address the problem at hand—depends heavily on using relevant, high-quality training data.

The following are some key questions to answer regarding your data at this preparatory stage:

**What data do you need to actually train your model to reach the intended output and subsequently your intended business outcome?**

**Do you have access to that data? If so, how much data do you have and where is it?**

**Which solution can you use to bring all this data into one centralized repository?**

To learn more about key considerations for selecting appropriate data to train robust ML models, choose each of the following three tabs.

### Labeled Data

Having properly labeled data allows machine learning models to learn the relationships between features and labels so they can accurately predict labels for new, unlabeled data points. The model relies on the patterns in features to determine the correct label to assign based on its training.

For example, in a credit card fraud detection model, potential features might include the transaction date, vendor, or charge amount. The label for each transaction would be whether it is fraudulent or legitimate, as shown in the following table.

### Data Quality and Relevance

Data used for modeling should contain relevant signals about the phenomena being studied. For example, a wholesaler forecasting product demand should track previous sales and when products were out of stock.

To forecast demand, the wholesaler must know when products were out of stock because no sales occurred at that time, despite underlying customer demand. Therefore, when modeling demand, out of stock events need to be included as an input feature to avoid misleading model training. For instance, out of stock events are included in the following table.

### Additional Data

Obtaining properly labeled data is often a challenge when training ML models. For example, a self-driving car requires image data that is meticulously labeled with the car's precise location at every moment. It needs to know its relative position to objects like roads, signs, and other vehicles.

Manual labeling of such complex data is extremely difficult and time-consuming. Without sufficient labeled data, model accuracy suffers, which can have dire consequences in safety-critical applications like autonomous driving.

## **Identify your ML success criteria**

![image.png](AWS%20ML%20Engineer%20Associate%20Curriculum%20Overview%201dab64ea00f7494b97e2e20b63691fcd/image%206.png)

### **Use cases with different ML success criteria**

![image.png](AWS%20ML%20Engineer%20Associate%20Curriculum%20Overview%201dab64ea00f7494b97e2e20b63691fcd/image%207.png)

![image.png](AWS%20ML%20Engineer%20Associate%20Curriculum%20Overview%201dab64ea00f7494b97e2e20b63691fcd/image%208.png)

![image.png](AWS%20ML%20Engineer%20Associate%20Curriculum%20Overview%201dab64ea00f7494b97e2e20b63691fcd/image%209.png)

![image.png](AWS%20ML%20Engineer%20Associate%20Curriculum%20Overview%201dab64ea00f7494b97e2e20b63691fcd/image%2010.png)