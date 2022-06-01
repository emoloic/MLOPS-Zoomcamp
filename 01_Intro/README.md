# Introduction to Machine learning Operations

<h2> 1. What is MLOps </h2>

Machine learning is not only about modelling and selecting appropriate network architecture or method for solving any business problem. Even 99 % accurate model deteriorates over time 
and most of the bussiness suffers from this because they dont have strategies to deploy and monitor the machine learning models. There comes the Machine learning Operations come to the rescue.

Machine Learning Operations(MLOps) is methodology for maintaining ML systems. Similar to DevOps, MLOps looks to increase the automation and improve the quality of ML models,
without hampering the business needs.

Using MLOps, organization can efficiently and reliably transition the model to production.

Phases of MLOps:

1. Data Gathering
2. Data Processing
3. Data Cleaning
4. Model Training and development
5. Model Evaluation
6. Model Serving
7. Model Monitoring
8. Model Re-Training

<h2> 2. MLOps Maturity Model </h2>

<table>
  <tr>
    <th> Level </th>
    <th> Description </th>
    <th> Highlights </th>
  </tr>
  
  <tr>
    <th> 0 </th>
    <th> No MLOps </th>
    <th> No automation and only notebook code, Organization focusing on POC for implementing Machine learning to solve their business problem </th>
  </tr>
  
  <tr>
    <th> 1 </th>
    <th> Devops, No MLOps </th>
    <th> There is some level of Automation, you can deploy a model in the same way as deploying web service, but No experiment tracking, no reproducibility </th>
  </tr>
  
  <tr>
    <th> 2 </th>
    <th> Automated Training </th>
    <th> We have Training pipeline such as train.py scripts for training the model, Tracking the experiment for model reproducibility, and registering model in model registry, when an organization have more than 2 or 3 use cases, then one should consider this maturity model </th>
  </tr>
  <tr>
    <th> 3 </th>
    <th> Automated Deployment </th>
    <th> Easy to deploy model, Model Monitoring and performing AB testing for deploying best model in production </th>
  </tr>
  <tr>
    <th> 4 </th>
    <th> Full MLOps Automated Operations </th>
    <th> No human decision involved in Full MLOps automated operations, Production systems are providing information on how to improve systems </th>
  </tr>
  
</table>

<h2> 3. Running Example </h2>
<p> duration-prediction.ipynb notebook contains code snippet for NYC-taxi duration prediction model training  </p>
  
