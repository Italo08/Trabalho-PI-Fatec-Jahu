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

#### RF03- Exibir meiots de Contatos
    O site deve ter algum tipo de formulario para contato.
    O site deve deixar disponivel telefones, e-mails e endereço do local.
  
#### RF04- Conter notícias e Eventos.
    O site deve permitir a publicação de novidades, campanhas e eventos futuros

#### RF05- Conseguir doações e apoio.
    O site deve conter uma aba propria para a possibilidade de doações e apoio da população

#### RF06- Realizar Cadastro de usuários.
    O sistema deve permitir cadastro de novos usuários

#### RF07- Realizar Login de usuários.
    O sistema deve conter uma aba para os usuários que já estiverem cadastrados para que possam efetuar login.

#### RF08 – Ter painel administrativo
    O sistema deve conter uma área administrativa para que membros autorizados da AMAI possam gerenciar cadastros,
	editar conteúdos e publicar novas informações no site.
---

## . ❌ Requisitos Não Funcionais

### Requisitos de Produto
	•	 – Desempenho: O site deve carregar completamente em até 3 segundos em conexões comuns.
	•	 – Responsividade: O layout deve se adaptar automaticamente a diferentes dispositivos (desktop, tablet e celular).
	•	 – Acessibilidade: O sistema deve seguir as diretrizes WCAG, garantindo contraste adequado, textos alternativos e
	       suporte a leitores de tela.
	•	 – Compatibilidade: O site deve funcionar corretamente nos principais navegadores (Chrome, Firefox, Edge e Safari).


### Requisitos de Organização
	•	 – Padronização do Código: O desenvolvimento deve seguir boas práticas de versionamento e organização, utilizando Git e GitHub.
	•	 – Documentação: O código deve conter comentários explicativos e documentação mínima para manutenção futura.
	•	 – Manutenção: O sistema deve permitir a inclusão de novos módulos sem reestruturação completa.


### Requisitos de Confiabilidade
	•	 – Disponibilidade: O sistema deve estar disponível 24h por dia, exceto em períodos de manutenção.
	•	 – Backup: Os dados armazenados devem possuir cópias de segurança periódicas.
	•	 – Integridade dos Dados: As informações inseridas pelos usuários devem ser validadas e protegidas
	       contra inconsistências.
			 

### Requisitos de Implementação
	•	 – Tecnologias Utilizadas: HTML5, CSS3, JavaScript e banco de dados relacional (MySQL ou Firebase).
	•	 – Frameworks e Ferramentas: Podem ser utilizados frameworks como Bootstrap e bibliotecas de acessibilidade.
	•	 – Controle de Versão: O projeto deve ser versionado com Git e armazenado em repositório público no GitHub.


### Requisitos de Padrões
	•	 – Usabilidade: O design deve ser simples, intuitivo e seguir boas práticas de UX/UI.
	•	 – Identidade Visual: O site deve manter as cores e o logotipo oficiais da AMAI.
	•	 – Linguagem: Os textos devem ser claros, acessíveis e adequados ao público da instituição.


### Requisitos de Interoperabilidade
	•	 – Integração: O sistema deve permitir integração futura com bancos de dados ou sistemas da prefeitura.
	•	 – Formatos de Dados: O sistema deve exportar e importar dados em formatos padrão, como CSV ou JSON.
	•	 – APIs: Caso sejam criadas APIs, elas devem seguir o padrão REST, facilitando expansões e integração com
	       outros sistemas.

---

## 3. 📊 Modelo de Casos de Uso

    - Cadastro de usuários
    - Login no sistema
    - Conhecer mais sobre a organização.

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

### •	Viabilidade técnica: 

    • Tecnologias necessárias:
      Desenvolvimento web (frontend e backend)
      Talvez algum uso de framework.

    • Banco de dados para armazenar informações dos usuários. 

    • Integração com sistemas da prefeitura se possível.

    • Infraestrutura: 
      Hospedagem do site, segurança de dados, talvez algum meio de backup e manutenção para o banco de dados.

### •	Viabilidade Financeira:

    • Hospedagem do site: 
      Caso o site não seja hospedado direto no site da prefeitura, teremos que ver a respeito de meios para
      serem hospedados (média de 100 a 200 por ano)

### •	Viabilidade de Mercado:

    • Cliente:
      No caso do nosso sistema já e uma demanda pedida por um cliente, para uso de cadastros de pessoas com deficiência
      no sistema da prefeitura.

    • Mercado:
      Talvez no futuro depois que de ver que funcionou o sistema como pedido e tenha tido sucesso, podemos ver a
      possibilidade de vender para outras cidades.

### •	Viabilidade Operacional:
       O projeto apresenta uma boa viabilidade operacional, pois o sistema vai ser de fácil utilização e poderá ser operado
       pelos próprios coordenadores da Secretaria de assistência e desenvolvimento social. E o sistema poderá ser acessado
       por qualquer dispositivo para que conheçam a história da parceira (AMAI) e uma aba para que realizem   seu cadastro
       com todas as principais informações para que a prefeitura tenha uma base de total de pessoas com deficiência tem na
       cidade e quantas precisam de algum auxílio profissional.

## 8. 💼 Regras de Negócio (Modelo Canvas)

 ### Proposta de Valor
    • Facilitar o cadastro, organização e consulta de informações de pessoas com deficiência (PCDs),
      promovendo uma melhor comunicação e integração entre a AMAI e a prefeitura, além de otimizar o
      acesso a dados para políticas públicas e programas sociais.

### Segmentos de Clientes
	•	Associação AMAI e seus colaboradores;
	•	Prefeitura municipal e setores responsáveis por inclusão e assistência social
	•	Pessoas PCDs que desejam se cadastrar e participar de programas de apoio.

### Canais de Distribuição
	•	Website oficial da AMAI e da prefeitura, acessível em computadores e dispositivos móveis
	•	Divulgação em redes sociais e canais institucionais da AMAI e da prefeitura.

### Fontes de Receita
	•	Projeto sem fins lucrativos, podendo receber apoio financeiro da prefeitura, doações ou patrocínios
	    de empresas locais para manutenção do sistema.
	•   Com a possibilidade de venda do website/sistema para outras cidades.

### Atividades Chave
	•	Desenvolvimento e manutenção do site
	•	Coleta e atualização de dados das pessoas cadastradas
	•	Suporte técnico e treinamento dos usuários da AMAI
	•	Divulgação do sistema à comunidade.

### Recursos Chave
	•	Equipe de desenvolvimento web
	•	Servidor e hospedagem do site
	•	Banco de dados para armazenar informações
	•	Computadores e acesso à internet.

### Parcerias Chave
	•	Prefeitura municipal (apoio técnico e institucional)
	•	Empresas locais (apoio financeiro ou tecnológico)
	•	Voluntários e desenvolvedores da comunidade.

### Estrutura de Custos
	•	Hospedagem e domínio do site
	•	Manutenção técnica e suporte
	•	Treinamento dos colaboradores da AMAI e da assistencia e desenvolvimento social
	•	Custos de divulgação e comunicação

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

