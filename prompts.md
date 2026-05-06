# Registro de Engenharia de Prompts e Raciocínio de Auditoria

Este documento detalha a estratégia de interação com a IA (NotebookLM) para a extração de inteligência jurídica e normativa aplicada ao setor condominial.

## 1. Metodologia: Jornada de Refinamento

O processo de consulta foi dividido em duas etapas para garantir a precisão dos dados:

1. **Pesquisa Exploratória (Gemini):** Identificação da legislação base e marcos regulatórios.
2. **Análise de Profundidade (NotebookLM):** Aplicação de prompts especializados sobre fontes curadas para garantir o rigor técnico (Código Civil, Atas e Convenções) para evitar alucinações e focar na base documental.

---

## 2. Prompts Estratégicos e Evolução

### Caso 1: Ciclo de Vida Legal e Instalação
* **Prompt Inicial:** "Quais leis regram o condomínio do projeto até a instalação?"
* **Prompt Otimizado (Consultoria):** *"Atue como um Consultor Jurídico Imobiliário. Liste cronologicamente a legislação aplicada, da Lei de Incorporações (4.591/64) ao Código Civil (Art. 1.331 a 1.358). Destaque pontos críticos de conformidade na transição da obra para a gestão condominial."*
* [cite_start]**Raciocínio:** Definir uma persona técnica obriga a IA a adotar um tom formal e estruturado, essencial para relatórios de auditoria[cite: 14].

### Caso 2: Auditoria de Descumprimento de Ata
* **Prompt Inicial:** "O que fazer se o síndico não cumpre a ata?"
* **Prompt Otimizado (Auditoria de Compliance):** *"Simule um cenário de descumprimento de deliberação aprovada. Com base no Art. 1.348 do CC, detalhe as medidas progressivas: da notificação extrajudicial à convocação por 1/4 dos condôminos. Explique as teses de 'culpa in vigilando' e 'in eligendo' no caso de falhas da administradora."* 
* **Raciocínio:** Injetar termos jurídicos específicos (teses de culpa) direciona a IA para uma resposta de nível especialista, útil para fundamentar ações reais.

---

## 3. "Cicatrizes" e Troubleshooting (Solução de Problemas)
Durante o desenvolvimento do caderno temático, observou-se:
* **Desafio:** A IA tendia a generalizar prazos de guarda documental.
* **Solução:** Foi necessário fornecer a fonte do **Art. 206 do Código Civil** e solicitar uma tabela de temporalidade específica para auditoria financeira (5 anos) versus documental (permanente).
