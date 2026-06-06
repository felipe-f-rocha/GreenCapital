# Caso Balmoral — VerdeCapital

**Languages:** [Español](README.md) · [English](README_en.md) · [Português](README_pt.md)

**Proyecto:** CopernicusLAC Panamá Hackathon 2026 — Seguridad alimentaria

**Descripción:** Caso de uso que muestra cómo VerdeCapital estructuró un crédito verde de $2.4M USD para la Finca Balmoral (Chiriquí, Panamá) usando datos satelitales Copernicus (Sentinel‑2, Sentinel‑3, ERA5) como colateral tecnológico para fortalecer la seguridad alimentaria.

**Resumen rápido**
- **Sector:** Agro — Banano
- **Ubicación:** Chiriquí, Panamá
- **Crédito estructurado:** $2.400.000 USD (7 años, 6.8% APR)
- **Área monitoreada:** 1.800 ha
- **Reducción de agua verificada:** 41%
- **Payback estimado:** 3.2 años

**Problema**
- **Causa principal:** Sistemas de riego convencionales con alto consumo de agua y diésel.
- **Riesgo financiero:** Los bancos rechazaban el préstamo por falta de garantías verificables y datos objetivos.

**Solución propuesta**
- **Diagnóstico satelital:** Series temporales Sentinel‑2 (NDVI, NDWI) y Sentinel‑3 (LST) para crear un Reporte de Salud de Finca.
- **Crédito verde condicionado:** Desembolsos vinculados a métricas trimestrales verificadas por satélite.
- **Plataforma de monitoreo:** Dashboard integrado con la API de VerdeCapital y Copernicus, con actualización cada ~10 días.

**Implementación y cronograma**
- Ago 2024 — Diagnóstico satelital inicial (36 meses de datos).
- Sep 2024 — Estructuración y aprobación del crédito (48 h).
- Oct–Dic 2024 — Instalación de riego por goteo y sensores IoT (1.200 ha).
- Ene 2025 → — Monitoreo continuo y generación de bonos de carbono.

**Tecnología y datos**
- **Sentinel‑2 MSI:** NDVI, NDWI y clasificación de cultivos (10 m).
- **Sentinel‑3 SLSTR:** Temperatura superficial terrestre (LST).
- **ERA5 (CDS):** Reanálisis climático para modelar demanda hídrica.
- **Integración:** API VerdeCapital ↔ Copernicus Dataspace Ecosystem.

**Resultados financieros clave**
- **Ahorro operacional anual proyectado:** +$512,600 (combustible, agua, mantenimiento, bonos).
- **Beneficio total frente a tasa convencional:** +$604,000 (incluye deducción fiscal Ley 37/2016).

**Impacto social y ambiental**
- **Agua ahorrada por ciclo:** ~172.000 m³
- **Emisiones evitadas (CO₂):** 1.240 t/año (certificable)
- **Empleo rural asegurado:** 340 empleos directos
- **Potencial de replicación:** 120+ productores en Panamá

**Cómo replicar**
1. Recopilar 24–36 meses de imágenes Sentinel‑2 para la finca.
2. Calcular indicadores: NDVI, NDWI, LST y clasificar lotes.
3. Generar el Reporte de Salud de Finca y presentarlo al comité crediticio.
4. Estructurar el crédito con métricas verificables y dashboard de seguimiento.

**Fuente:** [caso-balmoral.html](caso-balmoral.html)

---
*Resumen generado a partir del contenido de `caso-balmoral.html`; versión principal en español para el CopernicusLAC Panamá Hackathon 2026 — Seguridad alimentaria.*
