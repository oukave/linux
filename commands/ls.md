O comando `ls` é usado para listar o conteúdo de um ou mais diretórios.

**SINTAXE**
```
ls [opção]... [diretório]...
```

**OPÇÕES ÚTEIS**

- `-1` : Lista um único item por linha.

- `-A` : Faz com que o comando `ls` também liste os itens ocultos, exceto os diretórios especiais `.` e `..`.

- `-C` : Faz com que o comando `ls` liste a saída em colunas.

- `-F` : Adiciona identificadores nos itens para difenrenciar diretórios, links simbólicos, etc.

- `-H` : Faz o comando seguir links simbólicos nos argumentos.

- `-L` : Seguir links simbólicos para listar o destino.

- `-Q` : Faz o comando `ls` encapsular os item usando aspas duplas.

- `-R` : Faz o comando `ls` listar subdiretórios recursivamente.

- `-S` : Faz o comando ordenar os item por tamanho. ( decrescente ).

- `-T` : Usa tabs na saída formatada ao invés de espaços.

- `-X` : Faz o comando `ls` ordenar os item alfabeticamente considerando primeiro as extensões.

- `-Z` : Faz o comando `ls` exibir o contexto de seguraça de cada arquivo.

- `-a` : Faz com que o comando `ls` também liste os itens ocultos, inclusive os diretórios especiais `.` e `..`.

- `-c` : Faz ordenação usando `ctime` (hora da última modifcação de metadados).

- `-d` : Faz com que o comando `ls` liste o próprio diretório indicado e não seu conteúdo.

- `-f` : Faz con que o comando `ls` liste os item na ordem em que aparecem no diretório, sem qualquer ordenação ou formatação.

- `-i` : Quando usado em conjunto com `-l` Faz o comando também exibir o inode de cada arquivo.

- `-k` : Usa tamanos em kilobytes.

- `-l` : Faz o comando `ls` listar os itens em um formato longo que possui mais detalhes.

- `-m` : Faz com que o comando `ls` liste os arquivos separando-os por vírgula.

- `-n` : É igual a opção `-l`, mas exibe UID e GID numéricos.

- `-q` : Substitui caracteres não imprimíveis por `?`.

- `-r` : Inverte a ordem de listagem.

- `-t` : Faz a ordenação considerando a data de modificação.

- `-u` : Faz a ordenação usando `atime` (hora do último acesso).

- `-w` : Define a largura das colunas da saída formatada.

- `-x` : Faz o comando `ls` listar o itens em colunas, mas usar uma ordenação na horizontal. (ordena os itens por linha).