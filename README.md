🌟 Analisador de Currículos — Automação com n8n + IA (Groq + LLaMA)
Sistema automático de triagem e análise profissional de currículos
📌 Descrição

Este projeto é um fluxo completo criado no n8n para automatizar o processo de análise de currículos enviados em PDF.
Ele utiliza IA (LLaMA 3.3 70B via Groq) para extrair informações, gerar um resumo profissional, identificar o nome do candidato e avaliar se ele combina com a vaga (match).

Todo o resultado é enviado automaticamente para uma planilha no Google Sheets.

O objetivo é facilitar a triagem de candidatos na área de Desenvolvimento de Software (Python), deixando o processo mais rápido, inteligente e organizado.

🚀 Funcionalidades do Projeto
Função	O que faz
📥 Form Trigger	Recebe o nome do candidato + currículo PDF
📄 PDF Extract	Extrai o texto do currículo automaticamente
🧠 IA com Groq (LLaMA 3.3 70B)	Faz análise completa e gera resumo
🎯 Match da Vaga	IA retorna { "match": true/false }
🧹 JavaScript de Limpeza	Separa nome + resumo sem o prompt
📊 Google Sheets	Registra Nome, Match e Resumo automaticamente
🔄 Fluxo 100% automatizado	Nenhuma intervenção manual necessária
🛠 Tecnologias Utilizadas

n8n (Automação)

Groq API – LLaMA 3.3 70B

Google Sheets API

Extract From File (PDF → texto)

JavaScript para limpeza e formatação do output
