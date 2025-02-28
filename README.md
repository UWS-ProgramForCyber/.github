<img alt="UWS logo" src="\resources\UniWestScotland.jpg" title="UWS logo"/>

# COMP08101 - Programming for Cyber

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
the portfolio. The code in this project is from the labs so can not be shared with the students.

## Environment

Some of the labs require a plain Python installation. Other labs require the use of external
modules. UWS suggest that Anaconda is used as an environment for development with a suggested
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

UWS suggest the use of PyCharm Professional for the unit. Instructions are provided to connect to the 
UWS licence server. PyCharm Community Edition 2024 has proven to be sufficient for the unit. The only
advantage of the Professional edition would be the inclusion of Jupyter Notebooks, but none of these
have been supplied for the unit. If required these could be opened in Visual Studio Code with minimum
effort.
