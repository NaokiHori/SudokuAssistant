##################################################################
`Sudoku Assistant <https://naokihori.github.io/SudokuAssistant/>`_
##################################################################

|License|_ |LastCommit|_ |DEPLOYMENT|_

.. |License| image:: https://img.shields.io/github/license/NaokiHori/SudokuAssistant
.. _License: https://opensource.org/license/MIT

.. |LastCommit| image:: https://img.shields.io/github/last-commit/NaokiHori/SudokuAssistant/main
.. _LastCommit: https://github.com/NaokiHori/SudokuAssistant/commits/main

.. |DEPLOYMENT| image:: https://github.com/NaokiHori/SudokuAssistant/actions/workflows/deployment.yml/badge.svg?branch=main
.. _DEPLOYMENT: https://github.com/NaokiHori/SudokuAssistant/actions/workflows/deployment.yml

**********
Motivation
**********

This library is developed

* to bring the Sudoku books I have onto my laptop and solve them more comfortably,

* to experience a simple web development using HTML, CSS, and Java (Type) Script,

* just for fun.

*****
Usage
*****

Visit `the main page <https://naokihori.github.io/SudokuAssistant/>`_.

.. list-table::
   :header-rows: 1

   * - Trigger
     - Event
   * - E / Edit
     - Reset board and change to edit mode (to configure board)
   * - N / Normal
     - Change to normal mode (to assign numbers)
   * - M / Memo
     - Change to memo mode (to assign memos)
   * - 0, Backspace, Space
     - Remove numbers under cursor
   * - 1-9
     - Input numbers under cursor or highlight numbers
   * - Arrow keys (keyboard only)
     - Move selected cell

Bluish colors are used to highlight the selected values, while reddish colors indicate that the value is the only candidate of the cell.

