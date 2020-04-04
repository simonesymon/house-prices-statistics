# Analíse de regressão de preços das casas

Segue os comandos para utilizarmos o git no trabalho.

## 1. Importar o repositório

Para importar o repositório utilizar o seguinte comando:

```console
foo@bar:~$ git clone https://github.com/luiguip/house-prices-statistics.git
```

Para facilitar a comunicação e o trabalho em conjunto proponho cada um utilizar um notebook para fazermos uma análise inicial das variáveis e a limpeza delas.
Se todos utilizarem a mesma branch pode gerar conflitos então o ideal é utilizarmos cada um uma branch, e eu fico responsável de fazer o merge delas onde a master vai ser a branch com trabalho de todos.

Depois de importar selecionar a branch a ser utilizada.

```console
foo@bar:~$ git checkout -b <nome-da-branch>
```

Uma vez por dia vamos atualizar a branch master, para adicionar as mudanças ao commit.

```console
foo@bar:~$ git add <nome-do-arquivo>
```

Depois de adiconar os arquivos reaizar o commit.

```console
foo@bar:~$ git commit -m "Mensagem de descrição das mudanças"
```

Depois de realizar o commit suba sua branch ao github.

```console
foo@bar:~$ git push origin <nome-da-branch> 
```
