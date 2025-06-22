# serverless-cadastro-produtos

# 🛠️ Aplicação Serverless com AWS – Cadastro de Produtos

Este projeto foi realizado como parte dos laboratórios oferecidos pela **Escola da Nuvem**, com foco na construção de aplicações **serverless** utilizando serviços gerenciados da AWS.

## 🎯 Objetivo

Construir uma **aplicação web simples de cadastro de produtos**.

- O **frontend estático** será hospedado em um bucket do **Amazon S3**.
- As requisições de **criação, leitura, atualização e exclusão (CRUD)** serão processadas por uma função **AWS Lambda**.
- A função Lambda interage diretamente com uma **tabela Amazon DynamoDB**.
- Todas as chamadas passam por um endpoint configurado no **Amazon API Gateway**.
- O monitoramento da solução será feito por meio do **Amazon CloudWatch Logs**.

## 🧩 Serviços Utilizados

- **IAM** – Criação de role com permissões adequadas para Lambda e DynamoDB  
- **Amazon DynamoDB** – Tabela de produtos  
- **AWS Lambda** – Função em Python para operações CRUD  
- **Amazon API Gateway** – Integração da API  
- **Amazon S3** – Hospedagem da interface web  
- **Amazon CloudWatch** – Monitoramento de logs e métricas

## 🔄 Funcionalidades Implementadas

- CRUD completo via API Gateway
- Integração com banco NoSQL (DynamoDB)
- Frontend web estático com formulário
- Logs de execução e erros via CloudWatch
- Limpeza final dos recursos utilizados

## 📷 Capturas de Tela

*(Adicione imagens da aplicação, CloudWatch, tabela do DynamoDB, etc.)*

## 🧹 Limpeza de Recursos

Ao final do laboratório, todos os recursos foram removidos para evitar custos adicionais.

## 🏷️ Créditos

Este laboratório foi realizado com apoio da **Escola da Nuvem**.
