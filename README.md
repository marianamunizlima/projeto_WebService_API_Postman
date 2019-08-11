# projeto_WebService_API_Postman

Link da collection para importar: https://www.getpostman.com/collections/ea391d05c2e8071aed44

Pré requisito: Baixar os arquivos: "Avaliação - Neon.postman_collection" e "PROD SWAPI.postman_environment" em um diretório padrão

Instruções para executar via Postman:

Primeiro iremos preparar o ambiente no Postman para executar a coleção:

1 - Ter/Instalar o Postman 
3 - Abrir o Postman
4 - No menu "File", clicar em "Import"
5 - Escolher a aba "Import File" e clicar no botão "Choose Files"
6 - Selecionar o arquivo "Avaliação - Neon.postman_collection" salvo no diretório padrão e clicar em abrir
7 - Clicar no ícone de "engrenagem" (Configurações - Então você estará com a janela de "Manage Enviroments" aberta)
8 - Clicar no botão "Import", selecionar o arquivo "PROD SWAPI.postman_environment" salvo no diretório padrão e clicar em abrir (Pronto! Tudo certo!)

Depois de realizar as importações:
1 - Com o Postman aberto (Claro), clicar no botão "Runner" (Então abrirá a janela de "Collection Runner do Postman")
2 - Selecionar a coleção "Avaliação - Neon"
3 - Selecionar o enviroment "PROD SWAPI"
4 - Clicar no botão de "Run"
5 - Prontinho! Você consegue ver em tempo real as requisições acontecendo e quantos testes passaram/falharam! :)


Caso você queira executar via Newman também é bem simples:

Instruções (Execução via Newman):

1 - Ter instalado/instalar o nodejs na máquina
2 - Abrir um console (cmd; powershell, cmder, etc) e executar o comando: npm install -g newman
3 - Executar o comando: newman run <collection> --environment <diretório onde fica o environment que você deseja utilizar>\<nome do environment>.json

Exemplo: 

newman run https://www.getpostman.com/collections/ea391d05c2e8071aed44 --environment C:\Users\mariana\Desktop\Avaliação - Neon\Postman\PROD SWAPI.postman_environment.json

--> Demais informações consultar: https://learning.getpostman.com/docs/postman/collection_runs/command_line_integration_with_newman/

