# Projeto de Arquitetura AWS - EC2 com EBS para Bootcamp da DIO

Este projeto apresenta uma arquitetura na AWS utilizando **EC2** e volumes **EBS**, com foco em um cenário de **processamento e armazenamento de imagens médicas**.

---

## Descrição

- **Usuários**: acessam a aplicação via navegador.
- **Application Load Balancer**: distribui o tráfego entre instâncias EC2.
- **EC2 (Servidor de Aplicação)**: processa as requisições e conecta aos serviços.
- **EBS Volumes**:
  - Raw Data → armazena arquivos originais
  - Processed Data → armazena arquivos processados
  - Logs & Auditoria → armazena registros e trilhas de auditoria
- **RDS**: banco de dados para metadados dos exames.

---
