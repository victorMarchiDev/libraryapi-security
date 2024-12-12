# 📚 Library API - Security API

Bem-vindo à API de livros! Este projeto foi desenvolvido para gerenciar e consultar informações sobre livros e autores, oferecendo recursos modernos e eficientes para facilitar o acesso aos dados. 🚀

## 🛠️ Tecnologias Utilizadas

- **Java**: Linguagem principal utilizada para desenvolver a API.  
- **Spring Boot**: Framework para construção da aplicação, com módulos como Spring Data JPA, Spring Web e Spring Security.  
- **PostgreSQL**: Banco de dados relacional utilizado para persistência dos dados.  
- **Docker**: Ferramenta para containerização, garantindo fácil implantação e configuração do projeto.

## 🔑 Autenticação e Segurança

Este projeto utiliza **Spring Security** para implementar autenticação e autorização de usuários. Apenas usuários autenticados têm acesso aos endpoints protegidos. A autenticação é baseada em HTTP Basic Auth para garantir maior segurança e praticidade.

## 🌟 Recursos Principais

1. **Gerenciamento de Livros e Autores**  
   - Consultar a lista de livros.  
   - Consultar a lista de autores.  
   - Visualizar os detalhes de um livro ou autor específico.  

2. **Busca Paginada**  
   - Os endpoints que retornam listas de livros e autores suportam paginação, permitindo controlar o número de resultados retornados e navegar pelas páginas.

3. **Endpoints Protegidos**  
   - Operações sensíveis exigem autenticação, garantindo que apenas usuários autorizados possam acessá-las.
