 - git status - Esse comando vai listar o status dos arquivos, mostrando os que ainda não foram adicionados para o controle de versão
 - git add - Adiciona todos os arquivos não rastreados retornados pelo comando git status.
 - git add arquivo.ext - Adiciona um arquivo específico para o rastreamento.
 - git commit -m "Mensagem que identificará o commit" - Esse comando vai fazer com que os arquivos adicionados ao rastreamento através de $ git add sejam gravados no repositório. O -m utilizado serve para indicar a mensagem do commit.
  
     // Após executar esse comando, uma mensagem similar à mostrada abaixo será exibida:
                    [master (root-commit) 8666888] Arquivo inicial
                      1 file changed, 2 insertions(+)
                      create mode 100111 arquivo.ext
    // Sempre que fizer alterações em arquivos, você precisará executar um $ git add e depois um $ git commit verificando as alterações

 - git rm arquivo.ext - Esse comando remove um arquivo do repositório.
 - git mv arquivo.ext meu-arquivo.ext - O comando mv seguido do nome atual em seguida do novo nome fará essa mudança.
 - git remote add origin https://domain.com/repositorio.git - Se você estivesse usando o GitHub, por exemplo, o endereço do repositório remoto seria https://github.com/seunome/repositorio.git
 - git push - Esse comando faz o envio dos commits dados no repositório local, para o repositório remoto.