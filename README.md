# IntegrationTester (Computer Vision)

This repository provides a GUI-based (QT) environment designed to simplify the integration process for various models. 

This tool may be beneficial if you:

- Have correlated models or plan to develop new ones.
- Wish to combine different models using pre-processing, processing, and post-processing techniques.
- Need to debug your model processing health amidst multiple models and are unsure which model(s) is/are causing errors.
- Want to optimize your models based on field tests.
- Need to quantize your models for platforms with limited resources.

# Streamline Your Model Testing

Define the specifications of the input images, relationships between different models, and output results to test your models. This application is designed to simplify the model testing pipelines. The goal is to create a GUI that allows for testing of various model types, reducing the amount of repetitive work involved in model testing.

Operators can add or edit code using GUI tools. Each tool should have a pre-processing, processing, and post-processing environment.

**Note:** If a model's input and output are independent of others, it is recommended to test it separately.

## To-Do List:

1. **Main Window:** 
   - Should be divided into 'n' frames (defined in settings).
   - Odd-numbered frames will display the inputs, and even-numbered frames will display outputs.

2. **Model Definition Window:** 
   - A subwindow of the main window to define the models that will be tested.

3. **Settings**
   - select models.
   - operator should be able to add new models cia + sign.
   - import .py files for pre-processing, processing and post-processing
   - select input data directory for the first model
   - select input and output data directory for each model
   - 
