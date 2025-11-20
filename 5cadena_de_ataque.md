## 🔗 Cadena de Ataque de WannaCry – Diagrama en Mermaid

```mermaid
flowchart TD
    A[1. Reconocimiento<br/>Escaneo de hosts vulnerables<br/>(SMBv1 - MS17-010)] --> B[2. Explotación<br/>EternalBlue<br/>(RCE)]
    B --> C[3. Backdoor<br/>Instalación de DoublePulsar]
    C --> D[4. Payload Ransomware<br/>Carga y ejecución de WannaCry]
    D --> E[5. Acciones del Malware<br/>- Cifrado AES/RSA<br/>- Nota de rescate<br/>- Eliminación de Shadow Copies]
    E --> F[6. Propagación<br/>Nuevo escaneo y explotación]
    F --> G[7. Kill Switch<br/>Si el dominio responde,<br/>el malware se detiene]

