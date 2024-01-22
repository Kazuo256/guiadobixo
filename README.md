Guia do Bixe - Comissão de Recepção do IME-USP
==============================================

Este guia é escrito anualmente para facilitar a vida dos ingressantes no
IME-USP.

## Instalação do LaTeX

Para instalar o LaTeX, você precisará baixar os seguintes pacotes no Ubuntu:

- texlive
- texlive-latex-extra
- texlive-lang-portuguese

Para tal, digite
```bash
sudo apt-get install texlive texlive-latex-extra texlive-lang-portuguese
```
e aperte Enter, espere a Internet ser baixada para o seu computador e seja
feliz.

## Guidelines

Este guia tem o intuito de ser sustentável e de fácil manutenção entre os
anos. Assim, pedimos que sempre que contribuir, atente para as seguintes
orientações:

- Tente manter as linhas com menos de 80 caracteres
- Tente deixar a formatação do latex consistente
- Deixe uma linha vazia no começo e fim de cada seção pra facilitar a vida.
- Mantenha tudo claro e simples
- Comente qualquer coisa que fuja à regra anterior

## Ao escrever textos

Ao escrever textos, utilize uma linguagem impessoal e escreva da maneira mais
simples que você conseguir. Evite piadas muito internas e no geral, siga o 
seu bom senso.


## Coisas úteis

Sobre o latex:

- Lembre-se que pro latex, espaço, tab, newline é tudo a mesma coisa.
- Lembre-se que pro latex, uma linha vazia é igual a 20 linhas vazias.

Para procurar coisas:

```bash
grep "TODO" *.tex
```
    
No vim:

```vim
:%s/^\s\+//g  - Tira espaços em branco no começo da linha por todo o código
:%s/\s\+$//g  - Tira espaços em branco no fim da linha por todo o código
:.s/^\(.\{,79}\) \(\a\+.*\)/\1^M\2/  - Quebra a linha em aproximadamente 80 caracteres    
```

Pra escrever esse ^M, você deve apertar ctrl+v, soltar e depois apertar enter.
