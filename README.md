<!-- SPACY PROJECT: AUTO-GENERATED DOCS START (do not remove) -->

# 🪐 spaCy Project: Tech Topic Model

A machine learning model that checks if a news article title is part of the tech topic or not. Based on the demo textcat project
for spaCy. The data comes from a [Kaggle News Article Dataset](https://www.kaggle.com/rmisra/news-category-dataset)

## 📋 project.yml

The [`project.yml`](project.yml) defines the data assets required by the
project, as well as the available commands and workflows. For details, see the
[spaCy projects documentation](https://spacy.io/usage/projects).

### ⏯ Commands

The following commands are defined by the project. They
can be executed using [`spacy project run [name]`](https://spacy.io/api/cli#project-run).
Commands are only re-run if their inputs have changed.

| Command | Description |
| --- | --- |
| `convert` | Convert the data to spaCy's binary format |
| `train` | Train the tech topic model |
| `evaluate` | Evaluate the model and export metrics |
| `package` | Package the trained model as a pip package |
| `visualize-model` | Visualize the model's output interactively using Streamlit |

### ⏭ Workflows

The following workflows are defined by the project. They
can be executed using [`spacy project run [name]`](https://spacy.io/api/cli#project-run)
and will run the specified commands in order. Commands are only re-run if their
inputs have changed.

| Workflow | Steps |
| --- | --- |
| `all` | `convert` &rarr; `train` &rarr; `evaluate` &rarr; `package` |

### 🗂 Assets

The following assets are defined by the project. They can
be fetched by running [`spacy project assets`](https://spacy.io/api/cli#project-assets)
in the project directory.

| File | Source | Description |
| --- | --- | --- |
| [`assets/tech_topic_training.jsonl`](assets/tech_topic_training.jsonl) | Local | tech topic training data |
| [`assets/tech_topic_eval.jsonl`](assets/tech_topic_eval.jsonl) | Local | tech topic development data |

<!-- SPACY PROJECT: AUTO-GENERATED DOCS END (do not remove) -->
