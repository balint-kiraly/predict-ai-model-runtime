# predict-ai-model-runtime

**Team:** DeapLearners

**Members:** Jan Cardinael (M1GVE2), Bálint Király (EQF1M0)

> [!NOTE]
> Gyula Máté Szabó (A0KINA) was originally a member of the team but did not make any contributions.

**Task:**
The “Fast or Slow? Predict AI Model Runtime” challenge is a deep learning regression task where the goal is to predict the runtime of AI models on TPUs from their computational graphs and compiler configurations.
Each sample contains a graph of tensor operations, configuration parameters, and the measured execution time.
The task is to train a machine learning model and estimate or rank runtimes for unseen configurations.
Accurate predictions can help optimize compilation and improve hardware efficiency without costly real-world benchmarking.
Read more at: https://www.kaggle.com/competitions/predict-ai-model-runtime

**Data source:** https://www.kaggle.com/competitions/predict-ai-model-runtime/data

### Milestone I.

You can find the code for data exploration and preparation in `predict_ai_model_runtime_eda.ipynb` notebook.

### Milestone II.

The code for the baseline model training and evaluation is in `predict_ai_model_runtime_baseline.ipynb`.

### Final Model

Our final model can be found in `predict_ai_model_runtime.ipynb`.
