# Pathogen

## Install Pathogen

You can easily install vim by typing the two following commands in the terminal:

```
mkdir -p ~/.vim/autoload ~/.vim/bundle && \
curl -LSso ~/.vim/autoload/pathogen.vim https://tpo.pe/pathogen.vim
```

Next, open your ``.vimrc`` and add this line ``execute pathogen#infect()``.

Now ``cd`` into ``~/.vim/bundle/``. ``ls`` to view your plugins if you want.
