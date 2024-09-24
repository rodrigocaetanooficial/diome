# Criando um Assistente de Delivery com AWS Step Functions e Bedrock

Este repositório contém os códigos e anotações que desenvolvi ao longo do módulo "Criando um Assistente de Delivery com AWS Step Functions e Bedrock", parte do curso oferecido pela [DIO (Digital Innovation One)](https://dio.me). Nesse módulo, aprendi a utilizar uma combinação poderosa de serviços da AWS para criar e gerenciar fluxos automatizados e inteligentes para um assistente de delivery.

## O que eu aprendi

### 1. **AWS Step Functions**
   - **Orquestração de Serviços**: Como usar o AWS Step Functions para orquestrar diferentes serviços da AWS, criando fluxos de trabalho escaláveis e monitoráveis.
   - **Definição de Fluxos de Trabalho**: Através de JSON e do Amazon States Language, aprendi a definir estados, transições e atividades, conectando diferentes serviços como Lambda, DynamoDB, S3 e outros.
   - **Automatização**: Como criar fluxos automáticos que lidam com processos complexos, como o gerenciamento de pedidos de um sistema de delivery, desde a criação do pedido até sua conclusão.
   - **Monitoramento e Tolerância a Falhas**: Uso de logs e ferramentas de monitoramento integradas para verificar o status e lidar com erros automaticamente dentro dos fluxos.

### 2. **Amazon Bedrock**
   - **Inteligência Artificial e Machine Learning**: Descobri como o Amazon Bedrock facilita a criação e integração de modelos de machine learning de forma escalável e rápida, com foco em LLMs (Large Language Models).
   - **Geração de Texto e Conversação Natural**: Apliquei Bedrock para criar funcionalidades que permitem a interação natural com os usuários, como em um assistente virtual de delivery que entende e responde perguntas sobre status de pedidos e estimativas de entrega.
   - **Treinamento e Deploy de Modelos**: Aprendi o básico de como treinar e ajustar modelos personalizados, e implementá-los com facilidade utilizando a infraestrutura da AWS, sem precisar me preocupar com a manutenção de servidores.

### 3. **Integração dos Serviços**
   - **AWS Lambda**: Criei funções serverless para complementar o fluxo, permitindo que tarefas como o processamento de pedidos e consultas no banco de dados fossem executadas automaticamente.
   - **AWS DynamoDB**: Utilizei o DynamoDB para armazenar e consultar dados de pedidos em tempo real, garantindo alta disponibilidade e escalabilidade para o assistente de delivery.
   - **S3 e API Gateway**: Configurei armazenamento de dados e interfaces para interações com o assistente, como upload de arquivos ou APIs para uso externo.

### 4. **Implementação Prática**
   - **Cenário de Assistente de Delivery**: No final do módulo, implementei um cenário completo de um assistente de delivery, capaz de gerenciar pedidos, monitorar status e responder a consultas dos clientes de forma automatizada e inteligente.
   - **Testes e Validação**: Aprendi a testar fluxos e automatizar o processo de deployment para garantir que o sistema funcione corretamente em produção.

## Ferramentas Utilizadas
- **AWS Step Functions**
- **Amazon Bedrock**
- **AWS Lambda**
- **DynamoDB**
- **S3**
- **API Gateway**

## Conclusão
Esse módulo foi uma ótima introdução às poderosas ferramentas da AWS, especialmente no que diz respeito à automação e à integração com inteligência artificial. Com a combinação de Step Functions e Bedrock, é possível criar soluções escaláveis e inteligentes para diversos tipos de assistentes automatizados.
