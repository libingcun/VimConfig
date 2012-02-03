# Installation

If necessary, backup and remove your <tt>~/.vim</tt> directory and <tt>~/.vimrc</tt> file.

Clone this repository to <tt>~/.vim/</tt>

	git clone git@github.com:libingcun/vimconfig.git ~/.vim

(If you're behind a firewall that blocks port 9418, replace <tt>git:</tt> with
 <tt>https:</tt> in the above URL.)

Alternatively, if for some bizarre reason you don't have git installed, you can
download a zip or tar file using the link on
[GitHub](https://libingcun@github.com/libingcun/vimconfig.git).

Finally, symlink <tt>.vimrc</tt>:

    ln -s ~/.vim/vimrc ~/.vimrc

## Keeping up-to-date

	    cd ~/.vim
		    git pull

Then in vim:
	
	:helptags ~/.vim/doc

