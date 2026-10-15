# TRAZA//CO2 — Calculadora de Huella y Rentabilidad de Movilidad

Aplicación web profesional orientada a la consultoría de movilidad y descarbonización para calcular la huella de carbono, el Coste Total de Propiedad (TCO) y la rentabilidad económica del cambio de vehículo.

Desarrollada por **Miguel Ángel Layunta López**.

---

## 🚀 Características Principales

* **Análisis del Vehículo Actual vs. Candidato:** Compara consumos, kilometrajes, costes energéticos e inversión inicial entre distintos tipos de motorización (Gasolina, Diésel, Híbrido, PHEV, GLP/GNC y Eléctrico BEV).
* **Proyecciones de Precio de CO₂:** Incorpora escenarios basados en la directiva europea **UE ETS2** y proyecciones de **BloombergNEF** para horizontes temporales (2030, 2035, 2040).
* **Simulación de Costes ZBE (RTVV):** Cálculo y advertencias automáticas sobre penalizaciones operativas estimadas en Zonas de Bajas Emisiones para vehículos sin distintivo medioambiental.
* **Indicadores Financieros Clave (KPIs):** 
  * Toneladas de $CO_2$ evitadas al año.
  * Ahorro operativo anual y valorización del $CO_2$.
  * Periodo de amortización (*Payback*).
  * Ahorro neto acumulado a 10 años[cite: 1].
* **Visualización Gráfica Interactiva:** Gráficos dinámicos de evolución del TCO y $CO_2$ acumulado mediante **Chart.js**[cite: 1].
* **Informes en PDF:** Exportación inmediata de los resultados y métricas del análisis en formato PDF utilizando **jsPDF**[cite: 1].
* **Capacidad PWA & Offline:** Soporta Progressive Web App gracias a su *Service Worker* integrado, permitiendo su instalación en dispositivos y funcionamiento sin conexión[cite: 1].

---

## 🛠️ Tecnologías Utilizadas

* **HTML5 / CSS3** (Diseño adaptable *responsive* con variables personalizadas y paleta corporativa oscura)[cite: 1].
* **JavaScript (ES6+)**[cite: 1].
* **Chart.js** (Gráficos interactivos de líneas y métricas)[cite: 1].
* **jsPDF & html2canvas** (Generación de informes ejecutivos en PDF)[cite: 1].

---

## 📂 Estructura del Proyecto

```text
TRAZA-CO2/
│
├── index.html          # Interfaz principal, lógica de cálculo y estilos embebidos
├── sw.js               # Service Worker para gestión de caché y PWA offline
├── manifest.json       # Manifiesto de la aplicación web progresiva
└── icons/
    └── logo.png        # Logotipo corporativo con camión y símbolo del euro