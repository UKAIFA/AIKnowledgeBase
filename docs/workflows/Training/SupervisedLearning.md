# Supervised Learning


## Ingredient list:

- Labelled Data source for training and test
- Model definition
- GPU resources
- Model performance requirments
- Training process elements
- Training proceedure
- Result verification

## Data source

- Verify its a labelled
- Stage data
- Define a training and test dataset

## GPU resources

- Example definition of a K8s job
- Example of placing data in PVC so it can be used during a job.


## Model definition

We now need to define the layers the made up a given model in our prefered machine learning training framework. We supply an example for both pytorch and tensorflow to provide a concrete example for the rest of this workflow.

### Pytorch

### Tensorflow


## Training process elements

### Data loader

A data loader needs to be defined to load data from the indentified dataset into the 

#### Pytorch

#### Tensorflow

### Model

We can simply use the model definition defined above.

### Loss function

Choose a loss function for this particular model

#### Pytorch

#### Tensorflow

### Optimizer

#### Pytorch

#### Tensorflow

## Model performance criteria

- Accuracy of a model
- Speed of a model


## Training proceedure

- Train
    - Track the models loss 
- Test
- Measure model performance agains Model performance criteria
- Tune hyper-parameters
- Iterate on model training







