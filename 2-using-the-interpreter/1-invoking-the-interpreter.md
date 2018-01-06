<a id="invoking-the-interpreter" style="width:0;height:0;margin:0;padding:0;">&zwnj;</a>

# Invoking the Interpreter

The Python interpreter is usually installed as  ```/usr/local/bin/python3.6```  on those machines where it is available; putting  ```/usr/local/bin```  in your Unix shell’s search path makes it possible to start it by typing the command:

```bash
 python3.6
```

to the shell. Since the choice of the directory where the interpreter lives is an installation option, other places are possible; check with your local Python guru or system administrator. (E.g.,  ```/usr/local/python```  is a popular alternative location.)

On Windows machines, the Python installation is usually placed in  ```C:\Python36``` , though you can change this when you’re running the installer. To add this directory to your path, you can type the following command into the command prompt in a DOS box:

```bash
 set path=%path%;C:\python36
```

Typing an end-of-file character ( ```Control-D```  on Unix,  ```Control-Z```  on Windows) at the primary prompt causes the interpreter to exit with a zero exit status. If that doesn't work, you can exit the interpreter by typing the following command:  ```quit()``` .

The interpreter’s line-editing features include interactive editing, history substitution and code completion on systems that support readline. Perhaps the quickest check to see whether command line editing is supported is typing  ```Control-P```  to the first Python prompt you get. If it beeps, you have command line editing; see  [Appendix Interactive Input Editing and History Substitution](https://docs.python.org/3/tutorial/interactive.html#tut-interacting)  for an introduction to the keys. If nothing appears to happen, or if  ```^P```  is echoed, command line editing isn’t available; you’ll only be able to use backspace to remove characters from the current line.

The interpreter operates somewhat like the Unix shell: when called with standard input connected to a tty device, it reads and executes commands interactively; when called with a file name argument or with a file as standard input, it reads and executes a  *script*  from that file.

Some Python modules are also useful as scripts. These can be invoked using  ```python -m module [arg] ...``` ,  which executes the source file for module as if you had spelled out its full name on the command line.

When a script file is used, it is sometimes useful to be able to run the script and enter interactive mode afterwards. This can be done by passing  [-i](https://docs.python.org/3/using/cmdline.html#cmdoption-i)  before the script.

All command line options are described in  [Command line and environment](https://docs.python.org/3/using/cmdline.html#using-on-general) .