# deep_learning_challenge

Module 21 challenge on deep learning and neural networks.

This challenge is to design a tool for the nonprofit foundation called Alphabet Soup to select applicants for funding where the projects to be funded have the best chance of success.  

The input data on applicants that was provided by Alphabet Soup are retrieved through an online source created specifially for educational purposes and available at "https://static.bc-edx.com/data/dl-1-2/m21/lms/starter/charity_data.csv").

The tool was written in a form of jupyter notebook on Google Colab, and uses scikit learn, tensorflow and keras tuner.  Tensor flow is avaiable directly on Google CoLab, but Keras tuner has to be installed directly in the script because it is not part of the packages already installed on Google colab.

Part of the project requirements are to output the results to an HDF5 file, which then must be separately downloaded to a local device for upload to GitHub.  

The project requirements are to submit to scripts, one original and one with an optimized model, and two HDF5 files.  Because keras tuner is not part of the project requirements, a third notebook is included with the delivery that uses keras tuner to find the best model configuration.   That part was developed and run after at least 25 manual configuration efforts at optimization.

Explanations of the data, the preprocessing, the model configurations, and the results are all contained in a separate report for Alphabet Soup, which is included here as "deep_learning_challenge_final_report.docx".
