# BlackWinterSecurity

### The following python script was designed to create webshell for the following lang's:
- ASP
- ASPX
- PHP

### How to use:
To install all of the tools, run the following command:
```sh
$ python createWebShell.py -h
usage: createWebShell.py [-h] -t File_Type -ip ip_Address [-p Port] -o Output_File

Create WebShell for Education Purpose ONLY.

optional arguments:
  -h, --help      show this help message and exit
  -t File_Type    WebShell file type, options: php, asp, aspx
  -ip ip_Address  Enter local host IP Address
  -p Port         Enter local host PORT, Default: 8080
  -o Output_File  Enter the name of the output file

Ex: python createWebShell.py -t php -ip 10.10.10.10 -p 8080 -o myshell.php
```

## Developer
badc0d3 
