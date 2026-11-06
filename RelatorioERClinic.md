# Relatório – Tecnologias Inteligentes Aplicadas à Saúde (ERClinic)

## 1. Introdução

A apresentação da ERClinic demonstrou como a Inteligência Artificial pode melhorar a rotina de clínicas e consultórios. As aplicações apresentadas buscam automatizar tarefas, organizar informações e apoiar os profissionais, sem substituir a avaliação humana.

## 2. Técnicas de IA e aplicações

Foram apresentadas diferentes técnicas, escolhidas conforme o problema:

- **Machine Learning supervisionado e XGBoost:** analisam dados históricos e estimam a probabilidade de um paciente não comparecer à consulta. O modelo considera informações como histórico de faltas, convênio, dia e horário do agendamento.
- **LLMs e Prompt Engineering:** organizam informações e geram textos estruturados. São utilizadas, por exemplo, no registro das consultas e na criação de resumos do prontuário.
- **Speech-to-Text:** transforma o áudio da consulta em texto, que depois pode ser organizado pela LLM em campos do prontuário, como evolução, hipótese diagnóstica, medicações e plano de tratamento.
- **IA multimodal e OCR:** interpretam exames enviados em imagens ou PDFs, extraem informações e ajudam a identificar resultados fora dos valores de referência.
- **RAG (Retrieval-Augmented Generation):** permite consultar documentos, protocolos e diretrizes da própria clínica para fornecer respostas contextualizadas. É utilizada no copiloto clínico Córtex.
- **Automação com n8n e integração por APIs:** conectam etapas e serviços, como no chatbot de agendamento pelo WhatsApp.

A apresentação também mencionou uma proposta de uso de IA para identificar regiões de interesse em imagens de exames de colposcopia.

## 3. Responsabilidade e limites

A IA analisa, organiza, sugere e agiliza processos, mas a decisão e a responsabilidade continuam sendo do profissional de saúde. Como os modelos podem errar ou reproduzir vieses, é importante manter a supervisão humana.

Também foram destacados os mecanismos de controle (*Guardrails*), a rastreabilidade das informações e a proteção dos dados dos pacientes, que são dados pessoais sensíveis e devem ser tratados conforme a LGPD.

## 4. Conclusão

A apresentação mostrou que a IA vai além dos chatbots e dos modelos de linguagem. Técnicas como Machine Learning, OCR, reconhecimento de fala e IA multimodal podem ser combinadas para resolver diferentes problemas da área da saúde.

O principal objetivo dessas aplicações é reduzir tarefas repetitivas, aumentar a eficiência das clínicas e devolver tempo ao profissional para que ele possa se dedicar mais ao paciente, mantendo a avaliação humana como parte essencial do atendimento.
