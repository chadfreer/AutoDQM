# AutoDQM
AutoDQM parses DQM histograms and quickly identifies outliers for further analysis. AutoDQM's output can be easily parsed by eye on an AutoPlotter-powered html page, autogenerated when you run AutoDQM using the included bash script.

Example Output: http://uaf-10.t2.ucsd.edu/~jguiang/dqmGUI\_test
AutoPlotter: http://github.com/jkguiang/AutoPlotter

## Features

###### AutoDQM.py
- [x] Outputs histograms that clearly highlight outliers
- [x] Creates a .txt file along with each .pdf with relevant information on it
- [x] Allows user to easily change input
- [ ] Seeks and accurately finds outliers

###### index.php
- [x] Dynamically displays text files below AutoPlotter toolbar
