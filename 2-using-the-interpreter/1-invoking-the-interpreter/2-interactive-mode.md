<a id="interactive-mode" style="width:0;height:0;margin:0;padding:0;">&zwnj;</a>

# Interactive Mode

When commands are read from a tty, the interpreter is said to be in  *interactive mode* . In this mode it prompts for the next command with the  *primary prompt* , usually three greater-than signs ( ```>>>``` ); for continuation lines it prompts with the  *secondary prompt* , by default three dots ( ```...``` ). The interpreter prints a welcome message stating its version number and a copyright notice before printing the first prompt:

```python
 $ python3.6
 Python 3.6 (default, Sep 16 2015, 09:25:04)
 [GCC 4.8.2] on linux
 Type "help", "copyright", "credits" or "license" for more information.
 >>>
```

Continuation lines are needed when entering a multi-line construct. As an example, take a look at this  [if](https://docs.python.org/3/reference/compound_stmts.html#if)  statement:

```python
 >>> the_world_is_flat = True
 >>> if the_world_is_flat:
 ...     print("Be careful not to fall off!") 
 ...

 Be careful not to fall off!
```