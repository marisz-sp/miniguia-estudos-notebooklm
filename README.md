# miniguia-estudos-notebooklm
# 📚 Miniguia de Estudos: Informática em Saúde & Saúde Digital

> Projeto prático desenvolvido para o Desafio de Projeto da DIO, aplicando **Inteligência Artificial (NotebookLM)** na curadoria, organização e síntese de conhecimento sobre Saúde Digital.

---

## 📌 Sumário
- [🎯 Contexto e Objetivos](#-contexto-e-objetivos)
- [🔗 Curadoria de Fontes](#-curadoria-de-fontes)
- [🛠️ Engenharia de Prompts e "Cicatrizes"](#️-engenharia-de-prompts-e-cicatrizes-troubleshooting)
- [📖 Miniguia de Estudo (Entrega Final)](#-miniguia-de-estudo-entrega-final)
  - [1. Resumo Estruturado](#1-resumo-estruturado-diferenciação-no-atendimento-à-distância)
  - [2. Glossário de Conceitos](#2-glossário-de-conceitos-fundamentais)
  - [3. Prompts Reutilizáveis](#3-conjunto-de-prompts-reutilizáveis)

---

## 🎯 Contexto e Objetivos

Este repositório documenta a construção de um **Caderno Temático** interativo focado na **Informática em Saúde** e na **Transformação Digital na Medicina**. 

O objetivo principal foi utilizar a IA como uma ferramenta de **aprendizagem ativa**, permitindo:
* Compreender como sistemas de informação suportam o cuidado ao paciente;
* Mapear padrões de interoperabilidade, segurança de dados e prontuários eletrônicos;
* Testar técnicas de **Engenharia de Prompts** para extrair análises precisas a partir de documentações técnicas.

---

## 🔗 Curadoria de Fontes

Para alimentar o NotebookLM e garantir um aprendizado embasado em materiais de referência, foram selecionadas as seguintes fontes:

1. 📄 **Saúde Digital e Informática em Saúde**: Visão geral dos conceitos fundamentais e impacto na gestão hospitalar.
2. 📄 **Diretrizes de Telemedicina e Telessaúde**: Documentação sobre regulamentação, monitoramento remoto e consultas digitais.
3. 📄 **Segurança e Proteção de Dados (LGPD/HIPAA)**: Normas de governança de dados sensíveis e cibersegurança em saúde.

---

## 🛠️ Engenharia de Prompts e "Cicatrizes" (Troubleshooting)

Durante o uso da IA, foram realizados experimentos com diferentes abordagens de perguntas para refinar o resultado:

### 🧪 Teste 1: Prompt de Glossário (Visão Geral)
> **Prompt:** *"Crie um glossário com a definição simples dos principais termos técnicos encontrados nas fontes para auxiliar nos estudos."*  
> **Resultado:** A IA extraiu com precisão 14 termos essenciais (PEP, Interoperabilidade, CDSS, HL7, IoT, Machine Learning, etc.).

---

### 🧪 Teste 2: Prompt de Comparação (Aprofundado)
> **Prompt:** *"Explique a diferença entre Telessaúde, Telemedicina e Teleconsulta com base nos documentos enviados."*  
> **Resultado:** A IA gerou uma distinção hierárquica clara (Telessaúde como o "guarda-chuva", Telemedicina como ferramenta de acompanhamento e Teleconsulta como a prestação do serviço).

---

### 💡 Cicatrizes e Aprendizados (Troubleshooting)
* **Desafio:** Termos como *Telessaúde* e *Telemedicina* frequentemente apareciam misturados ou usados como sinônimos genéricos nas fontes.
* **Ajuste:** Foi necessário forçar uma estrutura no prompt exigindo uma **diferenciação relacional** (conceito guarda-chuva vs. aplicação prática), eliminando ambiguidades conceituais.

---

## 📖 Miniguia de Estudo (Entrega Final)

### 1. Resumo Estruturado: Diferenciação no Atendimento à Distância

* **Telessaúde:** É o ecossistema e "guarda-chuva" conceitual. Engloba atendimento clínico, monitoramento remoto, gestão de dados, educação e treinamento de profissionais.
* **Telemedicina:** Ferramenta focada no acompanhamento clínico à distância, diagnósticos e otimização dos recursos médicos.
* **Teleconsulta:** Ato pontual da consulta médica/clínica realizada de forma remota entre o profissional e o paciente.

---

### 2. Glossário de Conceitos Fundamentais

* **IA (Inteligência Artificial):** Algoritmos e métodos matemáticos que analisam grandes volumes de dados para prever funções de proteínas ou detectar desperdícios na gestão.
* **Informática em Saúde:** Campo interdisciplinar que integra ciência da computação, da informação e da saúde para gerenciar dados e melhorar o atendimento.
* **Interoperabilidade:** Capacidade de diferentes sistemas comunicarem e compartilharem dados de forma contínua (sintática e semântica).
* **Padrão HL7 (Health Level 7):** Normas internacionais para comunicação eletrônica de dados clínicos entre computadores e instituições.
* **PEP / RES (Prontuário Eletrônico do Paciente / Registro Eletrônico de Saúde):** Versão digital e organizada do histórico clínico do paciente.
* **Saúde Digital:** Conceito amplo que envolve tecnologias móveis, IA, genômica e telessaúde para bem-estar individual e coletivo.
* **Sistemas de Apoio à Decisão Clínica (CDSS):** Ferramentas com algoritmos que fornecem recomendações em tempo real para personalizar decisões e aumentar a segurança.
* **Telemedicina / Telessaúde:** Uso de tecnologias de informação para oferecer consultas remotas, monitoramento e facilitação de acesso.
* **Realidade Virtual (RV) e Aumentada (RA):** Tecnologias imersivas para simulação cirúrgica, treinamentos e terapias motoras/fóbicas.
* **Big Data:** Análise de massas de dados para identificar tendências epidemiológicas, rastrear doenças e apoiar diagnósticos.
* **Cibersegurança:** Práticas e criptografia para proteger dados sensíveis de pacientes e algoritmos contra acessos não autorizados.
* **Governança de Dados:** Políticas para assegurar qualidade, privacidade e conformidade legal (ex: LGPD / HIPAA) das informações.
* **Internet das Coisas (IoT / IoMT):** Dispositivos conectados (*wearables*) que coletam dados de saúde em tempo real.
* **Machine Learning (Aprendizagem de Máquina):** Técnica de IA onde o sistema aprende automaticamente a partir de dados para criar modelos preditivos.

---

### 3. Conjunto de Prompts Reutilizáveis

Prompts prontos para serem salvos e reutilizados em revisões futuras:

1. 💬 *"Com base no histórico clínico do paciente, apresente um resumo em tópicos focando apenas em diagnósticos anteriores e medicações em uso."*
2. 💬 *"Sintetize os principais requisitos de conformidade da LGPD aplicados ao armazenamento de dados no PEP."*
3. 💬 *"Compare as vantagens da Interoperabilidade de sistemas em relação aos sistemas legados e isolados na gestão hospitalar."*
