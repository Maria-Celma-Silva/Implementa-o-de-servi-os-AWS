# SERVIÇOS DA AWS
RELATÁRIO DE IMPLEMENTATAÇÃO DE SERVIÇOS AWS


Data: 18-07-2026
Empresa: Abstergo Industries 
Responsável: Celma Silva 

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Celma Silva. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:


Etapa 1: 
-  Nome da ferramenta: Amazon S3 (focado na classe S3 Intelligent-Tiering) 
- Foco da ferramenta: Armazenamento de objetos em nuvem e gerenciamento automático do ciclo de vida de arquivos. 
- Descrição de caso de uso: Armazenamento de dados não estruturados, como data lakes, mídias e backups. O uso específico do S3 Intelligent-Tiering otimiza custos automaticamente para dados com padrões de acesso desconhecidos ou em alteração, movendo os arquivos menos acessados para camadas mais baratas, cobrando apenas uma pequena taxa de monitoramento

  
Etapa 2:
- Nome da ferramenta: Amazon Aurora (através do Amazon RDS) 
- Foco da ferramenta: Banco de dados relacional gerenciado, de alta performance e baixo custo (opção Serverless). 
Descrição de caso de uso: Substituição de licenças caras de bancos de dados comerciais que suportam os sistemas transacionais da empresa. O Amazon Aurora entrega mecanismos compatíveis com PostgreSQL e MySQL custando o equivalente a 1/10 do preço de outros vendors do mercado, reduzindo drasticamente os gastos com licenciamento e manutenção de hardware.


Etapa 3:
Nome da ferramenta: Amazon DynamoDB 
Foco da ferramenta: Banco de dados não relacional (NoSQL) totalmente gerenciado e elástico. 
Descrição de caso de uso: Estruturação de dados que exigem baixíssima latência (performance abaixo de 10 milissegundos) e alto volume de acessos. Por ser um serviço Serverless que escala automaticamente, a empresa elimina o custo com servidores ociosos, pagando apenas pelo poder computacional de leitura e gravação que o negócio efetivamente consumir. 

Conclusão
A implementação de ferramentas na empresa Abstergo Industries tem como esperado a redução direta de custos de infraestrutura e o alinhamento das soluções técnicas às necessidades reais do negócio, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos
Apresentação Base: "Armazenamento e Bancos de Dados”.pdf

 
Assinatura do Responsável pelo Projeto:
Celma Silva 
