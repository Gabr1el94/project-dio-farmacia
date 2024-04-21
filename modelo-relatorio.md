# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 04/05/2024
Empresa: Abstergo Industries 
Responsável: Gabriel Soares

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa [nome da empresa], realizado por [nome do responsável pelo projeto]. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1: 
- Amazon EC2 (Elastic Compute Cloud)
- Oferece capacidade de computação escalável na nuvem.
- Caso de Uso
  
  Identificação de Instâncias Ociosas: Use o AWS Cost Explorer Resource Optimization para identificar instâncias do EC2 com baixa utilização ou ociosas. Você pode reduzir custos interrompendo ou ajustando os recursos dessas instâncias.
  
  Redimensionamento Automático: O AWS Operations Conductor pode redimensionar automaticamente as instâncias do EC2 com base nas recomendações do Cost Explorer.
  
  Instâncias Spot: Considere usar Instâncias Spot para economizar até 90% em comparação com instâncias sob demanda.  

Etapa 2: 
- Amazon RDS (Relational Database Service)
- Fornece bancos de dados gerenciados.
- Caso de Uso
    Escolha de Tipo de Instância: Use o AWS Compute Optimizer para examinar recomendações 
    de tipo de instância além do downsizing. Isso pode ajudar a otimizar os custos do RDS.

    Elastic Beanstalk: Considere usar o AWS Elastic Beanstalk para aplicativos web. Ele gerencia a infraestrutura subjacente, permitindo que você se concentre no desenvolvimento de software e economize em custos de gerenciamento.

Etapa 3: 
- Amazon S3 (Simple Storage Service)
- Armazenamento de objetos escalável.
- Caso de Uso

    Compartilhamento de Recursos: Compartilhe recursos entre contas da AWS usando o Amazon S3. 
    Isso pode reduzir custos e otimizar a utilização.

    Exclusão de Recursos Órfãos: Acompanhe e elimine recursos órfãos, como discos, IPs 
    e snapshots, para evitar custos desnecessários3.

## Conclusão
A implementação de ferramentas na empresa Abstergo Industries tem como esperado Amazon EC2, Amazon RDS e Amazon S3, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos

Amazon EC2:  https://docs.aws.amazon.com/ec2/;
Amazon RDS:  https://docs.aws.amazon.com/pt_br/AmazonRDS/latest/UserGuide/Welcome.html;
Amazon S3:   https://docs.aws.amazon.com/s3/;

Assinatura do Responsável pelo Projeto:

Gabriel Soares