
let mapleader=','
" 在插入模式中用jj 代替Esc 
inoremap jj <Esc>
" \ 开启鼠标模式
nmap \ <Esc>:set mouse=a<cr>
" - 关闭鼠标模式
nmap - <Esc>:set mouse=<cr>
" 持久化语法高亮
syntax on

" vim插件  先安装vim-plug  地址 https://github.com/junegunn/vim-plug
" 在vim中使用 :PlugInstall 安装
" - For Neovim: ~/.local/share/nvim/plugged
" - Avoid using standard Vim directory names like 'plugin'
call plug#begin('~/.vim/plugged')

Plug 'mhinz/vim-startify'
Plug 'scrooloose/nerdtree'
Plug 'kien/ctrlp.vim'
" Initialize plugin system
call plug#end()

nnoremap <leader>v :NERDTreeFind<cr>
nnoremap <leader>g :NERDTreeToggle<cr>
let NERDTreeShowHidden=1
let NERDTreeIgnore = [
	\ '\.git$', '\.hg$', '\.svn$', '\.stversions$', '\.svn$', '\.swp$',
	\]
let g:ctrlp_map = '<c-p>'
