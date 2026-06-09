# Cenário: Empresa de E-commerce

## Objetivo

Demonstrar a utilização dos serviços AWS EC2, EBS, Snapshot, AMI, S3 e Elastic Load Balancer em um cenário corporativo de e-commerce.

## Arquitetura

A empresa hospeda sua aplicação web em uma instância Amazon EC2.

O Elastic Load Balancer distribui o tráfego dos usuários para a aplicação.

Os dados da aplicação são armazenados em um volume Amazon EBS.

Snapshots são criados periodicamente para backup dos dados.

O Amazon S3 é utilizado para armazenar backups e apoiar a recuperação de desastres.

Uma AMI padrão corporativa é criada para permitir o provisionamento rápido de novas instâncias EC2 em situações de escalabilidade ou recuperação.

## Benefícios

* Alta disponibilidade
* Backup e recuperação de dados
* Escalabilidade
* Continuidade do negócio

## Diagrama

![Arquitetura AWS] <img width="696" height="1714" alt="Cenário_ Empresa de E-commerce drawio" src="https://github.com/user-attachments/assets/6f9182b2-1dab-47cf-a4a6-d16a392951f1" />

