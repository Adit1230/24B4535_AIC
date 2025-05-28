Monthlong preparation plan for Hackathons:


Week 1

Problem Selection:
    Decide which problem to tackle. Consider factors like complexity, time constraint, team strengths, previous experience, etc.
    Finalise the problem after discussion with all teammates.
    Decide what type of model must be built. Use models like CNNs for multi dimensional data and models like LSTMs and transformers for sequential data.
    Decide on the type of input data that will be used.
    Quantify what the output of the model should be, i.e what should it predict.

Data Acquisition:
    Search for datasets and download them.
    If no datasets are available or the datasets don't contain enough data, search for other sources of data.
    Scrape websites for data or create data yourself for example by clicking pictures for computer vision or asking chatgpt for texts for nlp.
    Convert the data into a type that is suitable and easy to work with, such as csv files.

Data Augmentation:
    If the amount of data is still less, manipulate the data a little, add some noise and use other processing techniques such as replacing with synonyms for text and flipping/rotating for images. This can increase the amount of data to train on.


Week 2

Exploratory Data Analysis:
    Look at some samples of data
    Check the means, standard deviations, correlation values, mutual information values, etc.
    Visualise the data using plots and graphs such as histograms, boxplots and scatter plots.
    Use jupyter notebook and libraries such as pandas, matplotlib, seaborn, etc. for this.
    Look for anomalies or errors or corrupted data.
    Find out which features are most important for the predictions.

Data Preprocessing:
    Remove or replace erroneous values from the dataset.
    Fix any corrupted data if possible
    Neutralise any anomalies or biases in the data.
    Create structures like datsets and dataloaders to access the data easily.
    Split the data into training and testing datasets.
    You can use pandas, sklearn, nltk, opencv, etc. for this.

Model building and app development:
    Parallelly start building the model and developing the frontend of the final app.


Week 3

Model building:
    Build the basic structure of the model and the data pipeline.
    Try using a pre trained model built for a similar task.
    Set a loss function, optimiser and learning rate scheduler.
    You can use pytorch, tensorflow, transformers, etc.

Model training:
    Make a training and evaluation loop.
    Experiment with different loss functions, optimisers, learning rate schedulers, dropout, etc.
    Experiment with different sizes and complexities of model and choose the best size. A too simple model will not be able to perform the task as well, but a too complex model will overfit the data if the amount of data is not enough.
    Train the model to a baseline level.

App Develepment (if required):
    Start developing the final app.
    Create the UI of the app and write the logic of the backend leaving space for the model to be integrated.


Week 4

Model optimisation and fine tuning:
    Experiment with different learning rates, weight decays, dropouts, normalisation, etc. and train the model further in order to further improve the accuracy of the model.
    Freeze the backbone and fine tune the last few layers.
    Fine tune the hyperparameters and train the model to achieve maximum accuracy.

Deployment:
    Integrate the model into a usable app.
    Optimise the model for performance.

Documentation and Presentation:
    Finish up on the documentation of the project.
    Make a report and presentation of the project.



Team roles:

    Data Engineer : Source and clean data. Explore and analyse data.
    ML Engineer : Build and train the AI model.
    App Developers (if required) : Build the final app.
    Communicators : Create the presentation and report and present to judges if required.
    Team lead : Coordinate between people, assign roles and keep track of progress. Help others in their work.