
![banner](https://github.com/user-attachments/assets/7c7e9939-a15c-4cc1-90b0-ffa8d7d51996)

# COMP08101 - Programming for Cyber

The repositories here contain sample code and worked examples from the weekly labs. The repositories contain code formatted for PyCharm, individual scripts might require additional modules to be installed via Anaconda.

**These repositories and their contents should remain private!** 

## Aims and Objectives

- L1. Effectively use a variety of software libraries to develop cyber security tools;​

- L2. Employ software tools to facilitate and automate cyber security processes;​

- L3. Understand how software tools can be chained to accomplish complex tasks;

## Labs
Overview the labs. Each lab contains multiple tasks that the student has to complete. Some of
the tasks will be included within the portfolio which makes up the final mark.

| Week | Activity                                                |
|------|---------------------------------------------------------|
| 1    | Introduction and setup                                  | 
| 2    | Introductory concepts                                   |
| 3    | Strings and collections                                 |
| 4    | Functions (hashes, Ceasar cipher)                       |
| 5    | Files access                                            |
| 6    | Command line parameters                                 |
| 7    | Optimisation and Efficiency                             |
| 8    | Scripts to automate cyber security (packet examination) |
| 9    | Scripts to automate cyber security (port scanning)      |
| 10   | Web scraping (beautiful soup)                           |
| 11   | Regular expressions                                     |





## Assessments

The unit is very practical. The results are measured by a portfolio (40%) and the production
of a tool (60%). A selection of tasks from the weekly labs will be selected to be included in 
the portfolio. 


## Environment

![image](https://github.com/user-attachments/assets/22444843-d78e-4a4c-9068-8ee71407ccc3)
Development language is Python. The suggested development environment is [Pycharm](https://www.bing.com/ck/a?!&&p=5884d82a0aed981a9ef6347fe2a632a1c20124229f6802ee109ddbae2ae58891JmltdHM9MTc0MDcwMDgwMA&ptn=3&ver=2&hsh=4&fclid=06a5893f-ee71-6ff8-1d3f-9cbaef0b6efc&psq=pycharm&u=a1aHR0cHM6Ly93d3cuamV0YnJhaW5zLmNvbS9weWNoYXJtLw&ntb=1). UWS suggest the use of PyCharm Professional for the unit. Instructions are provided to connect to the 
UWS licence server. PyCharm Community Edition 2024 has proven to be sufficient for the unit. The only
advantage of the Professional edition would be the inclusion of Jupyter Notebooks, but none of these
have been supplied for the unit. If required these could be opened in Visual Studio Code with minimum
effort. Some of the labs require a plain Python installation. Other labs require the use of external modules which can be installed via Anaconda.

![image](https://github.com/user-attachments/assets/ce55d38d-abff-4ee4-bf42-2a641125f753)
UWS suggest that [Anaconda](https://www.anaconda.com/download) is used as an environment for development, with a suggested
env name of P4CS. MiniConda works just as well as the full Anaconda installation, you just need
to be comfortable using the command line. 

Note: AY 2024/25 - The Anaconda Prompt worked for the lecturer but the didn't for the students.
UWS documentation says that Anaconda Powershell won't work but students had no issue using this on 
the college computers. 

The following packages are required,
- requests
- beautifulsoup4
- scapy*
- matplotlib
- dnspython

*scapy. The version (2.4.3) that installed through Anaconda didn't include everything required for the labs. A
newer version (2.6.1) had to be downloaded. The command to do this is, 

`conda install -c conda-forge scapy --force-reinstall`

![image](https://github.com/user-attachments/assets/34584181-e863-4559-8ab0-461c946c73b0) 

AY 2024/25 There were many problems found while using SCAPY, the above update fixed some but not all. Installing nmap seemed to solve all the remaining issues. The latest version can be found here [NMAP](https://www.bing.com/ck/a?!&&p=37cf78f77879e95f5616f04a5bda2fccb614a2297711433ffcdc3861b470a9b9JmltdHM9MTc0MDcwMDgwMA&ptn=3&ver=2&hsh=4&fclid=06a5893f-ee71-6ff8-1d3f-9cbaef0b6efc&psq=nmap&u=a1aHR0cHM6Ly9ubWFwLm9yZy8&ntb=1).


