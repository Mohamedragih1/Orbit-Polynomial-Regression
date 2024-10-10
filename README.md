# Orbit Polynomial Regression

## Objective
The primary objective of this notebook is to build and train a deep learning model to predict the y-coordinate of a polynomial orbit based on time steps. This model aims to approximate the behavior of an orbit using a neural network, enabling the prediction of the y-coordinate given specific time steps.

## Dataset Description
The dataset used in this project is a CSV file named `orbit.csv`, which contains the following columns:
- `time_steps`: An array of time steps for which the orbit positions are calculated.
- `y`: The corresponding y-coordinate positions of the orbit at each time step.

## Steps to Run the Code in Colab
1. **Open the Notebook**: Access the notebook on Google Colab.
2. **Upload the Dataset**: Ensure that the `orbit.csv` file is uploaded to your Colab environment or accessible through a cloud storage service like Google Drive.
3. **Load Libraries**: Import the necessary libraries in your notebook.
4. **Load the Dataset**: Load the data from the CSV file into your notebook environment.
5. **Construct the Model**: Define the architecture of the neural network according to the requirements of your project.
6. **Compile and Train the Model**: Compile the model and fit it to the training data.
7. **Evaluate the Model**: Use the model to predict the orbit and evaluate its performance.
## Old Orbit prediction VS New Orbit prediction
![old predicted orbit](https://github.com/user-attachments/assets/8a707913-c841-4413-88f7-8f922b5d8832)
![new predicted orbit](https://github.com/user-attachments/assets/5f76608e-a3e2-4c86-8365-78481ea71de2)
