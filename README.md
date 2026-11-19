# ErgoContexto

Triagem ergonômica e de fatores humanos, em um único `index.html` (sem build, sem dependências), com modo offline (PWA).

**Uso:** abrir o `index.html` publicado no GitHub Pages. Os dados ficam no navegador do aparelho (faça backup em *Histórico*).

## O que o app faz

- **5 domínios avaliados separadamente, sem nota total:** Ergonomia física, Ambiente, Carga cognitiva (grupo *Ergonomia*, foco em saúde) e Organização do trabalho e Trabalho prescrito × real (grupo *Fatores humanos*, foco em desempenho e segurança).
- Cada item tem 4 níveis com critério objetivo, a fonte do dado (observado, relatado, estimado) e observação.
- Nível por domínio pela média, com regra anti-diluição (um item Alto garante ao menos Alta) e "dados insuficientes" quando menos da metade foi avaliada.
- Prioridade sugerida pelo domínio mais crítico, elevada pela gravidade potencial quando os fatores humanos estão em Alta ou Crítica.
- Próximo passo por domínio na lógica SOBANE (Déparis → Observação → Análise → Perícia).
- Radar, mapa de itens, comparação com a avaliação anterior, relatório A4 para PDF.
- Plano de ação com hierarquia de controles, histórico, painel, exportação CSV/JSON e importação de backup.
- Análise por IA opcional (Worker no repositório `ergocontexto-ia`). A IA não altera pontuação nem classificação.

## Limites

É uma triagem. Os critérios são simplificados e não herdam a validade de RULA, REBA, NIOSH, OCRA, NASA-TLX, COPSOQ etc. Não substitui AET, avaliação quantitativa nem avaliação especializada.
