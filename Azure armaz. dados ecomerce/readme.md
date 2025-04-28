  📦 Projeto: Cadastro de Produtos na Nuvem 📦

Fala pessoal! Tudo certo? 😄
Esse repositório é o resultado de um projeto que desenvolvi durante o Bootcamp Microsoft Azure Cloud Native. A ideia foi criar uma aplicação simples, mas funcional, para cadastrar produtos e gerenciar as informações diretamente na nuvem usando Azure. Bora ver como ficou?



🔧 Tecnologias que usei

Microsoft Azure
Azure Blob Storage (para armazenar imagens)
Azure SQL Database (para salvar os dados dos produtos)
Python
Streamlit (para criar a interface rapidinho)
Pymssql (para conexão com SQL Server)
dotenv (para organizar variáveis de ambiente)
Pandas (para lidar com os dados de forma mais prática)


🚀 Como a aplicação funciona

O usuário preenche um formulário com nome, descrição, preço e imagem do produto.
A imagem é enviada para o Azure Blob Storage.
As informações do produto (com o link da imagem) são salvas no Azure SQL Database.
A aplicação lista todos os produtos cadastrados, bonitinhos em cards.



👉 Tela da aplicação

[Projeto Dio Me](https://github.com/user-attachments/assets/1765d4d4-f780-4198-b5dc-bc6e7e4261fc)




💡 O que eu aprendi na prática

Durante o projeto, coloquei a mão na massa em várias coisas:
Fazer upload de arquivos para o Azure Blob Storage usando Python.
Conectar a aplicação ao Azure SQL Database de forma segura usando variáveis de ambiente (.env).
Trabalhar com Streamlit para criar uma interface web de forma rápida e sem complicação.
Organizar o fluxo de dados da aplicação: do input do usuário até o armazenamento e exibição na tela.
E claro, entender melhor como serviços cloud da Azure funcionam na prática.



🌱 Ideias para evoluir o projeto

Ainda dá para melhorar bastante! Algumas ideias:
Implementar login para diferentes usuários.
Criar filtros de busca ou categorias para os produtos.
Melhorar o layout da listagem (deixar mais parecido com um site real de e-commerce).
Fazer o deploy do app em um serviço de hospedagem na nuvem (Azure App Service, por exemplo).
