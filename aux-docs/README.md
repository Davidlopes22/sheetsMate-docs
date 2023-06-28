<!--
author:   M. David Lopes

email:    mdlopes@inf.ufsm.br

version:  0.0.1

language: PT-BR

narrator: Brazilian Portuguese Female

comment:  Material de apoio para eøntendimento da ferramenta SheetsMate e testes

translation: English  translations/English.md

-->



# Testes do SheetsMate

> SheetsMate é uma ferramenta para auxiliar desenvolvedores na criação de APIs web no Google Workspace. Ao contrário de ferramentas similares, geramos código para você inspecionar e modificar, se necessário.

Este documento é um guia para o teste da ferramenta 🤯 
O teste tem 3 etapas:

  1. Assistir dois vídeos introdutórios
  2. Realizar tarefas usando a ferramenta
  3. Preencher um formulário de feedback

Estimamos que o tempo total de teste fique em torno de 15min.

> Em todas as etapas, clique -> no rodapé para continuar...


## Vídeos introdutórios


Tem dois **videos curtos** para auxiliar na sua jornada

1. Demonstração da utilização do Google Apps Script
2. Um step-by-step do uso da ferramente até a implantação (deploy) do código

> Clique -> no rodapé para continuar...

                 {{1}}
************************************************
**Uso do Google Apps Script**

<div style="position: relative; width: 100%; height: 0; padding-top: 56.2500%;
 padding-bottom: 0; box-shadow: 0 2px 8px 0 rgba(63,69,81,0.16); margin-top: 1.6em; margin-bottom: 0.9em; overflow: hidden;
 border-radius: 8px; will-change: transform;">
  <iframe loading="lazy" style="position: absolute; width: 100%; height: 100%; top: 0; left: 0; border: none; padding: 0;margin: 0;"
    src="https://www.canva.com/design/DAFmMcAMLOI/watch?embed" allowfullscreen="allowfullscreen" allow="fullscreen">
  </iframe>
</div>


************************************************



                 {{2}}
************************************************
**SheetsMate Step-by-step**

<div style="position: relative; width: 100%; height: 0; padding-top: 56.2500%;
 padding-bottom: 0; box-shadow: 0 2px 8px 0 rgba(63,69,81,0.16); margin-top: 1.6em; margin-bottom: 0.9em; overflow: hidden;
 border-radius: 8px; will-change: transform;">
  <iframe loading="lazy" style="position: absolute; width: 100%; height: 100%; top: 0; left: 0; border: none; padding: 0;margin: 0;"
    src="https://www.canva.com/design/DAFmM-5NwVA/watch?embed" allowfullscreen="allowfullscreen" allow="fullscreen">
  </iframe>
</div>


************************************************








### SOS: Infos adicionais

> Aqui você tem respostas para algumas dúvidas que podem surgir


![](https://images.unsplash.com/photo-1649565022637-feda16a124d2?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=250&q=80)




**1. O que é uma página em uma tabela?**

Uma página de uma tabela do Google Sheets é uma guia ou aba individual dentro de uma planilha do Google Sheets. Uma planilha pode conter várias páginas, cada uma delas representando uma tabela separada dentro do mesmo arquivo.

**2. Para que servem os campos requeridos?**

Campos requeridos serão úteis nos métodos de inserções e atualizações, sendo obrigatórios em inserções. Durante a atualização não podem ser atribuídos valores vazios ou nulos.

**3. Fiquei com dúvida sobre a utilização dos endpoints gerados!**

Tem um ícone de ajuda na home do SheetsMate!


## Tarefas a testar

> Agora iremos colocar a mão na massa testando o SheetsMate e as manipulações de planilhas utilizando o Google Apps Script.

**Tarefas de acesso e geração de API**

>Para evitar alguns bugs relacionados ao Google é aconselhável realizar os testes em guia anônima.
01. Faça login na conta do Google disponibilizada para o teste
02. Usando a conta Google disponibilizada, faça login na ferramenta através do seguinte link: https://davidlopes22.github.io/sheets-mate.github.io/
03. Visualize as tabelas disponibilizadas (clique no botão “Ver Tabelas”)
04. Selecione uma tabela
05. Selecione uma página/aba da tabela e clique em “Ver Colunas”
06. Selecione os campos que deseja marcar como requerido e gere o código

**Tarefas de deploy e uso de API - Utilize Postman, Insomnia ou alguma ferramenta correlata para as requisições**

07. Faça a implantação do código gerado na planilha escolhida no passo 4

08. Escolha **somente 2** das tarefas a seguir:

    - Faça um teste de inserção simples
    - Faça um teste de inserção múltipla
    - Faça um teste de deleção única
    - Faça um teste de atualização única


## Formulário de feedback

* Assim que você concluir os testes fique à vontade para responder o formulário a seguir -> https://forms.gle/QryjqHksgjk27gcX6
* Muito obrigado pela colaboração 😄 !
