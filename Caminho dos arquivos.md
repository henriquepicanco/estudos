# Caminho dos arquivos

É o endereço de um arquivo dentro do sistema operacional e existem **caminhos absolutos** e **caminhos relativos**.

## Caminhos absolutos

```cmd
C:\Users\User\Documents\projeto\index.html
```

Este é relativo a raíz do sistema (no Windows, geralmente ao **`C:\`** e no Linux e MacOS relativo a **`/`**).

Por conta de ter variáveis que podem mudar de um computador para o outro (como, por exemplo, o nome de usuário do utilizador no caminho, caso haja),  é **pouco utilizado na programação**.

## Caminhos relativos

```bash
~/projetos/index.html
```

É relativo a pasta atual onde estamos trabalhando. É mais usado na programação, principalmente no desenvolvimento *web*.

```text
projeto/
projeto/index.html
projeto/sobre.html
projeto/contato.html
projeto/404.html
projeto/outros/
projeto/outros/equipe.html
projeto/outros/copyright.html
```

Existem dois modos de usar caminhos relativos em páginas da internet: quando no mesmo nível (no exemplo, **index.html** e **sobre.html**), podemos indicar como `./sobre.html`. Quando numa pasta acima (no exemplo, querendo linkar **contato.html** dentro de **outros/equipe.html**), usamos ==dois pontos== `../contato.html`, para indicar que o arquivo está uma pasta **acima** da pasta atual. Caso fosse necessário, podemos continuar encadeando este elemento até chegar aonde é necessário, como `../../../exemplo.html`.

#HTML #Sistemas