# Ciclo de vida dos arquivos no GIT

<p>
<img src="ciclo-de-vida-git.png"/>
</p>

- git init
  
  inicializa um novo repositório do Git.

<br>

> **Arquivo unmodified e modified**
> 
> sem modificação / modificado
> 
> **Arquivo untracked**
> 
> arquivo recém criado

<br>

- git add
  
  move o arquivo untrecked ou modified direto para o staged, dessa forma ele está se preparando para fazer parte de um commit.

<br>

- git commit
  
  cria um snapshot (foto) do código naquele momento. Depois os arquivos retornam para unmodified aguardando um novo ciclo de etapas.

<br>

- git status
  
  permite vizualizar qual o estado atual do arquivo, em etapa do ciclo ele se encontra.


