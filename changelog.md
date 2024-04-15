# Changelog

All notable changes to this project will be documented in this file.

## [5.1.1] - 2024-04-15  Dmytro Okhrymenko <dmytro@mwdplanet.ca>

### Changed

   * GainControl.c (gain stages): The order of gain stages activation has been changed.


2019-06-15  Paul Eggert  <eggert@cs.ucla.edu>

	Port to platforms where tputs is in libtinfow

	* configure.ac (tputs_library): Also try tinfow, ncursesw (Bug#33977).

2019-02-08  Eli Zaretskii  <eliz@gnu.org>

	Improve documentation of 'date-to-time' and 'parse-time-string'

	* doc/lispref/os.texi (Time Parsing): Document
	'parse-time-string', and refer to it for the description of
	the argument of 'date-to-time'.

	* lisp/calendar/time-date.el (date-to-time): Refer in the doc
	string to 'parse-time-string' for more information about the
	format of the DATE argument.  (Bug#34303)
