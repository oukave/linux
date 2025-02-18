O comando `alias` é usado para exibir ou definir "aliases". Em outras palavras, ele é usado para criar "abreviações", apelidos para comandos complexos.

**SINTAXE**
```
alias [-p] [ name[=value] ...]
```

**OPÇÕES**

- `-p` :  Faz o comando exibir os aliases no formato ( `alias name=value` ). Alguns shells já exibem os aliases nesse formato, o que torna essa opção redundante.

**EXEMPLOS DE USO**

Usar apenas `alias` exibe todos os aliases existentes no shell atual.

```shell
alias
```

Usar apenas `alias -p`  exibe todos os aliases existentes no shell atual no formato 
`alias name=value`.

```shell
alias -p
```

Usar apenas `alias name` exibe apenas o alias especificado. ( se existir )

```shell
alias ll
```

Usar `alias name=value` cria um alias para o comando passado como value.

```shell
alias ll='ls -lAp --color=auto'
```

O comando `alias` também permite criar vários aliases ao mesmo tempo e também exibir.

```shell
alias la='ls -Ap --color=auto' l='ls -CF' ll
```
