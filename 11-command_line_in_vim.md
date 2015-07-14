# Using the command line directly from vim?!

Yup, you can!

Here's how. 

To invoke commands from within the shell:
```
:!<command>
```

Replace <command> with actual command, of course.

You can also use the output from the command line in your Vim file, you can use the read command.

```
:read !date
```

will output the date, like so:

```
Tue Jul 14 12:35:19 IST 2015
```

