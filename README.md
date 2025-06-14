"# MLFLoW-Experiments" 


import dagshub
dagshub.init(repo_owner='vishalgoyal25', repo_name='MLFLoW-Experiments', mlflow=True)

import mlflow
with mlflow.start_run():
  mlflow.log_param('parameter name', 'value')
  mlflow.log_metric('metric name', 1)