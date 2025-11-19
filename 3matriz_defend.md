## 🛡️ Matriz MITRE DEFEND 

```mermaid
flowchart TD
    A[🔍 Identificación de Activos<br/><b>D3-Identify</b><br/>📂 Inventario de Sistemas]:::identify
        --> B[🛡️ Protección de Credenciales<br/><b>D3-Protect</b><br/>🔑 MFA y Gestión Segura]:::protect

    B --> C[📊 Monitoreo y Detección<br/><b>D3-Detect</b><br/>👁️ SIEM / EDR]:::detect

    C --> D[🚨 Respuesta a Incidentes<br/><b>D3-Respond</b><br/>⚡ Contención y Erradicación]:::respond

    D --> E[🔄 Recuperación<br/><b>D3-Recover</b><br/>💾 Backups y Restauración]:::recover

    %% Definición de colores por fase
    classDef identify fill:#4CAF50,color:#fff,stroke:#2E7D32;
    classDef protect fill:#2196F3,color:#fff,stroke:#1565C0;
    classDef detect fill:#FFC107,color:#000,stroke:#FF9800;
    classDef respond fill:#F44336,color:#fff,stroke:#C62828;
    classDef recover fill:#9C27B0,color:#fff,stroke:#6A1B9A;

