# euIfood


Cenários de testes escritos em BDD utilizando cucumber,
Utilizei a abordagem page object para o melhor reaproveitamento do código, e manutenção das features, 
 Utilizei o Framework Appium com a linguagem Ruby, usei Ruby por ser uma linguagem não compilada, um código mais limpo
Porem  tenho conhecimentos em Java, e Phyton
Utilizei o emulador do Android

para executar em outra maquina, é necessários alterar o capabilities (appium.txt) informando localização do apk



Abrir o Cmd (Em modo administrador) e executar os seguintes comandos:

gem install bundler Acessar a pasta raiz do projeto e executar o comando:

bundle install (Este comando instala todas as gems e dependências do Ruby) Execução:

Executar comandos por tag (Via cmd, na raiz do projeto):

cucumber -t ("@Aluno) 

cucumber -t ("@Login) 
