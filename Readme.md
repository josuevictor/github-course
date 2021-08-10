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
 

<img src="https://www.google.com/imgres?imgurl=https%3A%2F%2Ft.ctcdn.com.br%2F8FplhVkDQdAatiUcehCimgkGJlI%3D%2F512x288%2Fsmart%2Fi257652.jpeg&imgrefurl=https%3A%2F%2Fcanaltech.com.br%2Fsoftware%2FComo-salvar-imagens-mais-leves-no-Photoshop%2F&tbnid=HHsYopXn4AdwOM&vet=12ahUKEwj_xKaexqfyAhVcuJUCHW0DBQ4QMygBegUIARDKAQ..i&docid=VHtg5hOBR0FhXM&w=512&h=288&q=imagens&client=ubuntu&ved=2ahUKEwj_xKaexqfyAhVcuJUCHW0DBQ4QMygBegUIARDKAQ">


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
