**README do Projeto BethanysPieShop**

## Visão Geral

O BethanysPieShop é um projeto de comércio eletrônico que oferece uma plataforma de venda de tortas artesanais. Utilizando uma combinação de tecnologias web e ferramentas de desenvolvimento robustas, este projeto visa proporcionar uma experiência de usuário excepcional e garantir a integridade e segurança dos dados dos clientes.

## Tecnologias Utilizadas

- **Front-End:**
  - HTML, CSS e Bootstrap: Responsáveis pelo layout e design responsivo do site.

- **Back-End:**
  - ASP.NET Core MVC, Razor Pages e Blazor: Utilizados para criar páginas web dinâmicas, permitindo a interação do cliente com o catálogo de tortas, o carrinho de compras e a finalização de pedidos.

- **Banco de Dados:**
  - Entity Framework e SQL Server: Gerenciamento eficiente e seguro dos dados relacionados a produtos, pedidos e clientes.

- **Autenticação e Autorização:**
  - Identity da Microsoft: Implementado para autenticação e autorização de clientes, permitindo a criação de contas seguras e personalizadas.

- **Hospedagem:**
  - Microsoft Azure: O projeto foi implantado na infraestrutura de hospedagem do Azure, garantindo alta disponibilidade e escalabilidade.

## Recursos Principais

1. **Catálogo de Tortas:** Apresenta tortas com imagens, descrições detalhadas e preços para facilitar a escolha do cliente.

2. **Carrinho de Compras:** Os clientes logados podem adicionar produtos ao carrinho de compras, que exibe uma visão geral dos itens selecionados, permitindo ajustes e revisão antes da finalização do pedido.

3. **Página de Pesquisa:** Oferece uma funcionalidade de pesquisa avançada para facilitar a localização de tortas específicas.

4. **Página de Contato:** Permite que os clientes entrem em contato diretamente com a equipe da BethanysPieShop.

## Benefícios

- **Conveniência:** Os clientes podem encomendar tortas a qualquer momento e de qualquer lugar, graças à plataforma de comércio eletrônico acessível.

- **Variedade:** O catálogo em constante expansão oferece uma ampla seleção de tortas para satisfazer diferentes gostos.

- **Segurança:** A autenticação e autorização do Identity da Microsoft garantem a proteção das informações dos clientes e a segurança das transações.

- **Escalabilidade:** A hospedagem no Microsoft Azure assegura alta disponibilidade e escalabilidade para atender às demandas dos clientes.

## Instalação e Execução Local

Para executar o projeto localmente, siga as etapas abaixo:

1. Clone o repositório para a sua máquina local.
2. Abra o projeto em seu ambiente de desenvolvimento preferido.
3. Configure a conexão com o banco de dados SQL Server no arquivo `appsettings.json`.
4. Execute as migrações do Entity Framework para criar o banco de dados: `dotnet ef database update`.
5. Inicie o aplicativo com o comando: `dotnet run`.
6. Acesse o aplicativo em seu navegador em `http://localhost:####`.

## Contribuição

Sinta-se à vontade para contribuir para o projeto BethanysPieShop. Se você encontrar problemas, tiver sugestões ou desejar adicionar novos recursos, abra uma _issue_ ou envie uma _pull request_.

## Licença

Este projeto está sob a licença [MIT](LICENSE).

---

O BethanysPieShop é um projeto que combina a tradição das tortas artesanais com a inovação tecnológica. Esperamos que você desfrute da experiência culinária oferecida por este site. Para obter mais informações ou entrar em contato, visite [BethanysPieShop.com](https://bethanyspieshopbr.azurewebsites.net/).
