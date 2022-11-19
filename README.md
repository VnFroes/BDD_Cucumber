### BDD_Cucumber_JUnit
### Descrição
  Este projeto tem como visão realizar cenários de testes que abrange dois testes relacionados a uma operação bancária (saque bancário) usando cucumber e JUnit como ferramenta de teste.
### Mecânicas
  O uso da classe "runner.java" do JUnit com cucumber serve para ter anotações nos testes a ser realizados. O arquivo "Conta_BDD.feature" conta com os cenários e o que é esperado deles. Já o arquivo "runner.java" executara o teste e retornara as anotações sobre o teste, o que passou ou não no teste.
  
  ### O que é esperado dos cenários
  <div align="center">
<img src="https://cdn.discordapp.com/attachments/1040755969589788675/1040764281400070174/image.png">
</div>

### O código e métodos
<div align="center">
<img src="https://cdn.discordapp.com/attachments/1040755969589788675/1043329607404879912/image.png">
</div>
  
  ### Código Runner.java
  <div align="center">
<img src="https://cdn.discordapp.com/attachments/1040755969589788675/1043329283134853140/image.png">
</div>

### Execução do Runner.java
Vale lembrar que dependendo do tipo do cliente declarado no "conta.java" na variavel booleana "cliEspecial" (caso a variavel seja TRUE sera cliente especial e FALSO sera cliente comum) o resultado do "runner.java" sera diferente dependendo disto.
### cliEspecial = true (cliente especial)
<div align="center">
<img src="https://cdn.discordapp.com/attachments/1040755969589788675/1043330086067241030/image.png">
</div>

### cliEspecial = false (cliente comum)
<div align="center">
<img src="https://cdn.discordapp.com/attachments/1040755969589788675/1043330476561154078/image.png">
</div>


### Como usar
  Baixe o projeto (crie uma pasta "disciplinaqualidade" e coloque os arquivos dentro para evitar problemas com o nome do projeto na hora de executar) e abra-o em uma IDE (recomendado Eclipse) porem antes sera necessário baixar algumas dependências (java 8, cucumber-junit plugin), após o projeto       aberto e as dependências instaladas basta executar o "Runner.java". 
### Ajuda
  Basta entrar em contato direto com o criador deste repositorio no github.
### Contribuidores (quem mantem o projeto)
  VnFroes
