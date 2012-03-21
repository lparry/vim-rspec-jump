vim-rspec-jump
==============
whack something similar to this in your ~/.vimrc to jump from spec to code and
vice-versa with <Leader>j

````vim
map <Leader>j :vs <C-R>=SpecOrCodeToggle() <CR> <CR>
````
