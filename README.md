# 📊 Dashboard Comercial Panovo - Power BI

Este repositorio contiene un ejemplo real de implementación de un dashboard de Power BI conectado a SQL Server, orientado al análisis de ventas de la industria panificadora.

---

## 📌 Objetivo

Brindar visibilidad diaria de la facturación, así como de la distribución por SKU y por cliente.

---

## 🛠️ Tecnologías Utilizadas

- Power BI Desktop (DirectQuery)
- SQL Server (Consultas a vistas y tablas en producción)
- DAX (Medidas complejas para disponibilidad, eficiencia, forecast, etc.)
- GitHub (para control de versiones y documentación técnica)

---

## 📁 Estructura del Repositorio

```plaintext
Comercial_Panovo/
├── README.md                               → Descripción general del repositorio
├── pbix/                                   → Archivo PBIX del tablero
├── docs/
│   ├── Medidas_DAX.md                      → Medidas DAX documentadas
│   ├── Columnas_DAX.md                     → DAX documentadas
│   ├── Tablas_DAX.md                       → DAX documentadas
│   └── Instructivo Dashboard OEE.docx      → Guía de uso del dashboard
├── img/
│   ├── preview_dashboard.png               → Captura del dashboard
└── ─── modelo_datos.png                    → Relación entre tablas
```

---

## 📷 Preview del Dashboard

![Preview](img/preview_dashboard.png)

---

## 📎 Cómo utilizarlo

1. Clona este repositorio.
2. Abre el archivo `pbix/Dashboard_OEE_Coflex.pbix` con Power BI Desktop.
3. Conecta tu fuente de datos o consulta en SQL Server.
4. Revisa la documentación en `/docs` para entender cada fórmula y estructura.

---

## 📄 Licencia

MIT – Libre uso con atribución.
