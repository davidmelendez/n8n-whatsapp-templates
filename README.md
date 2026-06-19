# n8n + WhatsApp Business API — Casos de Uso

Documentación de flujos de automatización para negocios que atienden clientes por WhatsApp.

Construido por [David Melendez](https://davidmelendez.net) — 20 años de experiencia en automatización de procesos con IA, n8n y WhatsApp Business API.

---

## Casos documentados

### 1. Agente de atención 24/7
Flujo que responde preguntas frecuentes fuera de horario sin intervención humana.
- Recibe mensaje por WhatsApp Business API
- Consulta base de conocimiento del negocio
- Responde con IA (Claude / OpenAI)
- Escala a humano si el caso lo requiere

### 2. Agendamiento automático de citas
El cliente agenda, confirma y recibe recordatorio sin que nadie del equipo intervenga.
- Cliente solicita cita por WhatsApp
- Agente verifica disponibilidad en tiempo real
- Confirma y registra en el sistema
- Envía recordatorio automático antes de la cita

### 3. Calificación de prospectos
Flujo que califica leads entrantes antes de que el equipo comercial los atienda.
- Prospecto escribe por WhatsApp
- Agente recopila información clave (presupuesto, urgencia, necesidad)
- Clasifica y notifica al equipo con el resumen

---

## Stack

- **n8n** — orquestación de flujos
- **WhatsApp Business API** (vía Bird / Meta directa)
- **Supabase** — base de datos y almacenamiento
- **Claude API / OpenAI** — procesamiento de lenguaje natural
- **.NET / C#** — integraciones con sistemas legacy

---

## ¿Querés implementar algo similar?

→ [davidmelendez.net](https://davidmelendez.net)
