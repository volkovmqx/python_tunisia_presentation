:title: Python Programming Launguage
:author: Messaoudi Lotfi
:description: Python Tunisia presents python programming language on the SFD 2014.
:keywords: presentation, restructuredtext, impress.js, tutorial
:css: tutorial.css



    .. title:: Python Tunisia


----

# whoami
========
.. image:: images/volkovmqx.jpg
.. code:: python
    
    # I am a
    print(
        "Computer Sciences Engineering Student",
        "Part-time FullStack Web Developer",
        "FOSS Jedi"
    )
    # Contact 
    email = "w@greyfox.io" 
    github = "https://github.com/volkovmqx"

----

Disclaimer
============
.. image:: images/Ghassen-Telmoudi.jpeg
.. code:: python

    ghassen.presentation.addRemote(
        "https://github.com/pyghassen/python_tunisia_presentation")

    self.presentation = ghassen.presentation.fork()
    

----

Python, do you know it?
=======================


.. image:: images/what-is-python.jpg


----

.. image:: images/python-logo-master-v3-TM.png

.. code:: python

    python_info = [
        "High level",
        "General purpose",
        "Open Source",
        "Multi-paradigm (Object Oriented and Functional)",
        "Interpreted and Interactive (REPL)",
        "Cross-platform",
        "Huge Community (Not just developers)"
    ]

.. _Python: http://www.python.org

----

.. image:: images/Guido-Van-Rossum.jpeg
.. code:: python
    
    python = {
        "who": "Python founder",
        "name": "Guido Van Rossum",
        "when": "1991",
        "where": "The Netherlands",
    }

----

.. image:: images/python-logo-master-v3-TM.png

.. code:: bash

    $ python -V
    Python 2.7.12
    $ python3 -V
    Python 3.5.2

.. code:: python

    #Python Enhancement Proposals
	python_peps = "https://www.python.org/dev/peps/"
	

.. _Python: http://www.python.org

----

Hello Python Tunisia in C
=========================

.. code:: c
    
    #include<stdio.h>

    int main() 
    {
        printf("Hello Python Tunisia!\n");
        return 0;
    }; 

    // 63 characters and 6 lines! }


----

Hello Python Tunisia in Java
============================

.. code:: java
    
    import java.io.*;
    public class Helloworld
    {
    public static void main(String[] args)
        { 
          System.out.println("Hello Python Tunisia!");
        }
    }

    // comes in at a 115 characters and a verbose 8 lines!

----
 
Hello Python Tunisia in Python
==============================

.. code:: python
    
    print("Hello World")

    # Comes in as little as 20 characters and only 1 line

----

Python philosophy
=================

.. code:: python

    >>> import this

    The Zen of Python, by Tim Peters

    Beautiful is better than ugly.
    Explicit is better than implicit.
    Simple is better than complex.
    Complex is better than complicated.
    Flat is better than nested.
    Sparse is better than dense.
    Readability counts...

----

Python Data types
=================

.. code:: python
    
    >>> _list = ["Python", "Tunisia", "on", "Google"]
    >>> _list[0]
    'Python'

    >>> tuple = (1, 2, "three")
    >>> tuple[2]
    'three'


    >>> _set = {"this","is","spartaaa"}                                                                                                           
    >>> 'spartaaa' in _set                                                                                                                          
    True
     
    >>> dictionary = {
        "date": "2016-10-19",
        "location": "ISSATSO, Tunisia, Mother Earth, Solar system"
    }
    >>> dictionary["date"]
    '2016-10-19'

    string = "yeah you guessed it, this a string"
    _int = 23
    _float = 9.99

----

Python functions
=================

.. code:: python

    def hello(name):
        """
        Says Hello.

        @name: string
        
        """
        message = "hello {}".formt(name)
        print(message)


----

Python functions
=================

.. code:: python

    def say_many_hellos(name, times=3):
        """
        Says Hello N times.

        @name: string
        @times: int

        """
        messages = ["hello {}\n".format(name) for name in range(time)]
        # Joins the list of messages and returns them as one String.
        return "".join(messages)

----

Python Class
=================

.. code:: python

    class Developper(object):
        """
        Defines a developer object.
        """
        def __init__(self, name):
            """
            @name: string
            """
            self.name = name

        def say_hello(self):
            """
            Ruturs a friendly message.

            """

            return "Hello my name is {}".format(self.name)

    if __name__ == '__main__':
        developer = Developper("Lotfi Messaoudi")
        developer.say_hello()

----

Disadvantages
============================
.. image:: images/not-sure.jpg
.. code:: python


    python_disadvantages = [
        "isn't the best for memory intensive task",
        "is interpreted language & is slow compared to C/C++ or java",
        "not a great choice for a high-graphic 3d game that takes up a lot of CPU",
    ]
    python_questions = [
        "Does adding some RAM Slots is expensive then your time ?",
        "You have the control, Jython, Cython, PyPy etc."
    ]

----

Python Tunisia
==============
.. image:: images/python_tunisia.png

----

Python and education in Tunisia
================================
.. code:: python

    print("You should learn it in school.")

----


That's all folks!
=================

.. image:: images/ancient_aliens_guy.jpg

.. code:: python

    print("Questions time !")


----


Thanks everyone !
=================

.. code:: python

    # Contact 
    email = "w@greyfox.io" 
    github = "https://github.com/volkovmqx"
    print("Thanks !")

