# Replace

The ``:s`` command, or substitute, is used to replace characters in Vim. ``:s/abc/xyz`` to replace ``abc`` with ``xyz`` on the line the cursor is on. 
To replace instances of ``abc`` in the whole file, we can use ``:s%/abc/xyz``. This will still only replace the next first instance of ``abc``. ``:s%/abc/xyz/g`` will replace all of ``abc``'s occurances.
