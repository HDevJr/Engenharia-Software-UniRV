# Metodologia de Estudo e Documentação

Este documento define como o repositório é mantido ao longo do curso, garantindo padronização, rastreabilidade e evolução.

## 1) Fluxo de estudo (por aula / semana)

### A) Antes da aula (preparação mínima)
- Revisar rapidamente o conteúdo anterior (5–15 min)
- Preparar dúvidas e tópicos que quero confirmar
- Criar uma seção “Perguntas” no arquivo da disciplina (quando aplicável)

### B) Durante a aula (captura)
- Registrar tópicos principais e termos-chave
- Capturar exemplos importantes
- Marcar pontos de incerteza para revisar depois

### C) Após a aula (consolidação)
- Reescrever o conteúdo com minhas palavras
- Criar exemplos próprios
- Resolver exercícios e registrar:
  - tentativa
  - erro
  - correção
  - explicação

## 2) Padrão por disciplina

Cada disciplina mantém a estrutura:

- `README.md`  
  Objetivo, ementa pessoal (com minhas palavras), visão geral e mapa de tópicos.

- `01-fundamentos-teoricos/`  
  Conceitos base, definições, intuição, notas de aula.

- `02-conceitos-e-modelos/`  
  Modelos, formalizações, diagramas, comparações, trade-offs.

- `03-exercicios-e-listas/`  
  Listas, questões e resoluções (com comentários).

- `04-implementacoes-praticas/`  
  Código, experimentos, repositórios mínimos dentro do repositório.

- `05-conexoes-com-ia.md`  
  Relação com IA/ML/DL: por que importa, onde aparece, o que habilita.

- `06-reflexoes-criticas.md`  
  Limitações, o que ficou difícil, o que precisa de revisão, insights.

- `referencias.md`  
  Bibliografia e links (quando houver), com padrão de citação.

## 3) Diretrizes de escrita

- Escrever como documentação técnica: claro, verificável e revisável.
- Sempre que possível, incluir:
  - definição curta
  - intuição
  - exemplo
  - implicação prática
- Evitar “copiar e colar” de materiais (usar paráfrase e citar referências).

## 4) Diretrizes para código e experimentos

- Preferência: **Python**
- Organização sugerida dentro de `04-implementacoes-praticas/`:
  - `python/` (código principal)
  - `notebooks/` (somente quando fizer sentido)
  - `datasets/` (apenas amostras pequenas ou link para fonte)
- Todo experimento deve ter:
  - objetivo
  - hipótese
  - procedimento
  - resultado
  - interpretação

## 5) Versionamento (Git)

Regras sugeridas:
- Commits pequenos e frequentes
- Mensagens claras, ex.:
  - `docs: adicionar fundamentos de álgebra linear (vetores e normas)`
  - `feat: implementar perceptron do zero`
  - `fix: corrigir exercício 3 (erro de sinal)`
- Tags por marcos (opcional):
  - `v1.0-fim-1o-periodo`

## 6) Revisão e manutenção

Semanal:
- revisar tópicos da semana
- atualizar `README.md` da disciplina (mapa de tópicos)
- registrar pendências e dúvidas

Mensal:
- revisar “lacunas”
- reforçar conexões com IA