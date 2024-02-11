# 🤗 Synthetic data blog post 
This is the reproduction repository for my Hugging Face blog post on synthetic data [ADD HYPERLINK ONCE PUBLISHED]

Feel free to re-use this code for creating your own synthetic dataset for your own use-cases. 

### Scripts: 
- `synthetic_data_creation.ipynb` is the final script for producing the numbers in the blog post. I recommend reusing the code from this script with asynchronous functions and batching if you want to create your own synthetic data efficiently.
- `synthetic_data_creation_simple.ipynb` is a simplified version of the script for easier readibility in the blog post.
- `synthetic_data_viz.ipynb` creates the visualisations.
- `synthetic_data_costs.ipynb` implements the calculations for monetary costs, latency, throughput and environmental CO2 costs. 

### Data:
The `/data` directory contains the outputs from different LLMs on test data (`df_test...`), the synthetic training dataset created with Mixtral (`df_train...`), as well as the final metrics (`metrics_...`), including metrics from the training run with AutoTrain (`logs_autotrain_roberta.rtf`).


### License
This code is published under the [OpenRAIL license](https://www.licenses.ai/ai-licenses). You are free to use it for most purposes, including commercial activities, but the license restricts certain unethical use-cases, such as surveillance or imitation of people. See details [here](https://www.licenses.ai/source-code-license). 

