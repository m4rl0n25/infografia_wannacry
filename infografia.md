# 🛡️ WannaCry Ransomware – Análisis Completo  
**Repositorio informativo y educativo sobre uno de los ataques de ransomware más grandes de la historia.**

![WannaCry Banner](https://img.shields.io/badge/WannaCry-Ransomware-critical?style=for-the-badge&color=red)

---

## 📖 Tabla de Contenidos
1. [Resumen Ejecutivo](#-resumen-ejecutivo)  
2. [Descripción Técnica de la Vulnerabilidad](#-descripción-técnica-de-la-vulnerabilidad)  
3. [Línea de Tiempo del Ataque](#-línea-de-tiempo-del-ataque)  
4. [Impacto y Riesgos](#-impacto-y-riesgos)  
5. [Técnicas MITRE ATT&CK](#-técnicas-mitre-attck-asociadas)  
6. [Sectores Afectados](#-sectores-afectados)  
7. [Consecuencias y Mitigaciones](#-consecuencias-y-mitigaciones)  
8. [Recomendaciones Generales](#-recomendaciones-generales)  
9. [Fuentes Oficiales y Documentación](#-fuentes-oficiales-y-documentación)  
10. [Descargo de Responsabilidad](#-descargo-de-responsabilidad)  
11. [Licencia](#-licencia)

---

## 🧩 Resumen Ejecutivo
WannaCry fue un ataque global de ransomware ocurrido el **12 de mayo de 2017** que afectó a más de **300,000 dispositivos en 150 países**.  
El malware explotaba la vulnerabilidad **MS17-010 (EternalBlue)** presente en sistemas Windows sin actualizar y se propagaba automáticamente a través del protocolo **SMBv1**, convirtiéndose en uno de los brotes de malware más rápidos de la historia.

El ataque fue atribuido por múltiples gobiernos al **Lazarus Group**, un actor de amenazas avanzado vinculado a Corea del Norte.

---

## 🔍 Descripción Técnica de la Vulnerabilidad
- **Vulnerabilidad:** `MS17-010 – EternalBlue`  
- **Componente afectado:** Protocolo **SMBv1** (Server Message Block)  
- **Impacto técnico:** Ejecución remota de código (RCE)  
- **Causa:** Manejo incorrecto de paquetes SMB  
- **Sistemas vulnerables:** Windows XP, 7, Server 2008/2012 sin parches  

WannaCry no solo cifraba archivos, sino que incluía un módulo de **propagación tipo gusano**, lo que permitía infectar redes enteras sin interacción humana.

---

## 🕒 Línea de Tiempo del Ataque
| Fecha | Evento |
|-------|--------|
| Marzo 2017 | Microsoft publica el parche MS17-010 |
| Abril 2017 | Herramienta EternalBlue se filtra vía Shadow Brokers |
| 12 mayo 2017 | Inicio del brote global de WannaCry |
| 13 mayo 2017 | Investigadores descubren un “kill switch” vinculado a un dominio |
| Mayo–junio 2017 | Variantes sin kill-switch comienzan a circular |
| 2018–2023 | Persisten intentos de explotación de SMBv1 por malware relacionado |

---

## ⚠️ Impacto y Riesgos
- Paralización de redes corporativas completas  
- Pérdida total o parcial de servicios esenciales  
- Costos multimillonarios en recuperación  
- Riesgo persistente para organizaciones que aún utilizan SMBv1  
- Alto riesgo de reinfección en sistemas sin parchear  

---

## 🎯 Técnicas MITRE ATT&CK Asociadas

| Técnica | ID | Descripción |
|--------|-----|-------------|
| Explotación de vulnerabilidades | `T1203` | Uso de EternalBlue para ejecución remota |
| Movimiento lateral vía SMB | `T1021.002` | Propagación sin intervención humana |
| Cifrado de datos | `T1486` | Encriptación de archivos para extorsión |
| Scripting | `T1059` | Uso de componentes de automatización |
| Comunicación con infraestructura de pago | `T1041` | Contacto con servidores C2 y paneles de rescate |

---

## 🏭 Sectores Afectados

- **Salud** (caso crítico: NHS UK)  
- Transporte y logística  
- Educación  
- Telecomunicaciones  
- Administración pública  
- Manufactura e industria pesada  
- Energía e infraestructura crítica  
- Bancos y servicios financieros  

---

## 🛡️ Consecuencias y Mitigaciones

### **Consecuencias principales**
- Interrupción de operaciones esenciales  
- Pérdidas económicas que superaron los **4 mil millones USD**  
- Exposición a futuros ataques por falta de actualización  
- Saturación de equipos de TI en procesos de recuperación  

### **Mitigaciones recomendadas**
✔ Aplicar inmediatamente el parche `MS17-010`  
✔ **Deshabilitar SMBv1** en todos los sistemas  
✔ Segmentar la red  
✔ Implementar backups offline y pruebas de recuperación  
✔ Monitoreo avanzado (EDR, IDS/IPS)  
✔ Bloquear puertos SMB expuestos a internet  
✔ Mantener una política fuerte de gestión de vulnerabilidades  

---

## 🧠 Recomendaciones Generales
- Implementar **MFA en todos los accesos remotos**  
- Mantener inventarios actualizados de software y hardware  
- Evitar el uso de sistemas operativos obsoletos  
- Ejecutar análisis de exposición a protocolos antiguos  
- Capacitar a usuarios en manejo seguro de información  
- Adoptar un marco de ciberseguridad (NIST, ISO 27001, MITRE)

---

## 📚 Fuentes Oficiales y Documentación

### Organismos públicos
- **Microsoft MSRC – Boletín MS17-010**  
- **CISA – Alertas de ransomware histórico**  
- **US-CERT / FBI – Public Safety Alerts**  
- **NCSC (Reino Unido)** – Informes de WannaCry  

### Análisis técnicos de la industria
- Kaspersky  
- Symantec  
- ESET  
- Trend Micro  

*(Todos los enlaces deben agregarse según tu repositorio.)*

---

## ⚖️ Descargo de Responsabilidad
Este repositorio tiene fines **educativos, informativos y de concientización en ciberseguridad**.  
**No contiene ni contendrá código malicioso, exploits, ni instrucciones operativas**.  
El objetivo es documentar y analizar WannaCry desde una perspectiva defensiva.

---

## 📄 Licencia
Este repositorio se distribuye bajo la licencia **MIT License**.  
Puedes usar, modificar y compartir el contenido citando la fuente original.

---

## ✍️ Autor / Créditos
Contenido generado con fines educativos para documentación en GitHub.  
Puedes personalizar esta sección con tu nombre, organización o contacto.


