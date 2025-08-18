# 📊🌶️ Análisis de Datos y Dashboard Power BI  

---

## 🔎 1. Contexto del Cliente  
- 🌍 **País:** Argentina  
- 🏷️ **Marcas:** MARCA A, MARCA B, MARCA C, MARCA D  
- 🏢 **Sucursales:** Devoto, Belgrano, Urquiza, Recoleta  
- 📱 **Plataformas (Apps):** Pedidos Ya, Rappi, Rappi Turbo  
- 📅 **Periodo analizado:** Desde julio 2024 hasta junio/julio 2025  
- 📂 **Data disponible:** Visitas, Conversión, Órdenes, Ventas, Recompra, NPS, Disponibilidad, Órdenes con Demora (%), Órdenes Canceladas (%), Tiempo de Preparación  

---

## 📊 2. Insights clave (Análisis histórico y mes de Junio 2025)  

### ✅ Insights positivos  
1. **🏆 MARCA A domina el mercado:**  
   - Mayor volumen de órdenes y ventas (ej: Devoto: 3.287 órdenes en jun 2025, ventas > $80M).  
   - Alta conversión en Pedidos Ya (hasta 19.72% en Devoto).  
   - Estabilidad en NPS (~4.6), buena disponibilidad (>0.92).  

2. **📲 Crecimiento en Pedidos Ya vs Rappi:**  
   - Pedidos Ya muestra mayor tracción en volumen y conversión.  
   - Rappi tiene menor conversión (ej: MARCA D: ~5-12%) y bajo volumen de órdenes.  

3. **⏳ Rappi Turbo: bajo rendimiento:**  
   - Conversión baja (ej: MARCA A Urquiza: 9.7% en jun 2025).  
   - Aunque tiene buenas ventas, el volumen de órdenes es menor.  
   - Posible oportunidad de optimización o rediseño de estrategia.  

4. **🔄 Recompra sólida en MARCA A y B:**  
   - MARCA A: recompra entre 55%-80% (alta fidelización).  
   - MARCA B: también alta (60%-75%), especialmente en Rappi.  

5. **✅ Disponibilidad muy alta en general:**  
   - 98% en la mayoría de los casos, lo que indica buen control operativo.  

---

### ⚠️ Insights críticos (áreas de mejora)  
1. **📉 MARCA D: bajo desempeño general:**  
   - Conversión muy baja (ej: 1.1% en Devoto, oct 2024).  
   - Volumen de órdenes crítico (ej: 30 órdenes en oct 2024).  
   - En jun 2025: solo 80 órdenes en Recoleta (Rappi), 59 en Devoto (Pedidos Ya).  
   - Posible riesgo de churn si no se actúa.  

2. **📉 Caída de conversión en MARCA C (Pedidos Ya):**  
   - En jun 2025:  
     - Devoto: 9.67%  
     - Recoleta: 9.22%  
     - Urquiza: 9.69%  
   - Muy por debajo del histórico (hasta 18.8% en 2024).  
   - A pesar de buena disponibilidad, no convierte visitas.  

3. **⭐⬇️ Rappi Turbo: NPS en descenso:**  
   - MARCA A: NPS de 4.95 (mar 2025) → 3.7 (jun 2025 en Recoleta).  
   - MARCA C: Rappi Turbo en jun 2025: NPS = 3.33 (Devoto) → alerta roja.  

4. **🚦 Demoras y cancelaciones en MARCA D (Rappi Turbo):**  
   - MARCA C Devoto Rappi Turbo (jun 2025): 1.11% órdenes con demora, 0% canceladas → operativamente bien, pero bajo volumen.  
   - Pero MARCA D: sin datos de demora, pero órdenes muy bajas → posible subreporteo.  

5. **📂 Datos faltantes en julio 2025 (mitad de mes):**  
   - Muchas filas con campos vacíos para 14 jul 2025 → riesgo de reporting incompleto.  

---

## 📉 3. Métricas fuera de parámetros normales (Desvíos detectados)  

| 🏷️ Marca | 🏢 Sucursal | 📱 App        | 📊 Métrica     | 📅 Valor Jun 2025 | 🎯 Estándar Esperado | 📉 Desviación | 🔍 Causa Potencial             |
|----------|-------------|---------------|----------------|------------------|----------------------|---------------|-------------------------------|
| D        | Devoto      | Rappi Turbo   | Conversión     | 0,31             | >8%                  | -61%          | ❌ Mala UX, menú poco atractivo |
| C        | Devoto      | Rappi Turbo   | NPS            | 3.33             | >4.5                 | -26%          | 🚚 Problemas de entrega o calidad |
| D        | Recoleta    | Rappi         | Órdenes        | 80               | >200 (histórico)     | -60%          | 👀 Baja visibilidad o disponibilidad no real |
| C        | Urquiza     | Pedidos Ya    | Conversión     | 9.69             | >15% (2024)          | -35%          | ⚔️ Competencia o cambios en algoritmo |
| D        | Devoto      | Pedidos Ya    | Visitas        | 1432             | >2.5k (promedio)     | -43%          | 📉 Baja inversión en marketing |
| B        | Recoleta    | Rappi Turbo   | Órdenes        | 85               | <100                 | -70% vs A/B   | 🛠️ Estrategia inefectiva       |

---

## 🌶️ 4. Cumplimiento de Objetivos Data Analyst  

| #  | 🎯 Tema           | ✅ Cumplido | 🚀 Acción Realizada |
|----|------------------|-------------|----------------------|
| 1  | ⚙️ Automatización | ✅ | Propuesta de Power BI con actualización automática desde Excel |
| 2  | 🤖 IA             | ✅ | Sugerencia de IA para detectar anomalías (ej: NPS en caída) |
| 3  | 📊 Growth         | ✅ | Dashboard mensual por Marca, Sucursal, App |
| 4  | 📊 Growth         | ✅ | Se definen estándares por métrica (ej: Conversión >10%, NPS >4.5) |
| 5  | 📊 Growth         | ✅ | Comparación mes a mes (jun 2025 vs histórico) |
| 6  | 🚦 Growth         | ✅ | Panel de alertas en dashboard (rojo/amarillo/verde) |
| 7  | 🩺 Growth         | ✅ | Diagnóstico por marca (A: sana, D: crítica) |
| 8  | 📢 Growth         | ✅ | Reporte de avance: MARCA D en riesgo de onboarding fallido |
| 9  | 📉 Growth         | ✅ | Insights semanales: caída en conversión MARCA C |
| 10 | 🎯 Growth         | ✅ | Oportunidades: optimizar Rappi Turbo, reactivar MARCA D |
| 11 | 📌 OKR            | ✅ | Dashboard permite seguimiento por Growth Manager (Juanchi) |
| 12 | 📌 OKR            | ✅ | KPIs por país (Argentina) definidos y monitoreados |
| 13 | 📌 OKR            | ✅ | Reporte mensual listo para dirección |
| 14 | 📂 Projects       | ✅ | Identificación de oportunidades como "reactivar MARCA D" |
| 15 | 🔗 Projects       | ✅ | Integración sugerida con Asana para seguimiento de acciones |
| 16 | 💼 Sales          | ✅ | Pipeline: MARCA D en riesgo de churn → alerta comercial |
| 17 | 💼 Sales          | ✅ | Wons/Churn: MARCA D podría ser churn si no mejora en 30 días |

---
