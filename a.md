# 🛡️ WannaCry Ransomware – Análisis Completo  
**Repositorio informativo y educativo sobre uno de los ataques de ransomware más grandes de la historia.**

![WannaCry Banner](https://img.shields.io/badge/WannaCry-Ransomware-critical?style=for-the-badge&color=red)

---

## 📖 Tabla de Contenidos
1. [Resumen Ejecutivo](#-resumen-ejecutivo)  
2. [Descripción Técnica de la Vulnerabilidad](#-descripción-técnica-de-la-vulnerabilidad)  
3. [Línea de Tiempo del Ataque](#-línea-de-tiempo-del-ataque)  
4. [Gráficos Mermaid](#-gráficos-mermaid)  
5. [Impacto y Riesgos](#-impacto-y-riesgos)  
6. [Técnicas MITRE ATT&CK](#-técnicas-mitre-attck-asociadas)  
7. [Sectores Afectados](#-sectores-afectados)  
8. [Consecuencias y Mitigaciones](#-consecuencias-y-mitigaciones)  
9. [Recomendaciones Generales](#-recomendaciones-generales)  
10. [Fuentes Oficiales](#-fuentes-oficiales-y-documentación)  
11. [Descargo de Responsabilidad](#-descargo-de-responsabilidad)  
12. [Licencia](#-licencia)

---

## 🧩 Resumen Ejecutivo
WannaCry fue un ataque global de ransomware ocurrido el **12 de mayo de 2017** que afectó a más de **300,000 dispositivos en 150 países**.  
El malware explotaba la vulnerabilidad **MS17-010 (EternalBlue)** y se propagaba mediante el protocolo **SMBv1**, lo que permitió un ataque rápido y masivo.

---

## 🔍 Descripción Técnica de la Vulnerabilidad
- **Vulnerabilidad:** `MS17-010 – EternalBlue`  
- **Componente afectado:** Protocolo **SMBv1**  
- **Impacto:** ejecución remota de código  
- **Sistemas vulnerables:** Windows XP/7/Server sin parchear

---

## 🕒 Línea de Tiempo del Ataque

```mermaid
timeline
    title Línea de Tiempo de WannaCry
    2017-03 : Microsoft publica MS17-010
    2017-04 : Shadow Brokers filtra EternalBlue
    2017-05-12 : Estalla el brote global de WannaCry
    2017-05-13 : Descubrimiento del "kill-switch" por investigadores
    2017-06 : Aparición de variantes sin kill-switch

