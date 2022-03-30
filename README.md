# Vim-TODO-Highlighter

This project was written to make my TODO lists easier to read by adding color coding.

The coloring is dependent on the type of bullet used to prefix a task.

\- This results in WHITE text \
\> This results in YELLOW text \
\>> This results in ORANGE text \
\>>> This results in RED text \
\>>>> This results in RED text with a WHITE background \

To use this project add ftdetect/todo.vim to the corresponding ftdetect directory on your computer and add syntax/todo.vim to the corresponding syntax directory on your computer. \
I use Neovim so these directories are located at ~/.config/nvim/ftdetect and ~/.config/nvim/syntax \
syntax/todo.vim is what defines the syntax highlighting. \
ftdetect/todo.vim will automatically set the syntax for any file with a .todo extension. \

Once you have added the files in to correct places, create a text file with a .todo extension and open it in Vim. \
If done correctly the syntax highlighting should be turned on and ready to go! \
