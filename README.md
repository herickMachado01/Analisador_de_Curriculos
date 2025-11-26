Analisador de Currículos com n8n + IA (Groq + LLaMA)
Automação completa para análise inteligente de currículos

📌 Descrição do Projeto

Este projeto é um fluxo n8n totalmente automatizado para análise de currículos usando IA (LLaMA 3.3 70B via Groq), extração de dados de PDFs e gravação em Google Sheets.

Ele permite que qualquer pessoa envie um PDF de currículo, e o sistema faz automaticamente:

✨ Extrai o texto do arquivo
✨ Identifica o nome do candidato
✨ Gera uma análise qualitativa profissional
✨ Determina se o candidato combina com a vaga (match)
✨ Limpa o texto com JavaScript para entregar só o essencial
✨ Salva tudo automaticamente em uma planilha Google Sheets

Ideal para automatizar recrutamento, triagem e avaliações técnicas.

🚀 Funcionalidades Principais
Função	Descrição
📥 Form Trigger	Recebe Nome + PDF do currículo
📄 Extração do PDF	Converte PDF para texto
🧠 Análise com IA (Groq LLaMA)	Gera resumo + avaliação profissional
🎯 Verificação de Match	Retorna { "match": true/false }
🧹 Limpeza do Output com JavaScript	Extrai só o nome e o resumo limpo
📊 Envio para Google Sheets	Salva automaticamente Nome, Match e Resumo
🔗 Tudo no mesmo fluxo do n8n	Fácil de importar, fácil de editar


Tecnologias Utilizadas

n8n (Cloud / Self-hosted)

Groq API – LLaMA 3.3 70B

Google Sheets API

JavaScript (para limpeza e manipulação do output)

Extract From File (PDF → Texto)
