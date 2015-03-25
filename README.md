# PHPUnitStarter
Estrutura básica para iniciar utilizando o PHPUnit (com NetBeans)

Passos:

PHPUnit
* 1 - Acessar: https://phar.phpunit.de/phpunit-skelgen-2.0.1.phar e realizar o download de "phpunit.phar" 
* 2 - Acessar: https://phar.phpunit.de/phpunit-4.5.0.phar e realizar o download de "phpunit-skelgen.phar" 

Links de: https://phar.phpunit.de/
Caso não consiga realizar o donwload, os .phar estarão disponíveis na pasta "phar"

NetBeans (8.0)
* 1 - Ferramentas -> Plugins -> Instalar o plugin "PHPUnit" no Netbeans;
* 2 - Ferramentas -> Opções -> PHP -> Frameworks e Ferramentas -> PHPUnit;
* 2.1 - Clicar em "Procurar" no campo "Script PHPUnit" e apontar para o phpunit.phar;
* 2.2 - Clicar em "Procurar" no campo "Script do Gerador Skeleton" e apontar para o phpunit-skelgen.phar;
* 3 - Clicar com o botão direito no nome do projeto -> Propriedades
* 3.1 - Acessar a opção "Testando" e clicar em "Adicionar Pasta" para o diretório "testes"
* 3.2 - Habilitar o checkbox "PHPUnit"
* 3.3 - Acessar a opção abaixo de "Testando" -> "PHPUnit"
* 3.4 - Selecionar "Usar Bootstrap" e apontar para o "test-config" -> "bootstrap.php"
* 3.5 - Selecionar "Usar Configuração XML" e apontar para o "test-config" -> "configuration.xml"
* 3.6 - Selecionar "Executar todos os Arquivos de *Teste usando PHPUnit

* 4 - Para configurar as pastas para Autoload, acessar "bootstrap.php" na pasta "test-config" e no "AutoLoader::registerDirectory('../');" alterar para a pasta com as classes;