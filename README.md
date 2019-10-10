# Create DynamoRIO Visual Studio Project
Forked from [fdiskyou/DBI](https://github.com/fdiskyou/DBI), Remove the file related to Intel PIN

**Usage:**


```shell
python create_dynamorio_project.py -h
usage: create_dynamorio_project.py [-h] -p PROJECT_NAME -a {32,64}

Create DynamoRIO Project

optional arguments:
  -h, --help            show this help message and exit

required arguments:
  -p PROJECT_NAME, --project PROJECT_NAME
                        DynamoRIO VS Project Name
  -a {32,64}, --arch {32,64}
                        x86 or x64
```