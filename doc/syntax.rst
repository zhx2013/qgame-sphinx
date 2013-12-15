.. highlight:: clojure

Syntax of QGAME programs
========================

Essentially, QGAME programs are Clojure programs. This is an example of a QGAME program::

	((hadamard 0)
	(measure 0)
	(hadamard 1)
	(measure 1)
	(end)
	(end)
	(end)
	(hadamard 2)
	(measure 2)
	(end)
	(end)
	(end))

Functions like ``hadamard`` and ``measure`` are quantum system operators defined in Qgame-clj.

Specially notes for Qgame-seesaw
--------------------------------

* You are supposed to put your program in a pair of outer parentheses.
* You are not allowed to use quotation marks to quote your programs as what you are expected to do in Clojure REPLs.
* Do not keep the warnings in your program.

.. NOTE::
	If your program in obviously wrong, a popup window would show up and notice you about the guidelines.


