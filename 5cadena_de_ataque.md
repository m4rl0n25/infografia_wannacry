## 🔗 Cadena de Ataque de WannaCry (Timeline)

```mermaid
timeline
    title Cadena de Ataque de WannaCry
    Reconocimiento : Escaneo de hosts vulnerables (SMBv1 / MS17-010)
    Explotación : Uso del exploit EternalBlue (ejecución remota de código)
    Backdoor : Instalación de DoublePulsar para cargar el payload
    Payload : Carga y ejecución del módulo ransomware WannaCry
    Acciones : Cifrado de archivos, nota de rescate, eliminación de Shadow Copies
    Propagación : Repite escaneo y explotación para infectar otros equipos
    Kill-switch : Si el dominio especial responde, el malware se detiene

