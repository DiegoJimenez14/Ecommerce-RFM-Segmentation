#  E-commerce RFM Segmentation
### Customer Segmentation using Python & Pandas

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4C8CBF?style=for-the-badge&logo=python&logoColor=white)

---

##  Business Case

Una empresa de retail online del Reino Unido posee una base de datos transaccional masiva (+500k registros) pero carece de inteligencia sobre sus clientes. El objetivo es segmentar la base de usuarios para optimizar campañas de marketing, pasando de un enfoque "masivo" a uno "dirigido".

**Técnica Utilizada:** Análisis RFM (Recency, Frequency, Monetary) para clasificar clientes según su valor y comportamiento.

---

##  Hallazgos Clave (Data Insights)

Tras procesar **397,884 transacciones** y depurar clientes inactivos, la segmentación reveló una realidad crítica:

1.  **Dominio de Clientes "Dormidos" (Hibernating):**
    * El segmento más grande es *Hibernating*. Esto indica una **tasa de retención muy baja**. Los clientes compran una vez y no vuelven.
    * *Acción:* No gastar presupuesto en intentar reactivarlos masivamente, el ROI sería bajo.

2.  **Escasez de "Champions":**
    * El grupo de clientes VIP (*Champions*) es el más pequeño.
    * *Riesgo:* Alta dependencia de pocos clientes. Si estos se van, el revenue cae drásticamente.

3.  **Oportunidad en "Potential Loyalists":**
    * Se identificó un grupo intermedio con alta recencia pero baja frecuencia.
    * *Estrategia:* Aquí es donde debe ir el presupuesto de Marketing (Cross-selling) para convertirlos en Champions.

---

##  Visualización de Segmentos

Distribución de clientes según su puntaje RFM. Nótese la gran base de usuarios inactivos vs. la élite de compradores frecuentes.

![RFM Segments](rfm_segments.png)

---

##  Tech Stack

* **Python (Pandas):** Limpieza de datos (Data Cleaning), manejo de fechas y cálculo de cuartiles con `qcut`.
* **Matplotlib / Seaborn:** Visualización de la distribución de segmentos.
* **Jupyter Notebook:** Entorno de desarrollo interactivo.

---
<div align="center">
  
**Author:** Diego Jimenez | [LinkedIn Profile](TU_LINK_DE_LINKEDIN_AQUI)

</div>
