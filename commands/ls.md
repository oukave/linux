O comando `ls` é usado para listar o conteúdo de um ou mais diretórios.

**SINTAXE**
```
ls [opção]... [diretório]...
```

**OPÇÕES ÚTEIS**

- `-1` : Lista um único item por linha.

- `-A` : Faz com que o comando `ls` também liste os itens ocultos, exceto os diretórios especiais `.` e `..`.

- `-a` : Faz com que o comando `ls` também liste os itens ocultos, inclusive os diretórios especiais `.` e `..`.

 - `-b` : Faz com que o comando `ls` escape caracteres não gráficos como o espaço em branco.

- `-B` : Faz com que o comando `ls` ignore arquivos de backup terminados com `~`.

- `-c` : Faz ordenação usando `ctime` (hora da última modifcação de metadados).

- `-C` : Faz com que o comando `ls` liste os itens em colunas.

- `--color[=WHEN]` : Controla se o comando `ls` deve usar cores na saída ou não, `WHEN` deve ser subtituido por `auto`, `never` ou `always`.

- `-d` : Faz com que o comando `ls` liste o próprio diretório indicado e não seu conteúdo.

- `-f` : Faz con que o comando `ls` liste os item na ordem em que aparecem no diretório, sem qualquer ordenação ou formatação.

- `-F` : Adiciona identificadores nos itens para difenrenciar diretórios, links simbólicos, executáveis, etc.

- `--group-directories-first` : Faz com que o comando `ls` liste os diretórios antes dos arquivos.

- `-h` : Faz com que o comando `ls`  liste o tamanho dos itens em um formato mais amigável para entender. Exemplo:  1K, 40M, 2G, etc.

- `-H` : Faz o comando seguir links simbólicos nos argumentos. ( ainda não usei  então não entendi o funcionamento muito bem )

- `-i` : Quando usado em conjunto com `-l` Faz o comando também exibir o inode de cada item.

- `-l` : Faz o comando `ls` listar os itens em um formato longo que possui mais detalhes.

- `-L` : Faz com que o comando `ls` siga symlinks e exiba as informações do arquivo original ao invés de exibir as informações do symlink.

- `-m` : Faz com que o comando `ls` liste os arquivos separando-os por vírgula.

- `-n` : É igual a opção `-l`, mas exibe UID e GID numéricos.

- `-N` : Faz com que o comando `ls` exiba os nomes de arquivos que contém espaços de forma literal sem aspas.

- `-p` : Adiciona uma barra ( / ) ao final do nome de diretórios para diferenciá-los.

- `-q` : Substitui caracteres não imprimíveis por `?`.

- `-Q` : Faz o comando `ls` encapsular os item usando aspas duplas.

- `-r` : Inverte a ordem de listagem.

- `-R` : Faz o comando `ls` listar subdiretórios recursivamente.

- `-S` : Faz com que o comando `ls` ordene os itens por tamanho. ( ordem decrescente )

- `--sort=WORD` : Faz o comando `ls` ordenar os itens por uma WORD específica. Os valores possíveis são:
	- `none`
	- `size`
	- `time`
	- `extension`
	- `version`
	- `width`

- `-t` : Faz a ordenação considerando a data de modificação.

- `-T` : Usa tabs na saída formatada ao invés de espaços.

- `-u` : Faz a ordenação usando `atime` (hora do último acesso).

- `-U`: Sem ordenação, exibe os itens na ordem em que aparecem no diretório.

- `-w` : Define a largura das colunas da saída formatada.

- `-x` : Faz o comando `ls` listar o itens em colunas, mas usar uma ordenação na horizontal. (ordena os itens por linha).

- `-X` : Faz o comando `ls` ordenar os item alfabeticamente considerando primeiro as extensões.

- `-Z` : Faz o comando `ls` exibir o contexto de seguraça de cada arquivo.





