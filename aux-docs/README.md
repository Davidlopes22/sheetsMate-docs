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

> Este documento serve para trazer algumas informações para auxiliar no entendimento e uso da ferramenta 🤯 

- Tem dois videos para auxiliar na sua jornada

  - Demonstração da utilização do Google Apps Script
  - Um step-by-step do uso da ferramente até a implantação do código

- Roteiro de tarefas para facilitar a progressão dentro da aplicação
- Caso tenha mais alguma dúvida sobre a utilização dos endpoints gerado, tem um icone de ajuda na home do SheetsMate!





## Uso do Google Apps Script

<div style="position: relative; width: 100%; height: 0; padding-top: 56.2500%;
 padding-bottom: 0; box-shadow: 0 2px 8px 0 rgba(63,69,81,0.16); margin-top: 1.6em; margin-bottom: 0.9em; overflow: hidden;
 border-radius: 8px; will-change: transform;">
  <iframe loading="lazy" style="position: absolute; width: 100%; height: 100%; top: 0; left: 0; border: none; padding: 0;margin: 0;"
    src="https://www.canva.com/design/DAFmMcAMLOI/watch?embed" allowfullscreen="allowfullscreen" allow="fullscreen">
  </iframe>
</div>


## SheetsMate Step-by-step

<div style="position: relative; width: 100%; height: 0; padding-top: 56.2500%;
 padding-bottom: 0; box-shadow: 0 2px 8px 0 rgba(63,69,81,0.16); margin-top: 1.6em; margin-bottom: 0.9em; overflow: hidden;
 border-radius: 8px; will-change: transform;">
  <iframe loading="lazy" style="position: absolute; width: 100%; height: 100%; top: 0; left: 0; border: none; padding: 0;margin: 0;"
    src="https://www.canva.com/design/DAFmM-5NwVA/watch?embed" allowfullscreen="allowfullscreen" allow="fullscreen">
  </iframe>
</div>

### Algumas infos adicionais
>O que seria uma página em uma tabela? Qual a utilidade dos campos requeridos no código gerado pelo SheetsMate? Aqui você tem as respostas
![](https://images.unsplash.com/photo-1649565022637-feda16a124d2?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=819&q=80)



#### O que é uma página em uma tabela?

>Uma página de uma tabela do Google Sheets é uma guia ou aba individual dentro de uma planilha do Google Sheets. Uma planilha pode conter várias páginas, cada uma delas representando uma tabela separada dentro do mesmo arquivo.

#### Para o que servem os campos requeridos?
>Campos requeridos serão úteis nos métodos de inserções e atualizações, sendo obrigatórios em inserções. Durante a atualização não podem ser atribuídos valores vazios ou nulos.

## Roteiro para auxiliar nos testes

- Agora iremos colocar a mão na massa testando o SheetsMate e as manipulações de planilhas utilizando o Google Apps Script.

* OBS:Escolha 2 passos nos testes de manipulação dos dados através do endpoint gerado(Passos 9, 10, 11 e 12)
>
01. Faça o login na conta do google disponibilizada para o teste
02. Realizar Login na ferramenta através do seguinte link utilizando a conta disponibilizada: https://davidlopes22.github.io/sheets-mate.github.io/
03. Veja as tabelas relacionadas
04. Para isso clique no botão “Ver Tabelas”
05. Selecione uma tabela
06. Selecione a página da tabela e clique em “Ver Colunas”
07. Selecione os campos que deseja marcar como requerido e gere o Código
08. Faça a implantação do código gerado na planilha escolhida no passo 4
09. Faça um teste de inserção simples
10. Faça um teste de inserção múltipla
11. Faça um teste de deleção única
12. Faça um teste de Atualização única
>
* Assim que você concluir os testes fique à vontade para responder o formulário a seguir -> https://forms.gle/QryjqHksgjk27gcX6
* Muito obrigado pela colaboração 😄 !