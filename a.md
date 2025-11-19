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
WannaCry fue un ataque global de ransomware ocurrido el **12 de mayo de 2017**, afectando a más de **300,000 dispositivos en 150 países**.  
Explotaba la vulnerabilidad **MS17-010 (EternalBlue)** en sistemas Windows sin actualizar, propagándose rápidamente mediante el protocolo **SMBv1**.  
El ataque fue atribuido al **Lazarus Group**, asociado a Corea del Norte.

---

## 🔍 Descripción Técnica de la Vulnerabilidad
- **Vulnerabilidad:** `MS17-010 – EternalBlue`  
- **Componente afectado:** SMBv1  
- **Impacto:** Ejecución remota de código (RCE)  
- **Sistemas vulnerables:** Windows XP, 7, Server 2008/2012 sin parches  

WannaCry incluía además un módulo tipo **gusano**, permitiendo su propagación automática entre sistemas vulnerables.

---

## 🕒 Línea de Tiempo del Ataque

```mermaid
timeline
    title Línea de Tiempo de WannaCry
    2017-03 : Microsoft publica MS17-010
    2017-04 : Shadow Brokers filtra EternalBlue
    2017-05-12 : Estalla el brote global de WannaCry
    2017-05-13 : Descubrimiento del "kill-switch"
    2017-06 : Variantes sin kill-switch empiezan a circular


