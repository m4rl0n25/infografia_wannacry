## 🎯 Técnicas MITRE ATT&CK Asociadas (Diagrama con Iconos)

```mermaid
flowchart TD
    A[💥 Explotación de Vulnerabilidades<br/><b>T1203</b><br/>🛠️ EternalBlue] 
        --> B[🔁 Movimiento Lateral vía SMB<br/><b>T1021.002</b><br/>📡 Propagación Automática]

    B --> C[🔐 Cifrado de Datos<br/><b>T1486</b><br/>💰 Extorsión]

    C --> D[📜 Scripting / Automatización<br/><b>T1059</b><br/>⚙️ Ejecución Interna]

    D --> E[🌐 Comunicación con Infraestructura C2<br/><b>T1041</b><br/>📥 Contacto con Servidores]
