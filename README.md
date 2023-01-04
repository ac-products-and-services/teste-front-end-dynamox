# Desafio Front-end Dynamox

> Desafio para ingressar como Front-end Developer na Dynamox

## Sobre a Dynamox

A Dynamox é uma empresa de alta tecnologia que desenvolve sistemas de monitoramento e aquisição de dados de vibração e temperatura. Somos uma empresa especialista em análise de vibrações e monitoramento da condição de ativos industriais.

Todas as soluções são desenvolvidas por nossa equipe, desde o hardware até a aplicação web. Nossa equipe é formada por desenvolvedores de hardware, firmware, mobile (android e ios) e web (backend e frontend), além de engenheiros especializados na área de processamento de sinais para vibração e acústica.


## Sobre a vaga e os desafios

Estamos buscando alguém que se identifique com o [perfil da vaga](https://dynamox.solides.jobs/vacancies/181263?__hstc=127459538.1d0234f804b73865f84753db24577b25.1658333603238.1663969357474.1664197850410.19&__hssc=127459538.3.1664197850410&__hsfp=309846428) e que possa integrar uma de nossas frentes de desenvolvimento:

- Relações Públicas (presença institucional);
- [DynaPredict](https://dynamox.net/dynapredict);

Para isso, sugerimos dois desafios. O primeiro para avaliar como você implementa um design definido para uma landing page e o segundo para avaliar suas abilidades em realizar operações básicas de CRUD e chamadas a uma api.

---

## Desafio 01 - Landing page

Neste desafio avaliaremos sua capacidade de implementar uma landing page com design pré definido, para ser visualizada em dispositivo desktop.

[Protótipo do Figma](https://www.figma.com/file/oMYCDyVORucqrRrohyQpwC/Desafio-01---Front-end?node-id=0%3A1)

Requisitos funcionais:

**Header**

- Ao clicar no logo Dymamox, usuário deve ser redirecionado para https://dynamox.net/
- Ao clicar em “DynaPredict”, usuário deve ser redirecionado para https://dynamox.net/dynapredict/
- Ao clicar em "Sensores", usuário deve ser movido para a seção de sensores da landing page.
- Ao clicar em "Contato", usuário deve ser movido para seção de contato da landing page.

**Sensores**

- Ao clicar em "Ver Mais" usuário deve ser redirecionado para https://dynamox.net/dynapredict/.

**Contato**

- Ao clicar em "Enviar", website deve emitir alerta contendo o conteúdo dos campos do formulário de contato.

Critérios de avaliação:

- Design: implementação do layout de acordo com o layout proposto;
- Funcionalidades: redirecionamentos para links e seções e disparo de funções no browser;
- Semântica e SEO: utilização de tags e metatags html adequados;

### Tecnologias, frameworks e bibliotecas

- A utilização de React é obrigatória;
- O restante das ferramentas fica a seu critério;

### Diferenciais

- Componentes reutilizáveis;
- Organização e documentação do código;
- Usabilidade;
- Layout responsivo (seja criativo!);
- Utilização de NextJS ou Gatsby;

---

## Desafio 02 - Autenticação e CRUD

Neste desafio avaliaremos sua capacidade de realizar operações básicas de criação, leitura, atualização e remoção de dados a uma api fake. Neste desafio, não serão avaliadas questões relacionadas ao design da aplicação.

Desenvolva uma tela de autenticação fake. O login pode ser feito com e-mail e senha fixos, porém as rotas devem ser privadas e as requests à API devem simular o envio do token JWT, que também poderá ser fake.

Requisitos funcionais:

- Aplicação deverá ter telas de criação, edição e listagem de produtos, com os campos:

  - Nome;
  - Data de fabricação;
  - Produto perecível (booleano);
  - Data de validade;
  - Preço;

- O usuário só deverá ter acesso às rotas de criação, edição e listagem de produtos caso esteja autenticado;
- O usuário só poderá cadastrar data de validade caso o produto seja perecível;
- A data de fabricação nunca deverá ser maior que a data de validade;
- O preço deverá estar em reais (R$);
- A tela de listagem deverá ter a possibilidade de ordenação dos campos e com uma paginação de 10 produtos por página.
- O backend deve ser simulado com [json-server](https://www.npmjs.com/package/json-server), que cria uma API REST fake;

### Tecnologias, frameworks e bibliotecas

- A utilização de React é obrigatória;
- A utilização de Redux para controle de estados globais é obrigatória;
- O restante das ferramentas fica a seu critério;

### Diferenciais

- Utilizar Redux Saga para controle de efeitos colaterais assíncronos;
- Componentes reutilizáveis;
- Organização e documentação do código;
- Usabilidade;
- Layout responsivo (seja criativo!);

## Pronto para começar os desafios?

- Faça um "fork" deste repositório (dynamox-s-a/teste-front-end) na sua conta do Github;
- No seu fork, crie uma branch contendo o número do desafio, seu nome e sobrenome seguindo o padrão `desafio-xx/nome-sobrenome`:
  - Ex.: `desafio-01/caroline-oliveira`
- Após completar o desafio, crie uma "pull request" neste repositório ([dynamox-s-a/teste-front-end](https://github.com/dynamox-s-a/teste-front-end)) comparando a branch de seu fork, com a master deste repositório;
  - Ex.: `carolina/teste-front-end:desafio-01/carolina-oliveira` -> `dynamox-s-a/teste-front-end:master`;
- Faça isso para cada um dos desafios separadamente;
- Receberemos uma notificação do seu pull request, faremos a avaliação da sua solução e entraremos em contato;

## FAQ

- Posso usar o create-react-app para completar o desafio?
  **Sim, você pode usar qualquer cli para criar seu projeto**
- Posso usar o Next ou Gatsby para completar o desafio?
  **Sim e até gostaremos de ver que usou alguma dessas ferramentas!**
- Preciso necessariamente fazer um fork do projeto?
  **Sim, para que possamos saber quanto tempo você levou para executar o desafio**
- Posso usar MaterialUI no projeto?
  **Sim e até gostaremos de ver que utilizou algum framework ou bibliotecas de react para UI**.

- Tenho mais dúvidas, com quem posso entrar em contato?
  **Entre em contato com [Calil](https://github.com/amaralc) (Front-end Developer)**

**Boa sorte.** 🚀
