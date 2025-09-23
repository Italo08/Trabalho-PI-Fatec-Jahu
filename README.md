# 📚 Documentação do PI

Esta documentação descreve o andamento do PI (Projeto Integrador) da faculdade, abordando as etapas realizadas e a evolução do projeto.

## 📑 Sumário

<details>
  <summary><strong>Expandir Sumário</strong></summary>

- [1. Introdução](#1-introdução)
  - [Objetivos](#objetivos)
  - [Metodologia](#metodologia)
- [2. Requisitos](#2-requisitos)
  - [Requisitos funcionais](#requisitos-funcionais)
  - [Requisitos não funcionais](#requisitos-não-funcionais)
- [3. Modelo de casos de uso](#3-modelo-de-casos-de-uso)
- [4. Modelo do banco de dados](#4-modelo-do-banco-de-dados)
- [5. Banco de dados](#5-banco-de-dados)
- [6. Diagrama de classes](#6-diagrama-de-classes)
- [7. Estudo de viabilidade](#7-estudo-de-viabilidade)
- [8. Regras de negócio (Modelo Canvas)](#8-regras-de-negócio-modelo-canvas)
- [9. Design](#9-design)
- [10. Protótipo](#10-protótipo)
- [11. Aplicação](#11-aplicação)

</details>

---

## 1. 📜 Introdução

### Contextualização & Justificativa

AMAI Jau ( Associação e movimento de assistencia ao indivíduo deficiente ) uma entidade sem fins lucrativos criada por PCDs que se reuniram com o objetivo de fundarem uma entidade de prestação de serviços e
atendimento a deficientes físicos, auditivos, visuais e múltiplos. Escolhemos a AMAI porque acreditamos na importancia da inclusão social e no impacto positivo que iniciativas voltadadas às pessoas com deficiência
geram na comunidade. O que nos motivou foi perceber como o trabalho da AMAI vai além do atendimento básico, oferecendo acolhimento, dignidade e oportunidades de desenvolvimento. Esse movimento é fundamental porque
promove a valorização do movimento combatendo o preconceito e contribuindo assim para uma sociedade mais unida.

---

### • Objetivos

O que visamos alcançar com este projeto? 

##### - Objetivo principal
  
    Desenvolver um site institucional para a AMAI, integrado à prefeitura da cidade, que possibilite o cadastro e getenciamento
    de informações de pessoas com deficiência (PCDs), funcionando commo um banco de dados confiável para auxiliar no planejamento,
    acompanhamento e oferta de serviços de inclusão social.

  
##### - Objetivos específicos


    1.	Criar um portal informativo que apresente a AMAI, sua missão, visão, valores e projetos.

    2.	Desenvolver um sistema de cadastro online para pessoas PCDs, com armazenamento seguro dos dados.
  
    3.	Permitir que a prefeitura e a AMAI tenham acesso aos dados para fins de acompanhamento, inclusão em programas sociais
    e políticas públicas.
  
    5.	Disponibilizar relatórios gerenciais para análise dos perfis cadastrados.
  
    6.	Implementar recursos de acessibilidade digital (contraste, fontes ampliadas, leitores de tela, textos alternativos).
  
    7.	Facilitar a comunicação entre PCDs, familiares, AMAI e prefeitura por meio de formulários de contato e integração com redes
    sociais.
  
    9.	Criar uma área destinada a campanhas, eventos e notícias relevantes para a comunidade.
  
    10.	Estimular a participação social, oferecendo opções de doações e voluntariado diretamente no site.

---

### • Metodologia

Aqui, explique como será o desenvolvimento do projeto.

- **Métodos utilizados** (ex.: ágil, cascata, etc.)
- **Tecnologias e ferramentas** (ex.: Node.js, Figma, MySQL)
- **Processos e abordagens** (ex.: Scrum, Kanban)

Responda à pergunta: *Como? Com o quê? Onde? Quando?*

---

## 2. 📋 Requisitos

### • Requisitos Funcionais

#### RF01- Exibir informações da instituição
O site deve apresentar a missão, visão e valores e a historia da AMAI Jau.

#### RF02- Divulgar projetos e serviços
O site deve disponibilizar informações sobre os programas, atividades e ações sociais já realizadas pela AMAI

#### RF03- Contatos
O site deve ter algum tipo de formulario para contato.
O site deve deixar disponivel telefones, e-mails e endereço do local.

#### RF04- Notícias e Eventos.
O site deve permitir a publicação de novidades, campanhas e eventos futuros

#### RF05- Doações e apoio.
O site deve conter uma aba propria para a possibilidade de doações e apoio da população

#### RF06- Cadastro de usuários.
O sistema deve permitir cadastro de novos usuários

#### RF07- Login de usuários.
O sistema deve conter uma aba para os usuários que já estiverem cadastrados para que possam efetuar login.

#### RF08- Navegação com acessibilidade  
Todo o site deve conter o sistema de acessibilidade desde o login até a navegação do site.

#### RF09- 
---

### • Requisitos Não Funcionais

Liste os **requisitos de qualidade** que o sistema deve ter, como:

- **Desempenho**: o sistema deve ser capaz de suportar até 1000 requisições simultâneas.
- **Segurança**: autenticação via OAuth2.
- **Usabilidade**: design responsivo, fácil de usar.

#### Subcategorias de requisitos não funcionais:

- **Requisitos de produto**
- **Requisitos de organização**
- **Requisitos de confiabilidade**
- **Requisitos de implementação**
- **Requisitos de padrões**
- **Requisitos de interoperabilidade**

---

## 3. 📊 Modelo de Casos de Uso

Inclua os principais casos de uso que o sistema deve oferecer. Isso pode ser feito de forma textual ou com diagramas.

Exemplo de casos de uso:

- Cadastro de usuário
- Login no sistema

---

## 4. 🗂️ Modelo do Banco de Dados

Descreva os modelos do banco de dados:

- **Modelo Conceitual**: Diagrama ER (Entidade-Relacionamento).
- **Modelo Lógico**: Estrutura das tabelas e relacionamentos.
- **Modelo Físico**: Como os dados serão armazenados no banco.

---

## 5. 💾 Banco de Dados

Aqui, descreva o banco de dados utilizado, como ele está estruturado, as tabelas e relações que existem, além dos detalhes de implementação.

---

## 6. 🧳 Diagrama de Classes

Adicione o **diagrama de classes** do sistema, explicando as entidades e seus relacionamentos. 

Caso não tenha, você pode incluir uma descrição das principais classes envolvidas.

---

## 7. 🔍 Estudo de Viabilidade

Realize uma análise sobre a **viabilidade** técnica, financeira e de prazo para a execução do projeto. Como será o impacto do projeto e sua sustentabilidade?

---

## 8. 💼 Regras de Negócio (Modelo Canvas)

Inclua o modelo **Canvas** que define as regras de negócios e a estrutura do projeto:

- **Proposta de valor**
- **Segmentos de clientes**
- **Canais de distribuição**
- **Fontes de receita**
- **Atividades chave**
- **Recursos chave**
- **Parcerias chave**
- **Estrutura de custos**

---

## 9. 🎨 Design

Aqui, fale sobre os aspectos de design do sistema:

- **Paleta de cores**
- **Tipografia**
- **Logo**
- **Wireframes**
- **Modelo de navegação**

Você pode adicionar imagens, como mockups ou esquemas, para ilustrar.

---

## 10. 🖥️ Protótipo

Inclua o protótipo funcional do sistema, com um link para a ferramenta em que ele foi desenvolvido, como o [Figma](https://www.figma.com/). 

Exemplo:

- [Acesse o protótipo no Figma](https://www.figma.com/file/12345/prototipo)

---

## 11. 💻 Aplicação

Descreva o estado atual da aplicação. Caso já tenha uma versão inicial funcionando, forneça detalhes:

- **Tecnologias utilizadas** (front-end, back-end, banco de dados)
- **Como executar a aplicação localmente**: Instruções para rodar o projeto em um ambiente local.

---

