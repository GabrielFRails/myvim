# myvim
Minhas configurações do VIM

" Configs Básicas
syntax on              " Ativa a colorização da sintaxe
set number             " Exibe a numeração das linhas
set autoindent         " Mantém a indentação automática
set clipboard=unnamed  " Usa o clipboard do sistema

" Configurações para tabulação
set tabstop=4       " um tab é igual a 4 espaços
set shiftwidth=4    " indentação automática usa 4 espaços
set softtabstop=4   " permite que backspace apague os espaços de uma tabulação
set expandtab       " converte tabs em espaços

" Mapeamento para desfazer tabulação (backtab)
inoremap <S-Tab> <C-d>

" Mapeamento básico para fechar automaticamente alguns symbols
inoremap ( ()<left>
inoremap { {}<left>
inoremap [ []<left>
inoremap " ""<left>
inoremap ' ''<left>
