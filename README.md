# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 13/07/2025

Empresa: Abstergo Industries

Responsável: Victor Andrade

# Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Victor Andrade. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar a diminuição de custos imediatos.

# Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:


# Etapa 1:

☁️ Amazon EC2 (Elastic Compute Cloud)
🛠 Serviço de computação que permite criar e gerenciar servidores virtuais (instâncias) sob demanda, substituindo servidores físicos locais.


✅ Vantagens:
Escalabilidade sob demanda (paga só pelo uso)

Elimina custos com compra e manutenção de hardware

Diversos tipos de instância para workloads diferentes (otimizados por memória, CPU, etc.)

Possibilidade de usar instâncias spot (até 90% mais baratas para tarefas tolerantes a interrupção)


💡 Aplicação:
Substitui os servidores locais da empresa usados para ERP, aplicações internas, etc


# Etapa 2:

🗄️ Amazon S3 (Simple Storage Service)
🛠 O que é:
Serviço de armazenamento escalável de objetos, ideal para backups, documentos, imagens, relatórios, arquivos legados etc.


✅ Vantagens:
Altamente durável e barato (99,999999999% de durabilidade)

Diversas classes de armazenamento para redução de custo (ex: S3 Standard, Infrequent Access, Glacier para arquivamento)

Elimina a necessidade de storage físico local

Cobrança baseada no uso (sem desperdício)


💡 Aplicação:
Armazenamento de arquivos de backup de banco de dados, documentos administrativos e históricos de medicamentos, por exemplo.


# Etapa 3:

🧠 AWS Lambda (Serverless Functions)
🛠 O que é:
Serviço de computação serverless, onde você executa código sem precisar manter servidores.


✅ Vantagens:
Custo zero quando não está executando

Ideal para tarefas pontuais, como processar uploads ou eventos

Elimina necessidade de servidores “ligados 24/7” para tarefas pequenas


💡 Aplicação:
Envio de relatórios automáticos, validações, notificações internas entre sistemas — com custo extremamente baixo.


## Conclusão
A implementação de ferramentas na empresa Abstergo Industries tem como esperado a redução de custos com tecnologias e mão de obra muito especializada, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos

| Serviço AWS    | O que substitui                 | Benefícios principais                      |
| -------------- | ------------------------------- | ------------------------------------------ |
| **Amazon EC2** | Servidores físicos on-premises  | Redução de CAPEX e escalabilidade          |
| **Amazon S3**  | Storages e backups locais       | Baixo custo, durabilidade e escalabilidade |
| **AWS Lambda** | Scripts e aplicações de rotina  | Serverless, custo sob demanda              |


# Assinatura do Responsável do Projeto:

Victor Andrade
