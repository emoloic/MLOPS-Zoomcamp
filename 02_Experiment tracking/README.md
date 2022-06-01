# Experiment Tracking and Model Registry
<h2> 1. Experiment Tracking </h2>
Experiment tracking is a process of tracking hyperparameters of the model, metrics of the model, metadata of the runs and all the other relevant information of 
a ML experiment such as:

<ol>
  <li> Source code </li>
  <li> Owner </li>
  <li> Hyperparameters </li>
  <li> Models </li>
  <li> Metrics </li>
</ol>

<h3> 1.1 Why experiment tracking is important </h3>
<ol>
  <li> Reproducibility</li>
  <li> Model/Data Lineage </li>
  <li> Organization </li>
  <li> Easy to select best models by tracking experiments </li>
</ol>

<h3> 1.2 MLFlow Library </h3>
MLFlow is an open source machine learning life cycle library. This library helps to tracks experiments by logging metrics,hyperparameters, saving models and its 
main modules are
<ol>
  <li> Tracking </li>
  <li> Models </li>
  <li> Model Registry </li>
  <li> Projects </li>
</ol>

<p> MLFlow not only tracks the model and metrics related data but also source code, author of the run and start and end time of the run </p>

<h2> 2. Model Registry </h2>

<p> Model Registry lists the models which are ready for the production and which are in the production currently, and we are assigning labels to each models to differentiate them, like the models which are ready to be in production and are retrained then they are assigned to staging, and the models which are currently in 
production are assigned to production. </p> 
