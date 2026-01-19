# Santander-2025_Reducao_Custos_Farmacia

# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 19012026
Empresa: Abstergo Industries 
Responsável: Daniel M Nachmanowicz

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Daniel Nachmanowicz. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1: 
- **Nome da ferramenta:** Amazon EC2 (Elastic Compute Cloud)
- **Foco da ferramenta:** Computação em Nuvem e Servidores Virtuais
- **Descrição de caso de uso:** Migração dos servidores físicos antigos da Abstergo para instâncias virtuais na nuvem. Isso elimina o custo de manutenção de hardware on-premise e permite o uso de "Auto Scaling", ajustando a capacidade computacional conforme a demanda de pedidos das farmácias, garantindo que a empresa pague apenas pelo que utilizar.

Etapa 2: 
- **Nome da ferramenta:** Amazon S3 (Simple Storage Service)
- **Foco da ferramenta:** Armazenamento de Objetos e Arquivamento
- **Descrição de caso de uso:** Armazenamento seguro e de baixo custo para o grande volume de notas fiscais, documentos regulatórios e mídias de marketing dos produtos farmacêuticos. Utilizaremos a classe "S3 Intelligent-Tiering" para mover automaticamente dados antigos para camadas mais baratas, otimizando os custos de retenção de dados a longo prazo.

Etapa 3: 
- **Nome da ferramenta:** Amazon RDS (Relational Database Service)
- **Foco da ferramenta:** Banco de Dados Relacional Gerenciado
- **Descrição de caso de uso:** Implementação de um banco de dados gerenciado para controlar o estoque e a logística de distribuição. O RDS automatiza tarefas pesadas como backups, atualizações de software e segurança (patches), liberando a equipe de TI da Abstergo para focar na lógica do negócio e reduzindo custos operacionais com administração de banco de dados.



## Conclusão
A implementação de ferramentas na empresa Abstergo Industries tem como esperado a redução drástica de custos com hardware físico (CAPEX) e manutenção operacional (OPEX), além de prover alta disponibilidade para o sistema de distribuição, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos

- Planilha de estimativa de custos (AWS Calculator)
- Diagrama da arquitetura proposta
- Documentação de segurança e conformidade da AWS

Assinatura do Responsável pelo Projeto:

Daniel M Nachmanowicz
