# Resumo Git e GitHub

Repositório para armazenar resumos sobre Git e GitHub .

## 📚 Documentação

- [Documentação Git](https://git-scm.com/doc)
- [Documentação GitHub](https://docs.github.com/)

## 👩‍💻 Comandos

Iniciar um repositório Git:

```
git init
```

Clona um repositório existente:

```
git clone URL
git clone URL nome-desejado
```

Mostra os repositórios remotos vinculados:

```
git remote -v
```

Vincula a um repositório remoto:

```
git remote add origin URL
```

Mostra os status da árvore de trabalho:

```
git status
```

Adiciona um arquivo à área de preparação:

```
git add nomeDoArquivo
git add .
```

Commita as mudanças adicionadas:

```
git commit -m"mensagem"
```

Mostra o log das mudanças:

```
git log
```

## Desfazendo alterações

Restaura um arquivo ao último estado salvo

```
git restore nome-do-arquivo
```

Editar a mensagem do ultimo commit:

```
git commit --amend -m"Nova mensagem"
git commit --amend
```

Desfazer mudanças voltando os arquivos posteriores à área de preparação:

```
git reset --soft código-do-commit
```

Desfazer mudanças voltando os arquivos posteriores fora da área de preparação:

```
git reset --mixed código-do-commit
```

Desfazer mudanças deletando os arquivos posteriores:

```
git reset --hard código-do-commit
```

Log completo:

```
git reflog
```

Remover da área de preparação:

```
git reset caminho-do/arquivo
```

Restaurar para a área de preparação:

```
git restore --staged caminho-do/arquivo
```

puxa alterações feitas no repositório remoto para o local:

```
git pull
```

Com o atalho "." do teclado, é possível abrir o editor online para mexer em seus arquivos no Github
