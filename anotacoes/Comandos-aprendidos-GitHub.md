
# Arquivo para adição de comandos que encontro durante aprendizagem

## Sobre comandos do Git aprendidos nas aulas da DIO.  

### Outras fontes:  
[Sparkfun](https://learn.sparkfun.com/tutorials/using-github-to-share-with-sparkfun/all)  

 - git add . : adiciona todo o conteúdo untracked do diretório para commit.
 - git add file : adiciona file ao commit.
 - git restore  file : descarta mudanças no diretório de trabalho. 
 - git ignore file : ao fazer commit, ignora arquivo file.
 - git commit -m : adiciona mensagem sobre conteúdo do commit (interessante para explicar quais modificaçãoes/exclusões foram feitas.
 - git commit -a : adiciona tudo para commit, sem mensagem.
 - git status : diz informações sobre o diretório - status de rastreamento de arquivos/pastas pelo Git, por exemplo.  
 - git remote -v : mostra repositórios cadastrados.
 - git clone endereco-de-clonagem: clona repositório no repositório local.
 - git push -u origin master - empuxa mudanças na branch master para 'remote location origin'.
 - git push origin main : empurra mudanças que foram 'commit' para main branch da origem do arquivo/pasta.
 - git restore --staged file : retorna arquivo para status de unstaged.
 - git pull origin main : puxa qualquer mudança no repositório GitHub e traz para o repositório local (útil para não ter problemas com merge
 - touch README.md - cria arquivo README com formato .md  Markdown.  

## Sobre comandos úteis para mexer com endereço de pasta, conteúdo de pastas, etc.  

 - ls : mostra conteúdo do diretório atual.
 - ls -a : mostra conteúdo do diretório atual, inclusive pastas ocultas - do sistema.
 - mv file ./destino/ : move pasta/arquivo do lugar atual para destino/.
 - mv file ../ : move arquivo para pasta anterior.
