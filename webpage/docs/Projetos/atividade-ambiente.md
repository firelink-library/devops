---
sidebar_position: 4
title: Projeto de Aplicação Web Segura
slug: /atividade-01
---

## Desenvolvimento Projeto de Aplicação Web Modularizada

Este projeto tem por objetivo verificar alguns pontos importantes para o desenvolvimento de projetos web, utilizando containers e uma configuração segura para a aplicação.

### Objetivo

O grande objetivo desta atividade é desenvolver uma aplicação web modularizada, utilizando containers e uma configuração segura para a aplicação.

> Mas Murilão você acabou de dizer isso!

Sim, mas não custa reforçar!

Agora vamos lá, frente nosso objetivo, acho que faz bastante sentido apresentar alguns objetivos específicos:

1. **Aplicação modularizada**: A aplicação deve ser dividida em módulos, incluindo um front-end, um back-end, um banco de dados e um servidor web.
2. **Uso de containers**: Cada módulo deve ser executado em um container separado, garantindo isolamento e organização.
3. **Configuração segura**: A aplicação deve estar configurada em uma rede dedicada, expondo apenas as portas necessárias para o funcionamento.
4. **Acesso via navegador**: A aplicação deve ser acessível por meio de um navegador web, hospedada em uma cloud comercial.

### Requisitos

A aplicação deve atender aos seguintes requisitos funcionais e técnicos:

#### Funcionalidades Básicas

1. **Cadastro de usuários**: Permitir que novos usuários sejam registrados no sistema.
2. **Autenticação de usuários**: Implementar um sistema de login para validar as credenciais dos usuários.
3. **Listagem de usuários cadastrados**: Exibir uma lista com todos os usuários registrados.
4. **Edição de usuários cadastrados**: Permitir a atualização das informações dos usuários.
5. **Exclusão de usuários cadastrados**: Permitir a remoção de usuários do sistema.
6. **Cadastro de produtos**: Registrar novos produtos no sistema (o tipo de produto é livre).
7. **Listagem de produtos cadastrados**: Exibir uma lista com todos os produtos registrados.
8. **Edição de produtos cadastrados**: Permitir a atualização das informações dos produtos.
9. **Exclusão de produtos cadastrados**: Permitir a remoção de produtos do sistema.

#### Requisitos Técnicos

10. **Front-end**: Deve ser desenvolvido utilizando qualquer framework de sua escolha (ex.: React, Angular, Vue.js, etc.).
11. **Back-end**: Deve ser desenvolvido utilizando GoLang com o framework Gin.
12. **Banco de dados**: Utilizar PostgreSQL para armazenar os dados.
13. **Servidor web**: Utilizar Nginx para servir a aplicação.
14. **Gerenciamento de usuários**: Deve incluir, no mínimo, os seguintes campos:
    - Nome do usuário;
    - Email;
    - Senha;
    - Foto de perfil.
15. **Gerenciamento de produtos**: Deve incluir, no mínimo, os seguintes campos:
    - Imagem do produto;
    - Valor;
    - Quantidade;
    - Descrição.
16. **Armazenamento de imagens**: Implementar uma solução para armazenar as imagens (tanto de usuários quanto de produtos) no sistema.

#### Observações Importantes

- A aplicação deve ser modularizada, com cada módulo (front-end, back-end, banco de dados e servidor web) executado em um **container separado**.
- A aplicação deve ser configurada em uma **rede dedicada**, expondo apenas as portas necessárias para o funcionamento.
- A aplicação deve ser acessível por meio de um navegador web e hospedada em uma **cloud comercial**.
- Deve ser utilizada **alguma tecnologia para armazenar as imagens (arquivos)**, ficando a critério de vocês como isso será realizado.

Esses requisitos foram definidos para simular um ambiente de desenvolvimento real, utilizando boas práticas de modularização, segurança e organização.

### Avaliação

<img src="./img/imagens-atividades/shark-tiger.jpeg" style={{ display: 'block', marginLeft: 'auto', maxHeight: '40vh', marginRight: 'auto', marginBottom: '24px' }}/>

Imagem completamente não relacionada, ams que achei legal.

1. O código fonte da solução deve estar disponível em um repositório público no Github (na branch main), em um diretório denominado src. Os módulos que compõe o seu código-fonte devem ser divididos em subdiretórios.
2. As instruções para  executar o projeto devem estar claramente discriminadas na documentação, com um link no README para que a seção possa ser prontamente acessada.
3. As descrições de documentação devem estar no README do projeto.

### Barema de Qualidade

***[0,0 - 3,0]*** A atividade não foi bem implementada, a implementação não esta completa e sainda não é possível executar o sistema completamente.

***[3,0 - 7,0]*** O projeto foi minimamente implementado e apresentado. Durante a apresentação, alguns conceitos não ficaram claramente apresentados.

***[7,0 - 9,0]*** Durante a apresentação da solução, ela funcionou corretamente e todos os conceitos foram claramente implementados.

***[9,0 - 10,0]*** Além do funcionamento e apresentação correta, foram implementados diferenciais na aplicação que fazem sentindo em sua implementação.

