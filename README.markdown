## History
snipMate.vim aims to be an unobtrusive, concise vim script that implements some of TextMate's snippets features in Vim. A snippet is a piece of often-typed text that you can insert into your document using a trigger word followed by a <tab>. 

The original plugin is developed by [Michael Sanders(http://github.com/msanders/))] 

=======
## Snipmate

This is a fork of msanders snipmate. I have modified it so that the original snippets do not collide with the larger snipmate repository (see below).

## Installation
Quickly install with:

    git clone https://spf13@github.com/spf13/snipmate.vim.git
	cd snipmate.vim
	cp -R * ~/.vim

## Snippets
You are going to want to pull in my snipmate-snippets repository.
(or even better, fork it and use your own)

	git clone git://github.com/spf13/snipmate-snippets.git
	ln -s /path/to/snipmate-snippets ~/.vim/snippets
