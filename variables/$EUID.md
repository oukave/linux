A variável `$EUID` (Effective User ID) armazena o ID do usuário efetivo que executa o processo atual. Por exemplo, ao executar um script com `sudo`, o **usuário real** continua sendo quem iniciou o comando, mas o **usuário efetivo** passa a ser **root**, herdando seus privilégios.

Essa variável é útil para verificar permissões dentro de scripts e determinar se um comando está sendo executado como root ou como um usuário comum.

Faça o teste!

Crie um script shell com o seguinte conteúdo:
```shell
#!/bin/bash

echo $EUID
```

Torne o script executável e execute-o sem o `sudo`. Em seguida execute-o novamente, mas dessa vez com `sudo` e compare os resultados.

Cada usuário no Linux possui um **UID** (User ID) numérico e o usuário root **sempre** terá um UID igual a zero.

A variável `$EUID` mostra o ID efetivo, que pode ser diferente do UID real `$UID` se um script estiver rodando com permissões elevadas via `sudo` ou com o bit **setuid** ativado.

O **bit SetUID** (Set User ID) é uma permissão especial em arquivos executáveis que permite que um usuário execute o arquivo com os privilégios do dono do arquivo, em vez dos seus próprios.