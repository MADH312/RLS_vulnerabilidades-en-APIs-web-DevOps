# 🔐 Integración de seguridad en pipelines DevOps para prevenir vulnerabilidades en APIs web

## 📖 Descripción
Este repositorio documenta una **revisión sistemática de la literatura (PRISMA 2020)** sobre las mejores prácticas para integrar controles de seguridad en pipelines DevOps, con el objetivo de **reducir vulnerabilidades en APIs web** sin comprometer la velocidad de despliegue.

La investigación analiza literatura académica y gris publicada entre **2020 y 2026**, sintetizando evidencia de **24 estudios seleccionados** tras evaluar 108 registros.

---

## 🎯 Objetivo
Identificar, evaluar críticamente y sintetizar la evidencia científica y empírica disponible sobre:
- Estrategias de integración de seguridad en pipelines CI/CD.
- Impacto en la reducción de vulnerabilidades de software.
- Retos y métricas actuales en la práctica de **DevSecOps**.

---

## 🔑 Hallazgos principales
- **Integración por capas**:
  - ✅ **SAST**: análisis estático de código.  
  - ✅ **SCA**: escaneo de dependencias.  
  - ✅ **DAST/IAST**: pruebas dinámicas e interactivas.  
  - ✅ **Pruebas específicas de APIs**: RESTest, EvoMaster, Schemathesis.  
  - ✅ **Validación de IaC y políticas como código**: Docker, Kubernetes, Helm.  

- **Resultados**:
  - La automatización favorece la detección temprana y reduce trabajo manual.
  - La evidencia cuantitativa de reducción se concentra en configuraciones e infraestructura.
  - Persisten retos en métricas uniformes y en la mitigación de vulnerabilidades funcionales de APIs.

---

## 📂 Estructura del repositorio

  - *Revision Sistemática de Literatura.pdf     → Documento académico con metodología PRISMA 2020*
  - *Laboratorios Evaluación experimental.pdf   → Ejercicios prácticos de explotación y mitigación*
  - *README.md                                  → Descripción general del proyecto*

---
## 🛠️ Tecnologías y conceptos clave
- **DevOps / DevSecOps**
- **CI/CD pipelines**
- **OWASP API Security Top 10**
- **Infraestructura como código (IaC)**
- **Automatización de pruebas de seguridad**
