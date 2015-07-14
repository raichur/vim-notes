# Macros

A macro is a special feature in Vim that allows you to store a command pipeline. Simply put, you initiate a macro recording, then you type all the commands you wish, and then finish the macro. You can then repeat that macro later as many times as you want.

To start recording, press ``q``. Then you need to register your macro (define the name by which you want to call it later), like ``a``.

To strip off the HTML tags from a long list of items like this:
``
<option value="AL">Albania</option> 
``

Delete everything from the cursor to the next ``>`` tag:
```
df>
```

Now we need to navigate to the next open tag:

```
f<
```

Now we can delete everything from the cursor to the end of the line:

```
d$
```

Then we can go to the next line:

```
j0
```

To repeat this macro, we can type ``@`` followed by what you registered it as (in my case ``a``).

We can specify how many times we want to run it as usual, like ``500@a`` to run it 500 times.

_OMG HOW AWESOME!_
