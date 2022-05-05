# Commit usando linhas de comando
* O primeiro passo é instalar o [Git](https://git-scm.com/downloads). Escolha a versão do seu Sitema Operacional e faça o download. A instalação não tem detalhes importantes, podendo apenas ir avançando até o final. 

* Feito isso, precisamos configurar o Git Bash, e de acordo com sua [documentação](https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup), basta utilizar os comandos: 
</br>
```$ git config --global user.name "seuNomeGithub" ```
</br>
```$ git config --global user.email seuEmailGitHub@examplo.com```

   Nenhuma mensagem de confirmação irá aparecer. Para ver o que ficou salvo, digite:
</br>
```$ git config --global user.name ```
</br>
```$ git config --global user.email```

* Agora precisamos acessar a pasta (diretório) onde estão os arquivos que você deseja comittar. Para acessar um diretório, utilize o comando: </br>
```$ cd nomeDoDiretorio```
</br>
</br>
    > No exemplo abaixo, estou acessando a pasta "github", que está dentro de "estudos" que está no meu hd L:

    > ![Oi](cdBash.png)

    > Dica: caso queira voltar para a pasta a anterior, use o comando: ```cd ..```

* Quando utilizarmos o comando:
  </br>
```$ git init```
  
  
   Iremos criar um repositório do Git na pasta do seu projeto, com todas as configurações que ele irá precisar para funcionar. Caso queira visualizar o repositório, basta habilitar a opção "exibir itens ocultos" do seu explorador, mas **não altere nada nele.**

* Criado o repositório .git, precisamos identificar quais arquivos iremos enviar para o seu repositório lá no servidor do Github. Nessa etapa, os arquivos ficarão em "stage". Adicionar algo ao stage no git permite que você continue fazendo modificações no seu diretório de trabalho e, quando decidir que quer interagir com o controle de versão, permite que guarde as mudanças em pequenos commits.Utilize o comando: 
</br>

    ```$ git add nomeDoArquivo.extensao ``` - *para add 1 arquivo por vez.*
</br>

    ou
</br>

    ``` $ git add * ``` -  *para add todos os arquivos do diretório.*

  
