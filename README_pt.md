# Caso Balmoral — VerdeCapital

**Projeto:** CopernicusLAC Panamá Hackathon 2026 — Segurança alimentar

**Descrição:** Caso de uso que mostra como a VerdeCapital estruturou um crédito verde de $2,4M USD para a Finca Balmoral (Chiriquí, Panamá) usando dados satelitais Copernicus (Sentinel‑2, Sentinel‑3, ERA5) como garantia tecnológica para fortalecer a segurança alimentar.

**Resumo rápido**
- **Setor:** Agro — Bananas
- **Local:** Chiriquí, Panamá
- **Crédito estruturado:** $2.400.000 USD (7 anos, 6,8% APR)
- **Área monitorada:** 1.800 ha
- **Redução de água verificada:** 41%
- **Payback estimado:** 3,2 anos

**Problema**
- **Causa principal:** Sistemas de irrigação convencionais com alto consumo de água e diesel.
- **Risco financeiro:** Os bancos rejeitavam o financiamento por falta de garantias verificáveis e dados objetivos.

**Solução proposta**
- **Diagnóstico satelital:** Séries temporais Sentinel‑2 (NDVI, NDWI) e Sentinel‑3 (LST) para criar um Relatório de Saúde da Fazenda.
- **Crédito verde condicionado:** Desembolsos vinculados a métricas trimestrais verificadas por satélite.
- **Plataforma de monitoramento:** Painel integrado com a API VerdeCapital e Copernicus, atualizado a cada ~10 dias.

**Implementação e cronograma**
- Ago 2024 — Diagnóstico satelital inicial (36 meses de dados).
- Set 2024 — Estruturação e aprovação do crédito (48 h).
- Out–Dez 2024 — Instalação de irrigação por gotejamento e sensores IoT (1.200 ha).
- Jan 2025 → — Monitoramento contínuo e geração de créditos de carbono.

**Tecnologia e dados**
- **Sentinel‑2 MSI:** NDVI, NDWI e classificação de cultivos (10 m).
- **Sentinel‑3 SLSTR:** Temperatura de superfície terrestre (LST).
- **ERA5 (CDS):** Reanálise climática para modelar demanda hídrica.
- **Integração:** API VerdeCapital ↔ Copernicus Dataspace Ecosystem.

**Resultados financeiros principais**
- **Economia operacional anual projetada:** +$512.600 (combustível, água, manutenção, créditos).
- **Benefício total frente à taxa convencional:** +$604.000 (inclui dedução fiscal da Lei 37/2016).

**Impacto social e ambiental**
- **Água economizada por ciclo:** ~172.000 m³
- **Emissões evitadas (CO₂):** 1.240 t/ano (verificável)
- **Empregos rurais assegurados:** 340 empregos diretos
- **Potencial de replicação:** 120+ produtores no Panamá

**Como replicar**
1. Coletar 24–36 meses de imagens Sentinel‑2 para a fazenda.
2. Calcular indicadores: NDVI, NDWI, LST e classificar lotes.
3. Gerar o Relatório de Saúde da Fazenda e apresentá-lo ao comitê de crédito.
4. Estruturar o crédito com métricas verificáveis e um painel de monitoramento.

**Fonte:** [caso-balmoral.html](caso-balmoral.html)

---
*Gerado a partir do conteúdo de `caso-balmoral.html`; versão em português para o CopernicusLAC Panamá Hackathon 2026 — Segurança alimentar.*
