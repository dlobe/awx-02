# How to use this project

This is Repo has 2 main function:
1. list manipulation with ansible
2. use of ansible slurp module

## Use of ansible slurp module 
This project consists in copying files from one directory to another within a
target node using tower. The list of source files and destination directories
are given in as a json file. In order to read the json file, we used slurp 
module. But after decoding the base64 characters, the registered value is a 
long string. We used different forms of filtering to permit us have the right 
ddata type. 

