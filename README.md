# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS


Data: 13 de março de 2026


Empresa: Abstergo Industries 


Responsável: Lucas Santos Pimentel


## Introdução

Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Lucas Pimentel. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.


## Descrição do Projeto

O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:


Etapa 1: 

- Amazon S3 (Simple Storage Service)

- Armazenamento de arquivos e documentos em nuvem.

- A Abstergo Industries lida com um grande volume de dados, como: notas fiscais, contratos com fornecedores, bulas e registros regulatórios. Isso acaba por exigir a compra constante de servidores de arquivos físicos. Com o Amazon S3, migraremos todos esses documentos pra nuvem. O custo é reduzido porque deixamos de comprar hardwares caros e passamos a pagar apenas pelos Gigabytes efetivamente utilizados por mês, além de economizar com a energia elétrica e refrigeração do datacenter local.


Etapa 2: 

- Amazon EC2 (Elastic Compute Cloud)

- Servidores virtuais para processamento e hospedagem de sistemas.

- O sistema de vendas Business to Business e o portal de pedidos para outras farmácias será hospedado no EC2. Como nossos clientes são empresas vamos presumir que o pico de acesso ocorre em horário comercial (8h às 18h). Utilizaremos o EC2 junto com o Auto Scaling para ligar servidores durante o dia e desligá-los (ou reduzi-los grandemente) durante a noite e nos finais de semana. Isso gera uma redução de custos muito alta, porque a empresa para de pagar por servidores ociosos fora do horário de pico.


Etapa 3: 

- Amazon RDS (Relational Database Service)

- Banco de dados relacional gerenciado.

- O controle de estoque de medicamentos e o registro de clientes serão armazenados no Amazon RDS. Manter um banco de dados local exige custos, infraestrutura e profissionais dedicados apenas à manutenção. O RDS automatiza essas tarefas de administração. O custo reduzido vem da economia de horas de trabalho da equipe de TI, que pode focar em melhorar as vendas, e na eliminação da necessidade de comprar servidores de banco de dados.


## Conclusão

A implementação de ferramentas na empresa Abstergo Industries tem como esperado a redução imediata de custos operacionais e de infraestrutura, além de trazer alta disponibilidade para o sistema de vendas, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa, como a análise de dados do estoque no futuro.


## Anexos

Link de planilha de estimativa de custos: 

https://drive.google.com/file/d/1ccQ4poH5VwwcXaBDY897pHmfNp6KLEp3/view?usp=sharing


#### Assinatura do Responsável pelo Projeto:

                                                      Lucas Santos Pimentel
