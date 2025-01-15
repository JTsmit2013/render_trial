# Tossing a Coin - Streamlit App

This is a simple Streamlit application that simulates the process of tossing a coin and calculates the cumulative mean of outcomes in real-time. The app is designed to demonstrate probability and randomness in a visually engaging way.

## Features

- **Interactive Coin Toss Simulation**: Choose the number of coin tosses using a slider and observe the real-time update of the mean outcome.
- **Data Persistence Across Experiments**: Keeps track of the results of all experiments in the session.
- **Dynamic Line Chart**: Displays the cumulative mean as the trials progress.
- **Session History**: View the results of all experiments conducted during the session.

## Requirements

To run this application, you need the following Python libraries:
- `pandas`
- `scipy`
- `streamlit`

## Installation

1. Clone this repository:
   ```bash
   git clone <repository-url>
   cd <repository-folder>
2. Create a new **Web Service** on Render.

## How to Use

1. Start the app by following the installation instructions.
2. Adjust the **Number of trials** slider to select the desired number of coin tosses (1 to 1000).
3. Click the **Run** button to start the experiment.
4. Watch the line chart update dynamically to show the cumulative mean outcome.
5. View the results of all experiments conducted during the session in the table below the chart.

## Deployment

This app is designed to run on [Render](https://render.com/). To deploy:
1. Push your code to a public or private Git repository.
2. Create a new **Web Service** on Render.
3. Use the following build and start commands:
   - **Build Command**: 
     ```bash
     pip install -r requirements.txt
     ```
   - **Start Command**: 
     ```bash
     streamlit run app.py --server.port $PORT --server.address 0.0.0.0
     ```
4. Wait for the deployment to complete, and access your app via the generated URL.

## Example Output

1. **Line Chart**: Displays the mean of outcomes (probability of heads).
2. **Experiment History**: 
   - Experiment Number
   - Number of Trials
   - Mean Outcome


