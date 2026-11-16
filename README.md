# 🎙️ Asistente Jules - Planillas de Lives por Voz con Calendario

> 🌐 **App en vivo (GitHub Pages):** [https://hugoandri.github.io/asistente-jules/](https://hugoandri.github.io/asistente-jules/)  
> 📦 **Repositorio:** [https://github.com/hugoandri/asistente-jules](https://github.com/hugoandri/asistente-jules)

Aplicación web interactiva para registrar ventas y cobros en **transmisiones en vivo (Lives)** organizados por clientes, códigos y precios mediante comandos de voz en español.

---

## ✨ Nuevas Características

- 📅 **Calendario visual de Lives:**
  - Vista mensual interactiva donde cada día muestra sus Lives programados y el total recaudado.
  - Permite programar o crear múltiples Lives por día (ej. *Live Mañana*, *Live Tarde*, *Remate Nocturno*).
  - Cada Live tiene su propia planilla independiente con clientes, subtotales y total general.
- 🗣️ **Jules pregunta el Live por voz:**
  - Al decir **“Oye Jules”**, el asistente inmediatamente pregunta:
    > *“¿A qué Live corresponde esta planilla?”*
  - Respondes con el nombre del Live (ej. *“Live de la tarde”* o *“el mismo”*). Si no existe, Jules lo crea automáticamente para hoy.
  - Luego te pide sucesivamente: **Nombre del cliente** ➔ **Código** ➔ **Precio**.
  - Confirma por voz el monto y dice el subtotal acumulado del cliente en ese Live.
- 👥 **Planilla agrupada por cliente:**
  - Detalle por persona con todos sus artículos adquiridos, hora de compra y subtotal.
  - Opciones para editar o eliminar registros individuales.
- 💾 **Persistencia local y respaldos:**
  - Guardado automático en `localStorage`.
  - **Exportar a Excel (CSV):** reporte con subtotales por cliente y total general del Live.
  - **Respaldos JSON:** descarga e importación completa.

---

## 🚀 Uso Rápido

1. Entra a [https://hugoandri.github.io/asistente-jules/](https://hugoandri.github.io/asistente-jules/) en **Google Chrome** o **Microsoft Edge**.
2. Presiona **“▶ Activar escucha continua”** y concede el permiso de micrófono.
3. Di en voz alta: **“Oye Jules”**.
4. Responde a sus preguntas:
   1. *¿A qué Live corresponde?* ➔ Ej: *"Live Tarde"*
   2. *¿Cuál es el nombre?* ➔ Ej: *"María"*
   3. *¿Cuál es el código?* ➔ Ej: *"A1"*
   4. *¿Cuál es el precio?* ➔ Ej: *"cinco mil pesos"*
