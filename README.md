# 🎙️ Asistente Jules - Registro Diario por Voz

Aplicación web ligera e interactiva para registrar movimientos de cobro y ventas organizados por clientes, códigos y precios mediante comandos de voz en español.

Diseñado especialmente para facilitar el registro de pagos, ventas por catálogo, cuotas o pedidos diarios mediante comandos simples de voz como **"Oye Jules"**.

---

## ✨ Características

- 🗣️ **Activación por voz con "Oye Jules":**
  - Reconocimiento continuo en segundo plano.
  - Flujo conversacional guiado: pregunta **Nombre** ➔ **Código** ➔ **Precio**.
  - Reconocimiento de frases continuas: *"Oye Jules anota a Camila código 12 diez mil pesos"*.
  - Consultas de saldo: *"¿Cuánto llevamos hoy?"* o *"¿Cuánto lleva Camila?"*.
- 📅 **Planillas diarias independientes:**
  - Cada día genera automáticamente su propia planilla (`YYYY-MM-DD`).
  - Navegador entre días anteriores, hoy y días siguientes con selector de fecha.
- 👥 **Organización automática por clientes:**
  - Agrupación por personas con cálculo automático de **subtotales por cliente**.
  - Tarjetas de resumen con el **Total general del día**, cantidad de personas y total de artículos.
  - Opciones para editar o eliminar registros individuales.
- 💾 **Persistencia local y respaldos:**
  - Todos los datos se guardan en el navegador (`localStorage`).
  - **Exportar a Excel (CSV):** con formato UTF-8 y separador `;` para visualización limpia en Excel.
  - **Respaldo y restauración (JSON):** para migrar datos entre dispositivos.
- 🌐 **Sin dependencias externas:** Funciona en cualquier navegador moderno (Google Chrome o Microsoft Edge recomendados) directamente abriendo el archivo o mediante GitHub Pages.

---

## 🚀 Uso Rápido

1. Abre `index.html` en **Google Chrome** o **Microsoft Edge**.
2. Presiona el botón **"▶ Activar escucha continua"** y concede el permiso de micrófono.
3. Di en voz alta: **"Oye Jules"** y sigue las preguntas.
