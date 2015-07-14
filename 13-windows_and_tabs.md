# Windows and Tabs

## Adding new windows

You can split windows horizontally and vertically. You can have as many splits as you like.

Type ``:vsplit <path of file>`` to split the window in half vertically.
Type ``hsplit <path of file>`` to split the window in half horizontally. 

# Navigating through windows

You can navigate between the windows using the ``Ctrl+w`` sequence, followed by one of the movement keys (h, j, k, l).

## Changing layout

You can change the layout of the windows after creation, too. First, navigate to the window you want to change. Then type ``Ctrl+wL`` to move it to the rightmost part of the window. To move it to the leftmost part of the window, type ``Ctrl+wJ``. Top: ``Ctrl+wK``, bottom: ``Ctrl+wH``.

You can also resize windows by using the ``Ctrl+w+`` and ``Ctrl+w-`` to increase and decrease the height of the current window respectively. To increase and decrease the width of the window, you type ``Ctrl+w>`` and ``Ctrl+w<`` respectively.

To make all the windows of equal width and height, you type ``Ctrl+w=``.

## Tabs

To open a new tab in Vim, you type ``:tabedit <file path>``.You can type ``gt`` to go forward, and ``gT`` to go backward. To close a tab, you can just type ``:q``.
