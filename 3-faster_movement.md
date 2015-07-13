# Commands for Faster Movement

We already know how to navigate the document using the h, j, k, and l keys, but what if we wanted to navigate faster?

- The ``w`` key allows you to go one word forward.
- The ``b`` key allows you to go one word backward.
- The ``W`` key allows you to go to the next string separated by a “ ”. The same goes with the ``B`` key.
- The ``^`` key takes you to the beginning of the line.
- The ``$`` key takes you to the end of the line.
- ``gg`` goes straight to the beginning of the file.
- ``G`` goes to the end of the file.
- ``{`` and ``}`` can be used to move between paragraphs at a time.
- ``f`` followed by a value will find the first occurance of that value following it in the line.
- ``F`` followed by a value will find the last occurance of that value in the line.
- ``t`` followed by a value will find the first occurance of that value following it in the line, and put the cursor one character before it.
- ``T`` followed by a value will find the last occurance of that value in the line, and will put the cursor one character before it.


## Repeater

The repeater allows for faster movement in Vim, and can be applied to most commands. You can prepend a number to a command to a vim command to specify how many times you want to run it. For example, you can use ``4w`` to go four words forward.
