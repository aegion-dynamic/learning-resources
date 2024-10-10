# Data Pipeline Development

### Motivation

In the field of machine learning or generally any kind of statistical data processing, creating data clean up pipelines, etc. are super critical. However, these pipelines are hard to maintain ensure reproducibility. Here we give general guidelines of how to setup a data pipeline, point you to reference repositories, etc. Our pipeline uses Python as the default programming language of choice not only for its ease of use but also for its versatility to interact with other computing environments.

### Environment Setup

As with all the other the other python projects, we recommend the use of `pyenv` and `Poetry` for managing dependencies and the environment. Once you setup the project the main directory needs to look like what is shown below:

### Project Directory Setup

We breakdown the pipeline code organization in terms of `Objectives -> Studies -> Field Actions`

```
project-dir
|-<pipeline_name_1>
    |-entrypoint.py
    |-<objective_1>
        |-<study_name_1>.py
        |-<study_name_2>.py
        |-...
    |-<objective_2>
    |-<objective_3>
    |-...
|-<pipeline_name_2>
|-<pipeline_name_3>
|-...
|-utils
    |-__init__.py
    |-utils_1.py
    |-utils_2.py
```

Since every study has fields associated with it, you can put all the&#x20;

```
# <study_name_1>.py


def <action>_<field_1>(args1: argtype1, ...)->rettype:
    ...
    return ret
    
    
def <action>_<field_2>(args1: argtype1, ...)->rettype:
    ...
    return ret
    
    
def <action>_<field_3>(args1: argtype1, ...)->rettype:
    ...
    return ret

```

In the entry point file ensure that all the actions are applied linearly.

```
# entrypoint.py


def execute_pipeline():
    
    data_frame = load_data()

    data_frame = <action>_<field_1>(data_frame)
    data_frame = <action>_<field_2>(data_frame)
    data_frame = <action>_<field_3>(data_frame)
    
    save_data()

```



```
project-dir
|-pipeline
    |-__init__.py
    |-entrypoint.py
    |-compute //This is an example of the objective
        |-__init__.py
        |-compute_<study_name1>.py
        |-compute_<study_name2>.py
        |-...
    |-cleanup //This is an example of the objective
        |-__init__.py
        |-cleanup_<study_name1>.py
        |-cleanup_<study_name2>.py
        |-...
|-tests
|-pyproject.toml
```

The directories like `compute` and `cleanup` are derived from the objectives of statistical study.



TODO: Add more examples for more ML like ETL pipelines





