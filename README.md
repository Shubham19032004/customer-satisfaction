
# customer-satisfaction





#
To run
```bash
python -m venv customerenv
pip install -r requirements. txt 
```
#
#
```bash
pip install zenml["server"]
zenml up
```

#

```bash
zenml integration install mlflow -y
```

```bash
zenml integration install mlflow -y
zenml experiment-tracker register mlflow_tracker --flavor=mlflow
zenml model-deployer register mlflow --flavor=mlflow
zenml stack register mlflow_stack -a default -o default -d mlflow -e mlflow_tracker --set
```

![pipelines](https://github.com/Shubham19032004/customer-satisfaction/assets/118589955/baf698d2-9248-4685-93ff-09e0d05f47fc)
![runs](https://github.com/Shubham19032004/customer-satisfaction/assets/118589955/fe5253a3-280e-4e20-9ea0-e63ec5a6608d)


