# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 10/09/2024  
Empresa: Abstergo Industries  
Responsável: Rodrigo Silva  

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Rodrigo Silva. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1: 
- Amazon EC2 (Elastic Compute Cloud)
- Otimização de infraestrutura com servidores escaláveis.
- A Abstergo Industries, que opera como hub de distribuição, utiliza servidores físicos em datacenters locais, o que gera altos custos de manutenção e upgrades de hardware. Com a migração para o Amazon EC2, a empresa conseguirá reduzir esses custos ao usar instâncias sob demanda e escalabilidade automática, ajustando o poder de processamento conforme a demanda de tráfego, principalmente em momentos de alta demanda logística.

Etapa 2: 
- Amazon S3 (Simple Storage Service)
- Armazenamento seguro e de baixo custo para grandes volumes de dados.
- A empresa precisa armazenar grandes volumes de dados de inventário, pedidos e informações dos produtos distribuídos. O uso do Amazon S3 permite o armazenamento de dados com alta durabilidade, ao mesmo tempo que reduz os custos com sistemas locais de armazenamento. Além disso, a política de armazenamento em camadas será implementada, para mover automaticamente os dados raramente acessados para classes de armazenamento mais econômicas.

Etapa 3: 
- AWS Lambda
- Redução de custos operacionais com processamento sob demanda sem servidor.
- Com a introdução do AWS Lambda, a Abstergo Industries passará a executar funções de forma assíncrona, eliminando a necessidade de manter servidores dedicados. Isso pode ser aplicado, por exemplo, ao processamento de dados de entrega e rastreamento de produtos, que agora serão realizados em segundos quando necessário, sem a necessidade de um servidor ativo 24/7, reduzindo os custos de operação e manutenção de infraestrutura.



## Conclusão
A implementação de ferramentas na empresa Abstergo Industries tem como esperado a redução de custos com infraestrutura, aumento de escalabilidade e agilidade nas operações, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos

[Guia de utilização do Amazon EC2](https://docs.aws.amazon.com/ec2/index.html)  
[Manual de políticas de armazenamento no Amazon S3](https://docs.aws.amazon.com/s3/)  
[Documentação AWS Lambda](https://docs.aws.amazon.com/lambda/index.html)  


Assinatura do Responsável pelo Projeto:

Rodrigo Silva
