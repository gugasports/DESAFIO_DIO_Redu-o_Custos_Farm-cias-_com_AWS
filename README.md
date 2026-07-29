# DESAFIO DIO Redução de Custos em Farmácias com AWS
Desafio de projetos do Bootcamp Totvs, do módulo de Noções de Computação em nuvem.

# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 29/07/2026.

Empresa: Abstergo Industries 

Responsável: Gustavo Mateus

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Gustavo Mateus. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1: 
- Amazon S3 Intelligent-Tiering
- O foco é trazer um armazenamento inteligente de arquivos com otimização automática de custos.
- Como a indústria farmacêutica apresenta uma enorme quantidade de documentos como exames, certificados, relatórios, backups, registros de qualidade, imagens e outros, sabemos que grande parte desses arquivos acabam não sendo acessadas de forma tão frequente. Com essa ferramenta conseguimos armazenar os dados de diferentes classes e nesse modo, o "Intellingent-Tiering" move automaticamente os arquivos para camadas mais baratas conforme seu acesso, reduzindo os custos de gerenciamento manual.

Etapa 2: 
- Amazon EC2 Auto Scaling
- Para gerenciar melhor os custos, essa ferramenta faz a escalabilidade automática dos servidores.
- O EC2 Auto Scaling aumenta ou diminui automaticamente a quantidade de instâncias conforme o uso, então como o pagamento acaba sendo pelo necessário, tenho menor consumo de CPU e menos servidores ligados 

Etapa 3: 
- Amazon CloudFront
- Foco em distribuição de conteúdo com baixa latência, utilizando cache.
- Como a farmacêutica disponibiliza PDFs, catálogos, bulas e esses arquivos são acessados milhares de vezes, o Cloudfront mantém cópias em cache próximas dos usuários. Dessa forma acabam chegando menos requisições ao servidor não sendo necessário tanto processamento e consumo de banda e gerando melhor desempenho para os usuários.



## Conclusão
A implementação de ferramentas na empresa *Abstergo Industries tem como esperado redução de despesas com armazenamento de documentos e backups, custos com servidores ociosos, ajustando automaticamente a capacidade computacional e diminuindo o consumo de banda e processamento ao distribuir conteúdos estáticos por meio de cache o que aumentará a eficiência e a produtividade da empresa. 
Essa combinação demonstra uma estratégia de otimização em armazenamento, processamento e tráfego de rede, ajudando a reduzir custos operacionais de forma imediata sem comprometer a disponibilidade dos sistemas.
Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.


## Anexos

**S3 Intelligent-Tiering:** https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/intelligent-tiering-overview.html
                            https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/Welcome.html
                        
**EC2 Auto Scaling:**   https://aws.amazon.com/pt/ec2/autoscaling/

**Amazon CloudFront:**  https://docs.aws.amazon.com/pt_br/cloudfront/?icmpid=docs_homepage_networking


Assinatura do Responsável pelo Projeto:
**Gustavo Mateus**
