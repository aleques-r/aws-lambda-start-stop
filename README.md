# Como desligar e ligar instâncias da AWS usando a URL de Função Lambda



### Introdução:

- Durante algumas das minhas pesquisas me deparei com a seguinte duvida: como eu poderia utilizar funções lambda da AWS para ligar e desligar instâncias? Seria possível passar também nessa mesma URL os parâmetros da minha instância? Felizmente a resposta da minha dúvida se mostrou positiva, como irei demonstrar a seguir.

### Passo a Passo:

- #### Criar a função Lambda:

  - Logado no console da AWS, acessa a pagina Lambda e clique em *Criar função*;
  - Defina um nome para a função, selecione o python 3.8, mantenha a arquitetura x86_64;
  - Em permissões marque *Criar uma função com permissão básicas do Lambda*;
  - Em Configurações avançadas marque *Habilite URL da função*;
  - Clique em *Criar função*;

- 
