# Relatório
O relatório é a prova de que o trabalho teve resultados e que são relevantes.
O relatório técnico transforma os dados em decisões.


## Elementos
Estrutura padrão de um relatório técnico.

### Capa
Identificação do cliente, escopo, data e classificação de confidencialidade.

### Sumário Executivo
Resumo para leitores não técnicos.
(máximo 1 página)

### Escopos e Metodologia
O que foi testado, o que ficou fora, como foi feito e base legal e ética.

### Achados
A parte principal do relatório, documentando cada achado.

### Conclusões e Mitigações
Recomendações do que deve ser feito sobre os achados.


## Achados
Possui seis campos:
- Título
    Nome curto e descritivo que resume o achado.
- Descrição Técnica
    O que é, como foi encontrado e o contexto técnico.
- Evidência
    Imagem ou output que comprova o achado. (_importante_)
- Impacto
    Perdas potenciais para o negócio: reputação, LGPD, operação e financeiro.
- Severidade
    Classificação do risco: baixo, médio, alto ou crítico, baseada no impacto real.
- Mitigação
    Ação detalhada, específica e aplicável para eliminar ou reduzir o risco.


## Severidade de impacto
Classificação baseada no impacto real

### Baixo
Informação útil para o atacante, sem impacto direto imediato
Ex.: versão do servidor HTTP revelada.

### Médio
Risco real, impacto limitado ou condicionado.
Ex.: dados de contato expostos no WHOIS.

### Alto
Impacto significativo na operação ou reputação.
Ex.: acesso não autorizado a sistemas.

### Crítico
Comprometimento total ou perda de dados sensíveis de terceiros.
Ex.: RCE, exfiltração de dados
