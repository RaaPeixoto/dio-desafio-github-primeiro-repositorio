#  💡<u>Git</u> 📄



## ❓ O que é Git ? 

Sistema de **controle de versão **,  usado para controlar o **histórico de alterações** de arquivos.

## ❗Importantes definições

- ##### **Repositórios: **

  é um diretório onde você  **armazena** os arquivos do seu projeto(códigos, imagens, áudios, vídeos, etc). Ele pode ficar armazenado um repositório local (seu computador) ou armazenado em um repositório remoto (GitHub, BitBucket ou GitLab).
  ​

- ##### **Branches: **

  Branch significa “ramo”, ou seja, uma **ramificação do seu código.**
  Exemplo: você tem o seu código que já está funcionando em produção e precisa desenvolver uma nova funcionalidade (“feature”). Mas você não pode mexer direto no código em produção. Para isso, você cria uma ramificação do seu código, uma branch, em que você pega o estado atual daquele código e cria um novo ambiente para desenvolver a nova feature a partir dali. Dessa forma, você não altera a versão principal do seu código, consegue desenvolver sua funcionalidade com segurança, e quando esse código estiver funcionando, você poderá colocar ele na principal (ou fazer o merge, que falaremos mais adiante nesse post).

  ![GIT Branching and Merging](https://i2.wp.com/digitalvarys.com/wp-content/uploads/2019/06/image-7.png?fit=640%2C311&ssl=1)
  ​

- ##### **Commits**: 

  Um commit é um **conjunto de alterações** que você fez em um projeto. Ele marca uma versão do seu código. Um commit **guarda as alterações feitas nos arquivos**, quem fez essas alterações e uma mensagem que resume essa alteração. Além disso, cada commit tem um hash único SHA1 que pode ser usado para acompanhar todas as alterações feitas no passado e inclusive pode ser usado para **voltar em alguma alteração específica ou em algum ponto no tempo específico do seu código.**

## 🕙Estados do Repositório:

Seus arquivos sempre estão em um dos estados fundamentais: **modificado (modified), preparado** (**staged) ou consolidado (committed)**. Toda vez que um arquivo é salvo no controle de versão, ou seja, é registrado uma versão, o Git armazena algo parecido com uma imagem do arquivo que representa seu estado atual.


![img](https://miro.medium.com/max/1400/1*oX0oxuHK-SI3nW2BmdaPng.png)

