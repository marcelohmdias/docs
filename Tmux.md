# Tmux

> `C-a` Equivalente as teclas Ctrl + a

## Alias

* `ts`- `tmux new-session -s` = Cria uma nova seção nomeada;
* `ta`- `tmux attach -t` = Vincula a janela a uma seção nomeada existente;
* `tl`- `tmux list-sessions` = Lista as seções existentes;
* `tksv` - `tmux kill-server` = Mata todas as seções;
* `tkss` - `tmux kill-session -t` = Mata uma seção nomeada especiíca;

## Comandos do Tmux

### Utilitário

* `C-a :` = Permite digitar comandos;
* `C-a ?` = Exibe os comandos existentes;
* `C-a I` = Instala novos plugins;
* `C-a U` = Atualiza os plugins existentes;
* `C-a r` = Recarega o Tmux;

### Seção

* `C-a $` = Renomeia uma seção;
* `C-a d` = Sai da seção atual (mantem ativa);
* `C-a s` = Lista todas as seções;

### Janelas

* `C-a n` = Cria uma nova janela;
* `C-a ,` = Renomeia uma janela;
* `C-a &` = Exclui uma janela;
* `C-a [1-9]` = Navega entre janelas;
* `C-a w` = Lista todas as janelas;
* `C-a f` = Busca uma janela pelo número;

### Paineis

* `C-a -` = Divide o painel horizontalmente ;
* `C-a |` = Divide o painel verticalmente;
* `C-a x` = Exclui um painel;
* `C-a SETA` = Navega entre os paineis;
* `C-a }` = Move o painel para a direita;
* `C-a {` = Move o painel para a esquerda;
* `C-a !` = Converte um painel em uma janela;
* `C-a z` = Habilita o zoom em um painel;
* `C-a q` = Exibe o número dos paineis;
* `C-a ctrl SETA` = Aumeta ou diminui o tamanho de um painel;

### Modo Cópia

* `C-a [` = Entra no modo cópia;
* `q` = Sai do modo cópia;
* `SPACEBAR` = Inicia a seleção;
* `ESC` = Cancela a seleção;
* `ENTER` = Confirma a seleção;
* `C-a ]` = Cola o que está na área de seleção;