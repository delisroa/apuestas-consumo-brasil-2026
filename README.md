# ¿Menos apuestas, más compras?
## Análisis de ventas en supermercados de Brasil — 2026

### Objetivo

Investigar si existe una relación entre las restricciones a las plataformas de apuestas online en Brasil y las variaciones en las ventas de supermercados durante agosto y octubre de 2026.

### Contexto

El 25 de septiembre de 2026 entraron en vigor restricciones a las apuestas de cuota fija en Brasil, y el 6 de octubre se estableció el cierre de los sitios y aplicaciones.

Este proyecto analiza los datos de ventas antes y después de esas fechas para observar posibles cambios en el comportamiento del sector.

### Herramientas utilizadas

- Python
- Pandas
- Matplotlib
- Google Colab
- Estadística descriptiva

### Metodología

Se analizaron 12 semanas de variaciones interanuales de ventas en valor, utilizando información de NielsenIQ y la Asociación Brasileña de Supermercados (ABRAS).

Los datos se organizaron en tres períodos: antes de las restricciones, transición y después.

Se calcularon estadísticas descriptivas y se construyeron gráficos para comparar la evolución de las ventas.

### Resultados principales

| Período | Crecimiento promedio |
|---|---:|
| Antes | 4,38 % |
| Transición | 1,05 % |
| Después | 7,35 % |

El promedio posterior fue 2,97 puntos porcentuales superior al anterior.

Sin embargo, antes de las restricciones ya existían semanas con crecimientos similares o superiores.

### Conclusión

Los resultados muestran un aumento del crecimiento promedio de las ventas durante las dos semanas posteriores analizadas, pero no permiten demostrar que haya sido causado por la prohibición de las apuestas.

La muestra es limitada y sería necesario incorporar más semanas y otras variables económicas para obtener conclusiones más sólidas.

### Código y análisis

[Ver notebook de Google Colab](Analisis_Apuestas_Consumo_Brasil_2026_Revision.ipynb)

### Fuentes

- [ABRAS / NielsenIQ — Monitoreo semanal de 2026](https://www.abras.com.br/economia-e-pesquisa/monitoramento-semanal-nielseniq-e-abras/2026)
- [Informe NielsenIQ / ABRAS, semana 42](https://static.abras.com.br/pdf/monitoramento-semanal-niq/semana-4226.pdf)
- [Ministerio de Hacienda de Brasil — Medida Provisional 1.394/2026](https://www.gov.br/fazenda/pt-br/composicao/orgaos/secretaria-de-premios-e-apostas/medida-provisoria-ndeg-1-394-2026-entenda-as-novas-regras-para-as-apostas-de-quota-fixa)

---

**Proyecto personal de portafolio — Data Science | Delis Roa**
