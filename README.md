Threat Visualizer and Impact Assessor
Overview
The Threat Visualizer and Impact Assessor is a Python application designed to visualize and evaluate attack trees. This tool allows users to import attack tree specifications, interactively add new risks, assign probabilities to risks, and calculate the overall threat assessment rating. It supports industry-standard file formats including JSON, YAML, and XML.

Features
Load Attack Trees: Import attack tree specifications from JSON, YAML, or XML files.
Visualize Trees: Generate graphical representations of the attack trees.
Interactive Node Addition: Add new risk nodes interactively.
Risk Value Assignment: Enter probabilities for leaf nodes.
Threat Assessment Calculation: Aggregate probabilities to assess the overall threat rating.

Requirements
Required Python libraries:
networkx
matplotlib
pyyaml
xml.etree.ElementTree (Standard library)

Installation
Install Dependencies:
pip install networkx matplotlib pyyaml

Usage
Run the Application:
python attack_tree_app.py

Enter the Attack Tree Specification:
Enter the attack tree specification (in an industry-standard format such as XML, YAML, or JSON): attack_tree.json

Add Risks:
Enter the parent node to which you want to add a new risk.
Input the name of the new risk node.
Type exit when you are finished adding nodes.
Enter the parent node to which you want to add a new node (or 'exit' to quit): Risk1
Enter the new node name to add under 'Risk1': Risk2

Enter probability of Risk and aggregate value of the overall thread rating probability:
Value for Sabotage (suffix '%' for probability): 8%