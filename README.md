Process Mining Project

This project is designed to analyze and gain insights from event logs using process mining techniques. The aim is to identify, analyze, and visualize business processes based on event data to enhance process efficiency and performance.
Project Overview

    Objective: Perform process mining on event logs to uncover patterns and improve business process understanding.
    Tools: Python, pm4py library for process mining, visualization libraries (e.g., Matplotlib, Seaborn).

Key Features

    Data Preprocessing: Clean and prepare event log data for analysis.
    Process Discovery: Generate process models using methods like the Heuristic Miner or Inductive Miner.
    Performance Analysis: Analyze key performance indicators such as throughput time and resource utilization.
    Visualization: Visualize the discovered processes and metrics using various charts and graphs.

Installation

To run this project, you’ll need to install the necessary dependencies.

    Clone this repository:

git clone https://github.com/your-username/ProcessMiningProject.git

Navigate into the project folder:

cd ProcessMiningProject

Create a virtual environment and activate it:

python -m venv env
source env/bin/activate  # On Windows use `env\Scripts\activate`

Install the required libraries:

    pip install -r requirements.txt

    Note: Ensure that pm4py is installed, as it is essential for process mining tasks.

Usage

    Data Preparation: Place your event log file (in CSV or XES format) in the data/ folder.
    Run Analysis: Use the provided scripts to preprocess data, discover processes, and generate insights.

    python main.py

    Visualization: Review the generated process maps and performance visualizations in the output/ folder.

Project Structure

    data/: Folder to store event log files.
    img/: Process discovery images
    main.py: Main script to run the entire process mining workflow.
    requirements.txt: Contains the list of dependencies.