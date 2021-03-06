<a id="an-informal-introduction-to-python" style="width:0;height:0;margin:0;padding:0;">&zwnj;</a>

# An Informal Introduction to Python

In the following examples, input and output are distinguished by the presence or absence of prompts ( [>>>](https://docs.python.org/3/glossary.html#term)  and  […](https://docs.python.org/3/glossary.html#term-1) ): to repeat the example, you must type everything after the prompt, when the prompt appears; lines that do not begin with a prompt are output from the interpreter. Note that a secondary prompt on a line by itself in an example means you must type a blank line; this is used to end a multi-line command.

Many of the examples in this manual, even those entered at the interactive prompt, include comments. Comments in Python start with the hash character,  ```#``` , and extend to the end of the physical line. A comment may appear at the start of a line or following whitespace or code, but not within a string literal. A hash character within a string literal is just a hash character. Since comments are to clarify code and are not interpreted by Python, they may be omitted when typing in examples.

```python
 # Some examples:
# 
 # 
 # this is the first comment 
 spam = 1  # and this is the second comment 
           # ... and now a third! 
 text = "# This is not a comment because it's inside quotes."
```