我的`.vim`文件夹

使用(从网站到新的机器)

	cd ~
复制下来

	git clone
重命名为`.vim`文件夹

	mv ~/dotvim ~/.vim
备份原来的配置文件(可选)
	
	mv ~/.vimrc ~/.vimrc.bak
	mv ~/.gvimrc ~/.gvimrc.bak
建立软连接

	ln -s ~/dotvimrc ~/.vimrc
	ln -s ~/dotgvimrc ~/.gvimrc
