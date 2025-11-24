# 📘 Atividade: Análise de Infraestrutura Insegura com ValidIaC

Esta atividade tem como objetivo exercitar a análise de riscos em **Terraform** usando o **ValidIaC**, trabalhando em grupo para identificar e corrigir problemas reais de segurança, custos e confiabilidade.

---

## 🎯 Objetivo da atividade

* Identificar misconfigurations em Terraform
* Entender impacto real em Segurança, SRE e Custos
* Praticar colaboração em grupos usando o Microsoft Teams
* Analisar e corrigir infraestrutura antes do deploy (Shift Left)

---

## 🟪 1. Organização dos Grupos (Teams)

* Divisão em salas no Teams (4–6 alunos)
* Um aluno compartilha a tela
* Um lê o código
* Todos analisam riscos em conjunto

---

## 🟪 2. Código inseguro a ser analisado

Cada grupo recebe **1 arquivo Terraform inseguro**, como:

* Security Group com `0.0.0.0/0`
* S3 sem encryption e público
* EC2 sem IAM Role + SG padrão
* RDS sem backup ou sem storage encryption

---

## 🟪 3. Análise no ValidIaC

Acessem: **[https://validiac.com](https://validiac.com)**

Cada grupo deve avaliar:

* 🔍 **Validate:** erros e misconfigurations
* 🔐 **Security:** alertas críticos
* 💰 **Cost:** possíveis custos inesperados
* 🗺️ **Map:** dependências do recurso

Discutam:

* Qual é o risco?
* O que pode dar errado?
* Como corrigir?

---

## 🟪 4. Apresentação dos grupos

De volta à sala principal:

* Cada grupo apresenta o que foi identificado:

  * Qual foi o risco mais crítico que encontraram?
  * Qual seria o impacto real em produção?
  * A correção foi simples ou complexa?
---

---

## 🟪 5. Principais aprendizados (Takeaways)

* Segurança não é só ferramenta, é impacto no negócio
* Problemas pequenos de IaC viram incidentes reais
* SRE sofre quando IaC é inseguro
* Shift Left evita riscos, custos e retrabalho
* ValidIaC + Terraform = prevenção antes do deploy

---
