# Projeto 3 - API do Urban.Grocers

### Visão geral
Projeto realizado pela plataforma da TripleTen, um novo recurso foi adicionado à API do Urban.Grocers, aplicativo para pedir comida que oferece entrega rápida, onde foram testadas as funcionalidades do aplicativo, realizado checklist e testes de API.

### O que foi feito
1. Criei e enviei solicitações à API via Postman;
2. Testei o aplicativo e criei relatórios de bug;
3. Li a documentação da API;
4. Decompus e visualizei os requisitos;
5. Criei os primeiros testes de API;
4. Defini os casos de teste e projetei testes com a ajuda de técnicas de design de teste;
5. Preparei a documentação do teste;
6. Testes positivos e negativos.

## conhecimento teórico do teste de API:
1. Estrutura HTTP;
2. Formato JSON;
3. REST;
4. Técnicas de design de testes para API.

### Funcionalidade
Urban.Grocers é um aplicativo para pedir comida que oferece entrega rápida. 

### Requisitos API
[Baixe aqui](https://github.com/bibiellabraz/meusarquivos/blob/6a6ff6c477bca073ba576e35fd2a361819fbce32/3%20Requisitos_para_o_back-end_do_Urban.grocers.pdf)

### Requisitos dos novos recursos
A nova funcionalidade cobre diversas áreas, inclusive trabalho com kits, entregas e o carrinho:
1. Trabalho com kits: a capacidade de adicionar produtos a um kit. O endpoint é POST /api/v1/kits/{id}/products
2. Trabalho com serviços de entrega: a capacidade de verificar se o serviço de entrega Order and Go está disponível e quanto custa. O endpoint é POST /order-and-go/v1/delivery
3. Trabalho com o carrinho: A capacidade de receber uma lista de produtos adicionados ao carrinho. O endpoint é GET /api/v1/orders/:id
4. A capacidade de adicionar produtos ao carrinho. O endpoint é PUT /api/v1/orders/:id
5. A capacidade de excluir o carrinho. O endpoint é DELETE /api/v1/orders/:id   

### Tecnologias e aplicativos
1. Jira

