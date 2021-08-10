# Aprendendo git e github


# File status Lifecycle

## untracked 
    Momento em que o arquivo é adcionado, mas não ficou visível para o git.

## unmodified
    Passa a existir no git, porém nao passou por nenhuma modificação.

## modified
    Arquivo modificado.

## staged
    Área onde será criada a versão.
    Após o commit volta para unmodified

<img src="/Development/courses/git-course/pic/lifecycle.png"  title="lifecycle" width="150" height="100" />


# Visualizando logs

    git log

    git log --decorate

    git log --author="nome"

    git shortlog 

    git shortlog -sn (quantidade de commits/pessoa)

    git log --graph(forma gráfica o que está acontedendo com os branches e versões)

    git show + hash


# visualizando o diff
    
    git diff ultimas alterações 

    git diff --name-only (lista de arquivos modificados)


# Dersafzendo alterações 
