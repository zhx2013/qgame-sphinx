Introduction to QGAME
=====================

**QGAME** is a *Quantum Gate and Measurement Emulator*.

The Common Lisp version
-----------------------

`The Common Lisp version of QGAME`_ is created by `Lee Spector`_. It is no longer in maintainance as the whole **ci_lab** has moved to *Clojure*. Due to the death of *Mac Common Lisp*, its GUI is totally died and no one can open it.

The Clojure version
-------------------

Thus, we made a Clojure_ version of **QGAME** as a course project.

Structure of QGAME-clj
^^^^^^^^^^^^^^^^^^^^^^

The current version of Qgame-clj is constructed with 2 components:

qgame_
	An API which provides Clojure functions to manipulate quantum gates and to run QGAME programs.
qgame-seesaw_
	A GUI frontend based on Seesaw_.

.. These are the links
.. _Lee Spector: http://faculty.hampshire.edu/lspector/
.. _The Common Lisp version of QGAME: http://faculty.hampshire.edu/lspector/qgame.html
.. _Clojure: http://clojure.org/
.. _qgame: https://github.com/omriBernstein/qgame
.. _qgame-seesaw: https://github.com/zhx2013/qgame-seesaw
.. _Seesaw: http://daveray.github.io/seesaw/
