# neoVim-nvChad

#### Introduction
Hello guys this my config(I collected it from peoples).
in this md file i will tell you how to achiece a simple yet extraordinary ide like features in your neovim 
## 
If you don't know what is neovim i will tell you that.
#### What is vim ??
Vim is a text editor for Unix that comes with Linux, and macOS. It is known to be fast and powerful, partly because it is a small program that can run in a terminal .
So if you run nvim in your preffered termianl i use zsh but you are using linux which is a fresh installation you will be using bash.
##
#### This is what Terminal Looks like when you run nvim command in your pc
![](Assets/Screenshot_05-Jun_23-09-49_16382.png)

#### Some basic command i will tell you to make your Neovim journey less painful.
There are modes which will be using so when we press "i" in our keyboard it will go in insert mode if you are in insert mode and you want to go to normal 
mode then you will press "Esc" to escape out of insert mode .
to quit neovim just press :q in normal mode in neovim .
to write something in that file :w in normal mode i neovim .

# NvChad
This is the thing which we will be using to modify our normal neovim user interface .
#### How to achieve this ??
you just simple need to run a command before that we will be creating a backup if you have any previous configurating for your neovim
`mv ~/.config/nvim ~/.config/nvimBackup
rm -rf ~/.local/share/nvim`
Now the main command we need to run
`git clone -b v2.0 https://github.com/NvChad/NvChad ~/.config/nvim --depth 1`
