Technical Standards
####################################

Languages
====================================

C++
------------------------------------------------
**Standard:** `C++14 ISO Standard <https://isocpp.org/std/the-standard>`_

**Compiler:** `GNU GCC 5 <https://gcc.gnu.org/gcc-5/changes.html>`_

**Windows Compiler:** `MSYS2 <http://msys2.github.io/>`

CSS
------------------------------------------------
**Standard:** `W3C CSS2-20110607 <http://www.w3.org/TR/2011/REC-CSS2-20110607/>`_

**Version:** CSS2

**What About CSS3?** There are many issues with early adoption for production.
Though we have transitioned to HTML5, we will continue to use CSS2 until all
W3C CSS3 standards reach RECOMMENDED status. Monitor progress
`here <http://www.w3.org/standards/techs/css>`_.

ECMAScript (Javascript)
------------------------------------------------
**Standard:** `Standard ECMA-262 <http://www.ecma-international.org/publications/standards/Ecma-262.htm>`_

Encoding
------------------------------------------------
**Standard:** `UTF-8 <http://unicode.org/resources/utf8.html>`_

HTML
------------------------------------------------
**Standard:** `W3C HTML5-20141028 <http://www.w3.org/TR/2014/REC-html5-20141028/>`_

**Version:** HTML5

Python
------------------------------------------------
**Standard:** `PEP8 <https://www.python.org/dev/peps/pep-0008/>`_

**Version:** `3.5.1 <https://www.python.org/downloads/release/python-351/>`_

**What About Python 2?** Python 2 is still important, especially for some
support targets. However, we should aim to make our code Python 2/3
cross-compatible whenever possible. PEP8 compliance will help us do that.

XML
------------------------------------------------
**Standard:** `W3C XML-20081126 (XML 1.0 5e) <http://www.w3.org/TR/2008/REC-xml-20081126/>`_

**Version:** 1.0

Libraries
================================================

+-------------------------------------------------+------------------------+---------+---------+--------------------+-----------+
| Library                                         | Use                    | Version | Binding | Package            | License   |
+=================================================+========================+=========+=========+====================+===========+
| `CPGF <http://www.cpgf.org/>`_                  | Signals, Introspection | 1.5.6   | C++     | (See website)      | Apache v2 |
+-------------------------------------------------+------------------------+---------+---------+--------------------+-----------+
| `Xerces <https://xerces.apache.org/xerces-c/>`_ | XML Parsing            | 3.1     | C++     | ``libxerces-c3.1`` | Apache v3 |
+-------------------------------------------------+------------------------+---------+---------+--------------------+-----------+
| `Kivy <https://kivy.org/>`_                     | GUI                    | 1.9     | Python2 | ``python-kivy``    | MIT       |
+-------------------------------------------------+------------------------+---------+---------+--------------------+-----------+

Operating System Support Targets
================================================

These show minimum specificaaitons for a goal.

Support Goals:

- 5: Essential
- 4: High Priority
- 3: Moderate Priority
- 2: Low Priority
- 1: Collateral Support
- 0: No Support

+-----------------------+---------+--------+
| OS                    | Memory  | Goal   |
+=======================+=========+========+
| **Microsoft Windows** |         |        |
+-----------------------+---------+--------+
| Windows 95            | 256 MB  | 2      |
+-----------------------+---------+--------+
| Windows 98            | 256 MB  | 3      |
+-----------------------+---------+--------+
| Windows 2000          | 256 MB  | 3      |
+-----------------------+---------+--------+
| Windows ME            | 256 MB  | 3      |
+-----------------------+---------+--------+
| Windows XP SP1        | 256 MB  | 4      |
+-----------------------+---------+--------+
| Windows XP SP2        | 512 MB  | 5      |
+-----------------------+---------+--------+
| Windows XP SP3        | 512 MB  | 5      |
+-----------------------+---------+--------+
| Windows Vista         | 512 MB  | 5      |
+-----------------------+---------+--------+
| Windows 7             | 1 GB    | 5      |
+-----------------------+---------+--------+
| Windows 8             | (Any)   | 0      |
+-----------------------+---------+--------+
| Windows 8.1           | (Any)   | 0      |
+-----------------------+---------+--------+
| Windows 10            | (Any)   | 0      |
+-----------------------+---------+--------+
| **Apple Mac**         |         |        |
+-----------------------+---------+--------+
| OS X 10.0-10.3 PPC    | 256 MB  | 2      |
+-----------------------+---------+--------+
| OS X 10.4 PPC         | 256 MB  | 4      |
+-----------------------+---------+--------+
| OS X 10.4 Intel       | 256 MB  | 4      |
+-----------------------+---------+--------+
| OS X 10.5             | 512 MB  | 3      |
+-----------------------+---------+--------+
| OS X 10.6             | 1 GB    | 4      |
+-----------------------+---------+--------+
| OS X 10.7-10.10       | 2 GB    | 4      |
+-----------------------+---------+--------+
| **Linux**             |         |        |
+-----------------------+---------+--------+
| Ubuntu 14.04          | 512 MB  | 5      |
+-----------------------+---------+--------+
| Ubuntu 16.04          | 512 MB  | 5      |
+-----------------------+---------+--------+
| Debian Jessie         | 512 MB  | 4      |
+-----------------------+---------+--------+
| Puppy Linux           | 256 MB  | 3      |
+-----------------------+---------+--------+
| Fedora 20             | 1 GB    | 4      |
+-----------------------+---------+--------+
| OpenSUSE 13.2         | 1 GB    | 3      |
+-----------------------+---------+--------+
| SoaS                  | 1 GB    | 3      |
+-----------------------+---------+--------+

.. NOTE::We want to get a version of OSR working on a version of Linux that
  runs entirely from a USB stick. We can target newer computers with this
  (i.e. RAM-only). The idea is to make a "bootable" version of the game for
  users who have Windows 8/8.1/10.

**For support consideration:**

- `Guadalinux <http://www.guadalinexedu.org/portal/>`_
- `Qimo4Kids <http://www.qimo4kids.com/>`_
