<h1 class="gap">0x00. Python - Hello, World</h1>
<article id="description" class="gap formatted-content">
    <p><img src="https://s3.amazonaws.com/intranet-projects-files/holbertonschool-higher-level_programming+/231/48a9fdbd67c84a328a9df9ec8d93b9ac2458ac37721d7d53e51a27fb2bdc5263.jpg" alt="" style=""></p>

<h2>Author’s disclaimer</h2>

<pre><code>Welcome to the Python world!

After 3 months of C, you will start Python today.
The first projects are more "C-oriented" - no tricks, no funky syntax - simple!
If you've already played with Python, don't worry, fun things will come.
You'll soon find that with Python (and the majority of higher level languages), there are ten different ways to do the same thing. Some tasks will expect only one implementation, while other tasks will have multiple possible implementations.
Like C, Python also has a linter / style guide like Betty, called PEP8, also now known as PyCode. At Holberton, we won't start off with using PyCode, because it's much more strict compared to PEP8. Don't worry if you see a warning when you are running PEP8, you can ignore it.

Enjoy!

- Guillaume, CTO at Holberton
</code></pre>

<h2>Resources</h2>

<p><strong>Read or watch</strong>:</p>

<h2>Resources</h2>
Read or watch:

- [The Python tutorial](https://docs.python.org/3.7/tutorial/index.html) (only the first three chapters below)
    - [Whetting Your Appetite](https://docs.python.org/3.4/tutorial/appetite.html)
    - [Using the Python Interpreter](https://docs.python.org/3.4/tutorial/interpreter.html)
    - [An Informal Introduction to Python](https://docs.python.org/3.4/tutorial/introduction.html) (Read up until “3.1.2. Strings” included)
- [How To Use String Formatters in Python 3](https://www.digitalocean.com/community/tutorials/how-to-use-string-formatters-in-python-3)
- [Learn to Program](https://www.youtube.com/playlist?list=PLGLfVvz_LVvTn3cK5e6LjhgGiSeVlIRwt)
- [PEP 8 – Style Guide for Python Code](https://www.python.org/dev/peps/pep-0008/)

<h2>Learning Objectives</h2>

<p>At the end of this project, you are expected to be able to <a href="/rltoken/fBqNUTa-ZywgkDpUYfAzAQ" title="explain to anyone" target="_blank">explain to anyone</a>, <strong>without the help of Google</strong>:</p>

<h3>General</h3>

<ul>
<li>Why Python programming is awesome (don’t forget to tweet today, with the hashtag #pythoniscool :))</li>
<li>Who created Python</li>
<li>Who is Guido van Rossum</li>
<li>Where does the name ‘Python’ come from</li>
<li>What is the Zen of Python</li>
<li>How to use the Python interpreter</li>
<li>How to print text and variables using <code>print</code></li>
<li>How to use strings</li>
<li>What are indexing and slicing in Python</li>
<li>What is the official Holberton Python coding style and how to check your code with <code>PEP 8</code></li>
</ul>

<h2>Requirements</h2>

<h3>Python Scripts</h3>

<ul>
<li>Allowed editors: <code>vi</code>, <code>vim</code>, <code>emacs</code></li>
<li>All your files will be interpreted/compiled on Ubuntu 14.04 LTS using <code>python3</code> (version 3.4.3)</li>
<li>All your files should end with a new line</li>
<li>The first line of all your files should be exactly <code>#!/usr/bin/python3</code></li>
<li>A <code>README.md</code> file at the root of the <code>holbertonschool-higher_level_programming</code> repo, containing a description of the repository</li>
<li>A <code>README.md</code> file, at the root of the folder of <em>this</em> project, is mandatory</li>
<li>Your code should use the <code>PEP 8</code> style (version <code>1.7.*</code>)</li>
<li>All your files must be executable</li>
<li>The length of your files will be tested using <code>wc</code></li>
</ul>

<h3>Shell Scripts</h3>

<ul>
<li>Allowed editors: <code>vi</code>, <code>vim</code>, <code>emacs</code></li>
<li>All your scripts will be tested on Ubuntu 14.04 LTS</li>
<li>All your scripts should be exactly two lines long (<code>wc -l file</code> should print 2)</li>
<li>All your files should end with a new line</li>
<li>The first line of all your files should be exactly <code>#!/bin/bash</code></li>
<li>All your files must be executable</li>
</ul>

<h3>C Scripts</h3>

<ul>
<li>Allowed editors: <code>vi</code>, <code>vim</code>, <code>emacs</code></li>
<li>All your files will be compiled on Ubuntu 14.04 LTS</li>
<li>Your programs and functions will be compiled with <code>gcc 4.8.4</code> using the flags <code>-Wall</code> <code>-Werror</code> <code>-Wextra</code> <code>and -pedantic</code></li>
<li>All your files should end with a new line</li>
<li>Your code should use the <code>Betty</code> style. It will be checked using <a href="https://github.com/holbertonschool/Betty/blob/master/betty-style.pl" title="betty-style.pl" target="_blank">betty-style.pl</a> and <a href="https://github.com/holbertonschool/Betty/blob/master/betty-doc.pl" title="betty-doc.pl" target="_blank">betty-doc.pl</a></li>
<li>You are not allowed to use global variables</li>
<li>No more than 5 functions per file</li>
<li>In the following examples, the <code>main.c</code> files are shown as examples. You can use them to test your functions, but you don’t have to push them to your repo (if you do we won’t take them into account). We will use our own <code>main.c</code> files at compilation. Our <code>main.c</code> files might be different from the one shown in the examples</li>
<li>The prototypes of all your functions should be included in your header file called <code>lists.h</code></li>
<li>Don’t forget to push your header file</li>
<li>All your header files should be include guarded</li>
</ul>

<h2>More Info</h2>

<h3>Zen</h3>

<pre><code>The Zen of Python, by Tim Peters

Beautiful is better than ugly.
Explicit is better than implicit.
Simple is better than complex.
Complex is better than complicated.
Flat is better than nested.
Sparse is better than dense.
Readability counts.
Special cases aren't special enough to break the rules.
Although practicality beats purity.
Errors should never pass silently.
Unless explicitly silenced.
In the face of ambiguity, refuse the temptation to guess.
There should be one-- and preferably only one --obvious way to do it.
Although that way may not be obvious at first unless you're Dutch.
Now is better than never.
Although never is often better than *right* now.
If the implementation is hard to explain, it's a bad idea.
If the implementation is easy to explain, it may be a good idea.
Namespaces are one honking great idea -- let's do more of those!
</code></pre>

<h3>Install PEP8</h3>

<p><code>Pycodestyle</code> is now the <a href="/rltoken/D67mmHg2X9ZI7QHlQxayyw" title="new standard of Python style code" target="_blank">new standard of Python style code</a>, but at school we will use <code>PEP8</code>, <code>version 1.7.*</code>
Don’t worry, <code>pycodestyle</code> is based on <code>pep8</code>.
The hardest part now is to install it for Python 3:</p>

<h4>Regular Ubuntu 14.04 install</h4>

<pre><code>$ sudo apt-get install python3-pep8
</code></pre>

<h4>Using Pip3</h4>

<h5>Install Pip3</h5>

<pre><code>$ sudo apt-get install python3-pip
</code></pre>

<h4>Install Pep8</h4>

<pre><code>$ pip3 install pep8
</code></pre>

<h4>Make sure you have the right version</h4>

<pre><code>$ pep8 --version
1.7
$
</code></pre>

<p>If it’s not the case, it means PEP8 is installed but not linked in your <code>PATH</code>.
You should look at these folders to find where it has been installed:</p>

<ul>
<li><code>/usr/local/lib/python3*/dist-packages/pep8.py</code></li>
<li><code>/usr/lib/python3*/dist-packages/pep8.py</code></li>
</ul>

<p>Don’t hesitate to delete <code>/usr/bin/pep8</code> and replace by one of those <code>pep8.py</code>: </p>

<ul>
<li><code>cp pep8.py /usr/bin/pep8</code></li>
<li><code>chmod u+x /usr/bin/pep8</code></li>
</ul>

<p>Finally, if you can’t make it work, please use the “container-on-demand” tool to “PEP8” your files in a pre-configured container.</p>

<p><br>
<br>
<img src="https://s3.amazonaws.com/intranet-projects-files/holbertonschool-higher-level_programming+/231/Flyingcircus_2.jpg" alt="" style=""></p>

  </article>
  
## Tests :heavy_check_mark:

* [tests](./tests): Folder of test files. Provided by Holberton School.

## Function Prototypes :floppy_disk:

Prototypes for functions written in this project:

| File                       | Prototype                             |
| -------------------------- | ------------------------------------- |
| `10-check_cycle.c`         | `int check_cycle(listint_t *list);`   |
| `102-magic_calculation.py` | `def magic_calculation(a, b):`        |


## INTRODUCTION TO FILES :closed_book::closed_book::closed_book::

0.	[**0-run**:](#0-run) Shell script that runs a Python script.The Python file name will be saved in the environment variable <code>$PYFILE</code>
1.	[**1-run_inline**:](#1-run_inline) Shell script that runs Python code.The Python code will be saved in the environment variable <code>$PYCODE</code>
2.	[**2-print.py**:](#2-printpy) Python script that prints exactly <code>"Programming is like building a multilingual puzzle</code>, followed by a new line.
3.	[**3-print_number.py**:](#3-print_numberpy) Complete this <a href="https//github.com/holbertonschool/0x00.py/blob/master/3-print_number.py" title="source code" target="_blank">source code</a> in order to print the integer stored in the variable <code>number</code>, followed by <code>Battery street</code>, followed by a new line.
4.	[**4-print_float.py**:](#4-print_floatpy) Complete the source code in order to print the float stored in the variable <code>number</code> with a precision of 2 digits.
5.	[**5-print_string.py**:](#5-print_stringpy) Complete this <a href="https//github.com/holbertonschool/0x00.py/blob/master/5-print_string.py" title="source code" target="_blank">source code</a> in order to print 3 times a string stored in the variable <code>str</code>, followed by its first 9 characters.
6.	[**6-concat.py**:](#6-concatpy) Complete this <a href="https//github.com/holbertonschool/0x00.py/blob/master/6-concat.py" title="source code" target="_blank">source code</a> to print <code>Welcome to Holberton School!</code>
7.	[**7-edges.py**:](#7-edgespy) Complete this <a href="https//github.com/holbertonschool/0x00.py/blob/master/7-edges.py" title="source code" target="_blank">source code</a>
8.	[**8-concat_edges.py**:](#8-concat_edgespy) Complete this <a href="https//github.com/holbertonschool/0x00.py/blob/master/8-concat_edges.py" title="source code" target="_blank">source code</a> to print <code>object-oriented programming with Python</code>, followed by a new line.
9.	[**9-easter_egg.py**:](#9-easter_eggpy) Python script that prints “The Zen of Python”, by TimPeters, followed by a new line.
10.	[**10-check_cycle.c, lists.h**:](#10-check_cyclec-listsh) <strong>Technical interview preparation</strong> Function in C that checks if a singly linked list has a cycle in it.Requirements
11.	[**100-write.py**:](#100-writepy) Python script that prints exactly <code>and that piece of art is useful - Dora Korpar, 2015-10-19</code>, followed by a new line.
12.	[**101-compile**:](#101-compile) Script that compiles a Python script file.The Python file name will be stored in the environment variable <code>$PYFILE</code>The output filename has to be <code>$PYFILEc</code> (ex <code>export PYFILE=my_main.py</code> =&gt; output filename <code>my_main.pyc</code>)
13.	[**102-magic_calculation.py**:](#102-magic_calculationpy) Write the Python function <code>def magic_calculation(a, b)</code> that does exactly the same as the following Python bytecode

## FILES :bookmark_tabs::bookmark_tabs::bookmark_tabs::

### 0-run

**<p>Shell script that runs a Python script.</p><p>The Python file name will be saved in the environment variable <code>$PYFILE</code></p>**

<pre><code>guillaume@ubuntu:~/py/0x00$ cat main.py 
#!/usr/bin/python3
print("Holberton School")

guillaume@ubuntu:~/py/0x00$ export PYFILE=main.py
guillaume@ubuntu:~/py/0x00$ ./0-run
Holberton School
guillaume@ubuntu:~/py/0x00$ 
</code></pre>

### 1-run_inline

**<p>Shell script that runs Python code.</p><p>The Python code will be saved in the environment variable <code>$PYCODE</code></p>**

<pre><code>guillaume@ubuntu:~/py/0x00$ export PYCODE='print("Holberton School: {}".format(88+10))'
guillaume@ubuntu:~/py/0x00$ ./1-run_inline 
Holberton School: 98
guillaume@ubuntu:~/py/0x00$ 
</code></pre>

### 2-print.py

**<p>Python script that prints exactly <code>"Programming is like building a multilingual puzzle</code>, followed by a new line.</p>**

<pre><code>guillaume@ubuntu:~/py/0x00$ ./2-print.py 
"Programming is like building a multilingual puzzle
guillaume@ubuntu:~/py/0x00$
</code></pre>

### 3-print_number.py

**<p>Complete this <a href="https//github.com/holbertonschool/0x00.py/blob/master/3-print_number.py" title="source code" target="_blank">source code</a> in order to print the integer stored in the variable <code>number</code>, followed by <code>Battery street</code>, followed by a new line.</p>**

<pre><code>guillaume@ubuntu:~/py/0x00$ ./3-print_number.py
98 Battery street
guillaume@ubuntu:~/py/0x00$ 
</code></pre>

### 4-print_float.py

**<p>Complete the source code in order to print the float stored in the variable <code>number</code> with a precision of 2 digits.</p>**

<pre><code>guillaume@ubuntu:~/py/0x00$ ./4-print_float.py
Float: 3.14
guillaume@ubuntu:~/py/0x00$ 
</code></pre>

### 5-print_string.py

**<p>Complete this <a href="https//github.com/holbertonschool/0x00.py/blob/master/5-print_string.py" title="source code" target="_blank">source code</a> in order to print 3 times a string stored in the variable <code>str</code>, followed by its first 9 characters.</p>**

<pre><code>guillaume@ubuntu:~/py/0x00$ ./5-print_string.py 
Holberton SchoolHolberton SchoolHolberton School
Holberton
guillaume@ubuntu:~/py/0x00$ 
</code></pre>

### 6-concat.py

**<p>Complete this <a href="https//github.com/holbertonschool/0x00.py/blob/master/6-concat.py" title="source code" target="_blank">source code</a> to print <code>Welcome to Holberton School!</code></p>**

<pre><code>guillaume@ubuntu:~/py/0x00$ ./6-concat.py
Welcome to Holberton School!
guillaume@ubuntu:~/py/0x00$ wc -l 6-concat.py
5 6-concat.py
guillaume@ubuntu:~/py/0x00$ 
</code></pre>

### 7-edges.py

**<p>Complete this <a href="https//github.com/holbertonschool/0x00.py/blob/master/7-edges.py" title="source code" target="_blank">source code</a></p>**

<pre><code>guillaume@ubuntu:~/py/0x00$ ./7-edges.py
First 3 letters: Hol
Last 2 letters: on
Middle word: olberto
guillaume@ubuntu:~/py/0x00$ wc -l 7-edges.py
8 7-edges.py
guillaume@ubuntu:~/py/0x00$ 
</code></pre>

### 8-concat_edges.py

**<p>Complete this <a href="https//github.com/holbertonschool/0x00.py/blob/master/8-concat_edges.py" title="source code" target="_blank">source code</a> to print <code>object-oriented programming with Python</code>, followed by a new line.</p>**

<pre><code>guillaume@ubuntu:~/py/0x00$ ./8-concat_edges.py
object-oriented programming with Python
guillaume@ubuntu:~/py/0x00$ wc -l 8-concat_edges.py
5 8-concat_edges.py
guillaume@ubuntu:~/py/0x00$ 
</code></pre>

### 9-easter_egg.py

**<p>Python script that prints “The Zen of Python”, by TimPeters, followed by a new line.</p>**

<pre><code>guillaume@ubuntu:~/py/0x00$ ./9-easter_egg.py
The Zen of Python, by Tim Peters

Beautiful is better than ugly.
Explicit is better than implicit.
Simple is better than complex.
Complex is better than complicated.
Flat is better than nested.
Sparse is better than dense.
Readability counts.
Special cases aren't special enough to break the rules.
Although practicality beats purity.
Errors should never pass silently.
Unless explicitly silenced.
In the face of ambiguity, refuse the temptation to guess.
There should be one-- and preferably only one --obvious way to do it.
Although that way may not be obvious at first unless you're Dutch.
Now is better than never.
Although never is often better than *right* now.
If the implementation is hard to explain, it's a bad idea.
If the implementation is easy to explain, it may be a good idea.
Namespaces are one honking great idea -- let's do more of those!
guillaume@ubuntu:~/py/0x00$
</code></pre>

### 10-check_cycle.c, lists.h

**<p><strong>Technical interview preparation</strong> </p><p>Function in C that checks if a singly linked list has a cycle in it.</p><p>Requirements</p>**

<pre><code>carrie@ubuntu:~/0x00$ cat lists.h
#ifndef LISTS_H
#define LISTS_H

#include &lt;stdlib.h&gt;

/**
 * struct listint_s - singly linked list
 * @n: integer
 * @next: points to the next node
 *
 * Description: singly linked list node structure
 * for Holberton project
 */
typedef struct listint_s
{
    int n;
    struct listint_s *next;
} listint_t;

size_t print_listint(const listint_t *h);
listint_t *add_nodeint(listint_t **head, const int n);
void free_listint(listint_t *head);
int check_cycle(listint_t *list);

#endif /* LISTS_H */
</code></pre>

### 100-write.py

**<p>Python script that prints exactly <code>and that piece of art is useful - Dora Korpar, 2015-10-19</code>, followed by a new line.</p>**

<pre><code>guillaume@ubuntu:~/py/0x00$ ./100-write.py
and that piece of art is useful - Dora Korpar, 2015-10-19
guillaume@ubuntu:~/py/0x00$ echo $?
1
guillaume@ubuntu:~/py/0x00$ ./100-write.py 2&gt; q
guillaume@ubuntu:~/py/0x00$ cat q
and that piece of art is useful - Dora Korpar, 2015-10-19
guillaume@ubuntu:~/py/0x00$ 
</code></pre>

### 101-compile

**<p>Script that compiles a Python script file.</p><p>The Python file name will be stored in the environment variable <code>$PYFILE</code></p><p>The output filename has to be <code>$PYFILEc</code> (ex <code>export PYFILE=my_main.py</code> =&gt; output filename <code>my_main.pyc</code>)</p>**

<pre><code>guillaume@ubuntu:~/py/0x00$ cat main.py 
#!/usr/bin/python3
print("Holberton School")

guillaume@ubuntu:~/py/0x00$ export PYFILE=main.py
guillaume@ubuntu:~/py/0x00$ ./101-compile
Compiling main.py ...
guillaume@ubuntu:~/py/0x00$ ls
101-compile  main.py  main.pyc
guillaume@ubuntu:~/py/0x00$ cat main.pyc | zgrep -c "Holberton School"
1
guillaume@ubuntu:~/py/0x00$ od -t x1 main.pyc # SYSTEM DEPENDANT =&gt; CAN BE DIFFERENT
0000000 ee 0c 0d 0a 91 26 3e 58 31 00 00 00 e3 00 00 00
0000020 00 00 00 00 00 00 00 00 00 02 00 00 00 40 00 00
0000040 00 73 0e 00 00 00 65 00 00 64 00 00 83 01 00 01
0000060 64 01 00 53 29 02 7a 10 48 6f 6c 62 65 72 74 6f
0000100 6e 20 53 63 68 6f 6f 6c 4e 29 01 da 05 70 72 69
0000120 6e 74 a9 00 72 02 00 00 00 72 02 00 00 00 fa 07
0000140 6d 61 69 6e 2e 70 79 da 08 3c 6d 6f 64 75 6c 65
0000160 3e 02 00 00 00 73 00 00 00 00
0000172
guillaume@ubuntu:~/py/0x00$ 
</code></pre>

### 102-magic_calculation.py

**<p>Write the Python function <code>def magic_calculation(a, b)</code> that does exactly the same as the following Python bytecode</p>**

<pre><code>  3           0 LOAD_CONST               1 (98)
              3 LOAD_FAST                0 (a)
              6 LOAD_FAST                1 (b)
              9 BINARY_POWER
             10 BINARY_ADD
             11 RETURN_VALUE
</code></pre>



