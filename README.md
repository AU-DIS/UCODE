# UCoDe: Unified Community Detection with Graph Convolutional Networks

Implementation of UCoDe for overlapping and non-overlapping community detection as proposed in the paper:

This implementation is written in Python 3.

# Requirements
<ul>
  <li>networkx</li>
  <li>numpy</li>
  <li>pandas</li>
  <li>scikit-learn</li>
  <li>scipy</li>
  <li>torch==1.10.0</li>
</ul>

# Installation
    
You can install all the required packages using the following command:

$conda create --name <env> --file requirements.txt

# Run the code

Run main.py for an example result of non-overlapping community detection.
<br>Run mainOUCODE.py for an example result of overlapping community detection.

# Cite 


@article{moradan2023ucode,
<br>author = {Moradan, Atefeh and Draganov, Andrew and Mottin, Davide and Assent, Ira},
<br>title = {UCoDe: unified community detection with graph convolutional networks},
<br>journal = {Machine Learning},
<br>pages={1--24},
<br>year = {2023},
<br>publisher = {Springer},
<br>}



