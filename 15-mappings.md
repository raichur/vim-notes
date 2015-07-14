# Mappings

Key mapping in Vim refers to creating a shortcut for a sequence of keys or commands. To create a map, type ``:map <shortcut> <command>``. That's it.

For example, here is how you can map ``,rs`` to run ``:!bundle exec rspec<CR>``:
```
:map ,rs :!bundle exec rspec<CR>
```

``<CR>`` means enter.
