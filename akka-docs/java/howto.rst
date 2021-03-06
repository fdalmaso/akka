
.. _howto-java:

######################
HowTo: Common Patterns
######################

This section lists common actor patterns which have been found to be useful,
elegant or instructive. Anything is welcome, example topics being message
routing strategies, supervision patterns, restart handling, etc. As a special
bonus, additions to this section are marked with the contributor’s name, and it
would be nice if every Akka user who finds a recurring pattern in his or her
code could share it for the profit of all. Where applicable it might also make
sense to add to the ``akka.pattern`` package for creating an `OTP-like library
<http://www.erlang.org/doc/man_index.html>`_.

You might find some of the patterns described in the Scala chapter of 
:ref:`howto-scala` useful even though the example code is written in Scala.

Template Pattern
================

*Contributed by: N. N.*

This is an especially nice pattern, since it does even come with some empty example code:

.. includecode:: code/docs/pattern/JavaTemplate.java
   :include: all-of-it
   :exclude: uninteresting-stuff

.. note::

   Spread the word: this is the easiest way to get famous!

Please keep this pattern at the end of this file.

