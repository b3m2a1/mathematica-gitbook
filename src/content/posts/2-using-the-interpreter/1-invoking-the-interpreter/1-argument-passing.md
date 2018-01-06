Title: Argument Passing
Authors: 
Categories: python
Date: 2018-01-05 16:26:17
ID: 2.1.1
Modified: 2018-01-05 16:26:17
Path: Using the Python Interpreter/Invoking the Interpreter
Slug: argument-passing
Tags: interpreter

<a id="argument-passing" style="width:0;height:0;margin:0;padding:0;">&zwnj;</a>

# Argument Passing

When known to the interpreter, the script name and additional arguments thereafter are turned into a list of strings and assigned to the argv variable in the  ```sys```  module. You can access this list by executing  ```import sys``` . The length of the list is at least one; when no script and no arguments are given,  ```sys.argv[0]```  is an empty string. When the script name is given as  ```'-'```  (meaning standard input),  ```sys.argv[0]```  is set to  ```'-'``` . When  ```-c```  command is used,  ```sys.argv[0]```  is set to  ```'-c'``` . When  ```-m```  module is used,  ```sys.argv[0]```  is set to the full name of the located module. Options found after  ```-c```  command or  ```-m```  module are not consumed by the Python interpreter’s option processing but left in  ```sys.argv```  for the command or module to handle.