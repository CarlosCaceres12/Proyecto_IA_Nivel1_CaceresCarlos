# 🤖 AgendaBot Services

**Proyecto de Automatización de Agendamiento vía Telegram con n8n y Google Sheets.**

Este repositorio contiene la implementación de **AgendaBot**, un asistente virtual diseñado para gestionar citas, tareas y recordatorios de manera automatizada. El proyecto simula una interacción humana, respeta reglas de negocio estrictas y funciona sin depender de servicios de pago, cumpliendo con los requerimientos del Nivel 1 de IA.

## 👥 Equipo de Desarrollo
* **Carlos Caceres** - QA, Pruebas, Documentación y Despliegue.
* **[Nombre de tu Amigo]** - Desarrollo de Flujos y Lógica Backend.

## 🛠️ Stack Tecnológico (Capítulo II)
El proyecto ha sido implementado cumpliendo las restricciones de "Cero Costo":
* **Interfaz:** Telegram Bot API.
* **Orquestador:** n8n Community Edition (Self-hosted / Local).
* **Base de Datos:** Google Sheets.
* **Infraestructura:** Ejecución local con Tunneling.

## 📂 Estructura del Repositorio
```text
Proyecto_IA_Nivel1_CaceresCarlos/
├── docs/               
│   └── AgendaBot.md    # Documentación técnica y funcional completa
├── evidencias/         
│   ├── Evidencia_Final_Completa.xlsx  # LOGS maestros (Navegación, Citas, Errores)
│   ├── captura_chat_historial.jpg     # Evidencia visual de navegación
│   └── captura_base_datos.jpg         # Evidencia de impacto en BD
├── workflows/          
│   └── AgendaBot_Workflow.json        # Archivo fuente del flujo de n8n
└── README.md           # Información general del proyecto
