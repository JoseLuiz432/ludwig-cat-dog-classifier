# ludwig-cat-dog-classifier
An example how to use ludwig AutoML to classifying images.

[What is AutoML?](https://en.wikipedia.org/wiki/Automated_machine_learning)

[What is Ludwig?](https://ludwig.ai/late)

# Env preparate
First thing you need to do is preparate the enviroiment, installing ludwig, etc.

To this porpose I recoment to create a new env:
```
  python -m venv venv
```

Activate the env and installing ludwig
```
  python -m pip install --upgrade pip &&  python -m pip install ludwig
```

# Configuration
This is a important aspect when using ludwig I put a configuration file in this repository: config.yaml. For more detaled information please see the oficial documentation [Configuration](https://ludwig.ai/latest/configuration/) 

# Train

Ludwig train command:
```
ludwig train \
  --dataset cats-dogs.csv \
  --config config.yaml
```
# Evaluate

# Visualize Metrics

# Predictions


# Using pretrained model 

You can find all available Pretrained models at (here)[https://ludwig.ai/latest/configuration/features/image_features/]. To use this models you can add the model you want inside the config file as config_pretrained.yaml I put in this repo.