## Histórico de Versões

| Data       | Versão | Descrição                                | Autores          | Revisor          |
| ---------- | ------ | ---------------------------------------- | ---------------- | ---------------- |
| 20/03/2021 | 0.1    | Criação da Página                        |   Pedro Haick    | ---------------- |
| 20/03/2021 | 0.2    | Adição dos cenários 1 a 3                |   Pedro Haick    | ---------------- |

## Introdução

<p align="justify">São exemplos reais da utilização de um sistema, incluindo um detalhamento da situação inicial, do fluxo esperado dos eventos e das possíveis exceções, além de informações sobre eventos simultâneos e descrição do estado ao final do cenário.</p>

## Cenário 1

|  Título  | Cadastro do usuário |
| -------- | ------------------- |
| Objetivo | Permitir ao usuário a funcionalidade de cadastro no aplicativo |
| Contexto | *Local*: Página inicial do aplicativo <br> *Pré-condição*: Ter o aplicativo instalado <br> *Estado final*: Usuário cadastrado |
| Atores | Usuário |
| Recursos | Conexão à internet, aplicativo instalado, dados para cadastro, CNH ou título de eleitor |
| Episódios | Usuário deseja se cadastrar no aplicativo <br> Usuário seleciona a opção "Entrar com gov<span>.</span>br" <br> Usuário seleciona a opção "Crie sua conta" <br> Usuário seleciona uma das opções de cadastro e prossegue com o cadastro
| Exceções | Aplicativo indisponível <br> Conexão instável com a internet <br> Usuário já possuir conta <br> Dados para cadastro inválidos |

## Cenário 2

|  Título  | Login do usuário |
| -------- | ------------------- |
| Objetivo | Permitir ao usuário fazer login no aplicativo |
| Contexto | *Local*: Página inicial do aplicativo <br> *Pré-condição*: Ter o aplicativo instalado, usuário cadastrado <br> *Estado final*: Usuário logado |
| Atores | Usuário |
| Recursos | Conexão à internet, aplicativo instalado, dados de login |
| Episódios | Usuário deseja realizar login no aplicativo <br> Usuário seleciona a opção "Entrar com gov<span>.</span>br" <br> Usuário digita o CPF para prosseguir <br> Usuário digita a senha <br> Usuário realiza o reconhecimento facial para finalizar o login
| Exceções | Aplicativo indisponível <br> Conexão instável com a internet <br> Usuário não cadastrado <br> Dados inválidos |

## Cenário 3

|  Título  | Visualizar documentos |
| -------- | ------------------- |
| Objetivo | Permitir ao usuário visualizar seus documentos |
| Contexto | *Local*: Dashboard inicial no aplicativo <br> *Pré-condição*: Usuário logado <br> *Estado final*: Documentos exibidos |
| Atores | Usuário |
| Recursos | Conexão à internet, aplicativo instalado |
| Episódios | Usuário deseja visualizar seus documentos <br> Usuário seleciona a opção "Documentos" <br> Usuário seleciona o documento a ser visualizado
| Exceções | Aplicativo indisponível <br> Conexão instável com a internet <br> Nenhum documento disponível |

## Referências
SOMMERVILLE, Ian. Engenharia de Software, Pearson Prentice Hall.