# Portal da Transparência do Estado de Minas Gerais

Esse repositório visa armazenar o conteúdo estático do [Portal da Transparência](http://www.transparencia.mg.gov.br/) e controlar seu fluxo editorial.

O commit inicial de alguma página deve ser realizado com o status atual do html retirado do Joomla na opção `Editor de Código Fonte` e convertido para markdown por meio do comando

```
pandoc --wrap=none --from html content/perguntas-frequentes/index.html --to markdown --output content/perguntas-frequentes/index.md
```

O segundo commit deve apresentar as revisões manuais para adequação do arquivo, e, do terceiro em diante, as alterações podem ser sugeridas.