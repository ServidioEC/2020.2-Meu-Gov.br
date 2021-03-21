## Histórico de Versões

| Data       | Versão | Descrição                                | Autores          | Revisor          |
| ---------- | ------ | ---------------------------------------- | ---------------- | ---------------- |
| 20/03/2021 | 0.1    | Criação da Página                        |   Pedro Haick    | ---------------- |
| 20/03/2021 | 0.2    | Adição dos cenários 1 a 3                |   Pedro Haick    | ---------------- |
| 20/03/2021 | 0.3    | Adição dos cenários 4 a 7                |   Pedro Haick    | ---------------- |

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

## Cenário 4

|  Título  | Visualizar proteção dos dados |
| -------- | ------------------- |
| Objetivo | Permitir ao usuário visualizar quais autorizações foram concedidas aos seus dados |
| Contexto | *Local*: Dashboard inicial no aplicativo <br> *Pré-condição*: Usuário logado <br> *Estado final*: Autorizações exibidas |
| Atores | Usuário |
| Recursos | Conexão à internet, aplicativo instalado |
| Episódios | Usuário deseja visualizar a situação da proteção de seus dados <br> Usuário seleciona a opção "Proteção de Dados" <br> Autorizações concedidas aos dados do usuário são exibidas
| Exceções | Aplicativo indisponível <br> Conexão instável com a internet <br> Nenhuma autorização concedida |

## Cenário 5

|  Título  | Rever instruções |
| -------- | ------------------- |
| Objetivo | Permitir ao usuário que reveja as instruções do aplicativo |
| Contexto | *Local*: Dashboard inicial no aplicativo <br> *Pré-condição*: Usuário logado <br> *Estado final*: Instruções exibidas |
| Atores | Usuário |
| Recursos | Conexão à internet, aplicativo instalado |
| Episódios | Usuário deseja rever as instruções <br> Usuário seleciona a última aba do aplicativo <br> Usuário seleciona a opção "Rever instruções Meu gov<span>.</span>br" |
| Exceções | Aplicativo indisponível <br> Conexão instável com a internet |

## Cenário 6

|  Título  | Ver a política de privacidade |
| -------- | ------------------- |
| Objetivo | Permitir ao usuário que leia a política de privacidade do aplicativo |
| Contexto | *Local*: Dashboard inicial no aplicativo <br> *Pré-condição*: Usuário logado <br> *Estado final*: Política de privacidade exibida |
| Atores | Usuário |
| Recursos | Conexão à internet, aplicativo instalado |
| Episódios | Usuário deseja ler a política de privacidade <br> Usuário seleciona a última aba do aplicativo <br> Usuário seleciona a opção "Política de Privacidade" |
| Exceções | Aplicativo indisponível <br> Conexão instável com a internet |

## Cenário 7

|  Título  | Logout do usuário |
| -------- | ------------------- |
| Objetivo | Permitir ao usuário fazer logout do aplicativo |
| Contexto | *Local*: Dashboard inicial no aplicativo <br> *Pré-condição*: Usuário logado <br> *Estado final*: Usuário deslogado |
| Atores | Usuário |
| Recursos | Conexão à internet, aplicativo instalado |
| Episódios | Usuário deseja realizar logout do aplicativo <br> Usuário seleciona a última aba do aplicativo <br> Usuário seleciona a opção "Sair do meu gov<span>.</span>br"
| Exceções | Aplicativo indisponível <br> Conexão instável com a internet |

## Referências
SOMMERVILLE, Ian. Engenharia de Software, Pearson Prentice Hall.