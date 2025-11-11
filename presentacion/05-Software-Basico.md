# 5. 💻 Software Básico

## 🤔 ¿Qué es un Slicer?

**Un slicer** convierte tu modelo 3D en instrucciones que la impresora entiende

📁 **Entrada:** Archivo `.STL` o `.3MF` (tu modelo 3D)

⚙️ **Proceso:** El slicer "rebana" el modelo en capas

📤 **Salida:** Archivo `.gcode` (instrucciones para la impresora)

👉 **Sin slicer = No puedes imprimir**

---

## 🛠️ Los 3 Slicers Recomendados

### 🌐 Cura (Ultimaker)

**🏆 El MÁS POPULAR y gratuito → Empieza con este**

✅ **Ventajas:**

- 💯 **Completamente gratuito**
- 👶 **Interfaz super intuitiva** (aprende en 10 minutos)
- 📦 **Perfiles pre-configurados** para +200 impresoras
- 🌍 **Gran comunidad** → tutoriales en español abundantes
- 🔄 **Actualizaciones frecuentes** y estable

**💻 Compatible con:** Windows, Mac, Linux

**🎯 Ideal para:** Principiantes y usuarios intermedios

**🔗 Descarga:** [ultimaker.com/software/ultimaker-cura](https://ultimaker.com/software/ultimaker-cura)

**💡 Mi recomendación:** Empieza aquí → 90% de usuarios nunca cambian

---

### 🟧 PrusaSlicer

**🔧 Excelente alternativa open source (más avanzado)**

✅ **Ventajas:**

- 💯 **Gratuito y open source**
- ⚙️ **Muy potente** → configuraciones avanzadas
- 🎨 **Painted supports** (soportes pintados manualmente)
- 🔓 **Funciona con TODAS las marcas** de impresoras

**💻 Compatible con:** Windows, Mac, Linux

**🎯 Ideal para:** Usuarios intermedios/avanzados que quieren control total

**⚠️ Curva de aprendizaje:** Más empinada que Cura

**🔗 Descarga:** [prusa3d.com/prusaslicer](https://prusa3d.com/prusaslicer)

---

### 🟩 Bambu Studio

**🚀 Para impresoras Bambu Lab (muy moderno)**

✅ **Ventajas:**

- ⚡ **Optimizado específicamente** para Bambu Lab
- 🎨 **Interfaz moderna** y elegante
- 📹 **Integración total** con cámara y WiFi
- 🎯 **Multi-color** nativo (si tienes AMS)

**💻 Compatible con:** Windows, Mac, Linux

**🎯 Ideal para:** Propietarios de Bambu Lab

**⚠️ Limitación:** Solo funciona bien con Bambu

**🔗 Descarga:** [bambulab.com/en/download/studio](https://bambulab.com/en/download/studio)

---

## 🎯 ¿Cuál Elegir?

**🟩 Cura → EMPIEZA AQUÍ**

👉 Fácil, gratuito, funciona con TODO

**🟧 PrusaSlicer → Cuando quieras más control**

👉 Configuraciones avanzadas, painted supports

**🟩 Bambu Studio → Si tienes Bambu Lab**

👉 Aprovecha al máximo tu impresora

---

## 📊 Flujo de Trabajo (Del Modelo 3D a la Impresión)

### 🔹 Paso 1: Obtener el Modelo 3D

**Opción A:** Descarga de repositorios

- 🏛️ **Thingiverse** / **Printables** / **MyMiniFactory**
- Formato: `.STL` o `.3MF`

**Opción B:** Diseña el tuyo

- 🎨 **Tinkercad** (fácil, navegador)
- 🔧 **Fusion 360** (profesional)
- 🎭 **Blender** (orgánico)

---

### 🔹 Paso 2: Abrir en el Slicer

**Cómo hacerlo:**

1. 📂 Abre **Cura** (o tu slicer)
2. 🖱️ **Arrastra** el archivo `.STL` a la ventana
3. 👀 El modelo aparecerá en la **cama virtual**

**✅ Si ves tu modelo en la pantalla, vas bien**

---

### 🔹 Paso 3: Configurar Parámetros

**📝 Parámetros BÁSICOS (los únicos que necesitas al inicio):**

**🎨 Material**

👉 **PLA** (empieza siempre con PLA)

**📏 Calidad de Capa**

👉 **0.2mm** (calidad estándar) → equilibrio perfecto

- 0.1mm = más detalle, más lento
- 0.3mm = menos detalle, más rápido

**🔲 Relleno (Infill)**

👉 **20%** para la mayoría de cosas

- 10-15% → decoración
- 30-50% → piezas funcionales

**🏗️ Soportes**

👉 **"Solo si el modelo los requiere"**

- Voladizos > 45° necesitan soportes
- Cura te lo dice automáticamente

---

### 🔹 Paso 4: Generar G-code

**Qué hacer:**

1. 🖱️ Click en **"Slice"** o **"Laminar"** (botón naranja en Cura)
2. ⏱️ **Revisa tiempo estimado** (¿tienes ese tiempo disponible?)
3. 📊 **Revisa cantidad de material** (¿tienes suficiente filamento?)
4. 👀 **Vista previa de capas** (opcional: revisa que se vea bien)

**✅ Si todo se ve bien, continúa**

---

### 🔹 Paso 5: Transferir a la Impresora

**Opción A: Tarjeta SD (más común)**

1. 💾 Click en **"Save to Removable Drive"**
2. 🔌 Expulsa la SD de forma segura
3. 🖨️ Inserta en la impresora

**Opción B: WiFi (si tu impresora lo soporta)**

1. 📡 Conecta Cura a tu impresora
2. 📤 Click en **"Print via Network"**

---

### 🔹 Paso 6: ¡Imprimir!

1. 🖨️ En la impresora, selecciona el archivo
2. ▶️ **Inicia la impresión**
3. 👀 **Observa los primeros 5 minutos** (crítico)
4. ✅ Si la **primera capa se adhiere bien**, puedes relajarte

---

## 🎯 Configuración Recomendada para Tu PRIMERA Impresión

**📋 Usa estos valores exactos:**

| Parámetro | Valor | Por qué |
|---|---|---|
| **Material** | PLA | El más fácil |
| **Temperatura Boquilla** | 200°C | Estándar para PLA |
| **Temperatura Cama** | 60°C | Adhesión perfecta |
| **Velocidad** | 50mm/s | Lento pero seguro |
| **Altura de Capa** | 0.2mm | Calidad estándar |
| **Relleno** | 20% | Suficiente para la mayoría |
| **Soportes** | NO | Elige modelos sin voladizos |

**👉 Copia estos valores EXACTAMENTE para tu primera impresión**

---

## 💡 Consejos de Oro

**🔥 Tip #1: No cambies configuraciones al inicio**

👉 Usa los **perfiles por defecto** → están bien calibrados

**🔥 Tip #2: Si cambias algo, cambia UNA cosa a la vez**

👉 Así sabes qué causó el problema (o la mejora)

**🔥 Tip #3: Guarda tus configuraciones exitosas**

👉 En Cura: **"Manage Profiles" → "Create Profile"**

**🔥 Tip #4: La primera capa es el 80% del éxito**

👉 Si falla la primera capa, pausa y ajusta

---

## ❓ Preguntas Frecuentes

**🤔 ¿Necesito pagar por un slicer?**

❌ **NO** → Cura y PrusaSlicer son completamente gratuitos

**🤔 ¿Puedo usar Cura con cualquier impresora?**

✅ **SÍ** → Funciona con +200 marcas diferentes

**🤔 ¿Qué es mejor, Cura o PrusaSlicer?**

💡 **Cura para principiantes**, PrusaSlicer cuando quieras más control

**🤔 ¿Cuánto pesa un archivo G-code?**

📊 Típicamente **2-20 MB** (cabe en cualquier SD)