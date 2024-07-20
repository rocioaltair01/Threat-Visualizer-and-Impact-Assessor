# Threat Visualizer and Impact Assessor

## Overview

The **Threat Visualizer and Impact Assessor** is a Python application designed to visualize and evaluate attack trees. It allows users to:

- Import attack tree specifications
- Interactively add new risks
- Assign probabilities to risks
- Calculate the overall threat assessment rating

The application supports industry-standard file formats including JSON, YAML, and XML.

## Features
- **Load Attack Trees:** Import attack tree specifications from JSON, YAML, or XML files.
- **Visualize Trees:** Generate graphical representations of the attack trees.
- **Interactive Node Addition:** Add new risk nodes interactively.
- **Risk Value Assignment:** Enter probabilities for leaf nodes.
- **Threat Assessment Calculation:** Aggregate probabilities to assess the overall threat rating.

## Requirements

- Required Python libraries:
  - `networkx`
  - `matplotlib`
  - `pyyaml`
  - `xml.etree.ElementTree` (Standard library)

## Installation
- Install Dependencies:
```bash
pip install networkx matplotlib pyyaml
```

## Usage
- Run the Application:
```bash
python attack_tree_app.py
```

- Enter the Attack Tree Specification:
- Enter the attack tree specification (in an industry-standard format such as XML, YAML, or JSON):attack_tree.json
```bash
attack_tree.json
```

- Add Risks:
- Enter the parent node to which you want to add a new risk.
  - Input the name of the new risk node.
  - Type exit when you are finished adding nodes.
  - Enter the parent node to which you want to add a new node (or 'exit' to quit): exit
  - Enter the new node name to add under 'Risk1': Risk2

- Enter probability of Risk and aggregate value of the overall thread rating probability:
  - Value for Sabotage (suffix '%' for probability): 8%

After all commands are finished, the application will visualize the attack tree graph as below:
<img width="958" alt="Screenshot 2024-07-20 at 2 11 09 PM" src="https://github.com/user-attachments/assets/0015f5d5-f5b7-4e7a-a35a-a210019fdd62">


Command example:
<img width="767" alt="Screenshot 2024-07-20 at 4 10 26 PM" src="https://github.com/user-attachments/assets/baaf41be-cbc9-434f-8710-95bfeba118c7">
