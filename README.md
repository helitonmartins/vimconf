vimconf
=======

My Vim configuration.

Easy to install, explained .vimrc and usable for a wide array of tasks.  
All required files to get it up and running is included. Fonts aswell. 

The install process heavily relies upon the genius plugin manager Vundle, 
thus it is included.  
It doesn't matter if it's outdated, it'll update itself.

### Installation
To install simply download and copy all the files to your home-folder,   
alternatively symlink your ~/.vimrc to your git clone so in order to update
only a git pull is needed.  

    ln -s /dir/vimconf/.vimrc ~/.vimrc

Then open an empty file with Vim and run this to install the plugins.  
It's the same command for updating.  

    :BundleInstall

See [Vundle](https://github.com/gmarik/vundle) for more information on how 
to use it.

**Note**: This configuration uses 'fancy' glyphs for 
[Powerline](https://github.com/Lokaltog/vim-powerline) and therefore requires 
a patched font for it to work.  
Either disable this or use an appropriate font. See the docs for more 
information.

### Configuration
Use a ~/.vimrc.local for your own settings. In this way you can still easily 
update this config without  
having to maintain your personal changes. It will be sourced automatically.  
As for Gvim I'd still recommend using .vimrc.local since noexrc is enabled.

### Preview
![Preview](http://i.imgur.com/mbnEL.png "Vim screenshot")

[Writing a small perl-script using Vim](http://youtu.be/DrzAuLsxgwU)
