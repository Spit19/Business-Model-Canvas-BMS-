# AI Business Architect Platform

Este repositório contém a documentação arquitetural de uma plataforma de
análise inteligente de modelos de negócio baseada no Business Model Canvas (BMC),
desenvolvida como parte de um estágio supervisionado em Engenharia de Software.

## 📌 Objetivo
Projetar uma arquitetura escalável baseada em microsserviços e IA generativa
para análise estratégica de modelos de negócio.

## 🧱 Arquitetura
A solução utiliza:
- Microsserviços
- Processamento assíncrono
- Integração com LLMs
- RAG (Retrieval-Augmented Generation)

Os diagramas estão disponíveis na pasta `docs/diagramas`.

## 📄 Documento de Arquitetura de Software (DAS)
O DAS está disponível em:
- `docs/DAS.md`

## 🛠️ Serviços e a Stack tecnológica
- API Gateway (Node.js)
- Canvas Service (Spring Boot)
- Intelligence Service (FastAPI + LLM)
- Market Data Service (Node.js)
- RabbitMQ, PostgreSQL, Redis
- Docker e Kubernetes

## ⚠️ Observação
Este projeto possui foco em **arquitetura e design**, não sendo uma implementação
completa de software.
