# 我的Vim

![My Vim screen shot](https://raw.github.com/taberh/vim/master/vim.png)

## 安装

    $ git clone https://github.com/taberh/vim.git ~/vim
    $ mv ~/vim/.vim ~/vim/.vimrc ~/
    $ git clone https://github.com/gmarik/vundle.git ~/.vim/bundle/vundle
    $ vim +BundleInstall +qall
    $ rm -rf ~/vim

## 快捷键

    ,w  =>  :w!
    ,q  =>  :q!
    ,qq =>  :qa!

    ,ee =>  :e ~/.vimrc         // 快速编辑vimrc
    ,ss =>  :source ~/.vimrc    // 重载vimrc配置

    ,/  =>  :noh    // 取消搜索高亮

    ,t2 =>  :set shiftwidth=2   
    ,t4 =>  :set shiftwidth=4

    *   // 向上搜索当前光标所在单词  
    #   // 向下搜索当前光标所在单词

    ,tn =>  :tabnew
    ,to =>  :tabonly
    ,tc =>  :tabclose
    ,ts =>  :tab splict
    ,m  =>  :tabmove
    ,l  =>  :tabn
    ,h  =>  :tabp

    ,n  =>  :NERDTreeTabsToggle     // 切换目录浏览窗口

## 参考

* <https://github.com/easwy/share>
* <http://amix.dk/vim/vimrc.html>
* <https://github.com/gmarik/vundle>
