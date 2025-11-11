# 6. 🚀 Primeros Pasos

## 🎯 Antes de Imprimir: Calibración Básica

**⚠️ CRÍTICO:** El 90% de las impresiones fallidas se deben a mala calibración inicial

👉 **Dedica 30 minutos a calibrar BIEN** → Ahorrarás HORAS de frustración

---

## 🔧 Las 3 Calibraciones Esenciales

### 1️⃣ Nivelación de la Cama (LA MÁS IMPORTANTE)

**🔥 ¿Por qué es importante?**

La primera capa es la **BASE** de toda tu impresión

❌ **Primera capa mal** = **TODO falla**

✅ **Primera capa bien** = **90% de éxito asegurado**

---

### 🤖 Con Nivelación Automática (ABL)

**✅ Mucho más fácil:**

1. 📱 Ve al menú de la impresora
2. 🔍 Busca **"Auto Bed Leveling"** o **"ABL"**
3. ▶️ Inicia el proceso
4. ⏱️ Espera 2-3 minutos
5. ✅ ¡Listo!

**💡 La impresora mide 9-25 puntos automáticamente**

---

### ✋ Con Nivelación Manual

**⚠️ Requiere paciencia, pero no es difícil:**

**🛠️ Necesitas:**

- 📄 Una hoja de papel (papel normal)

**📝 Proceso:**

1. 🏠 **Home** todos los ejes (lleva boquilla a posición inicial)
2. 🌡️ **Calienta** la cama a 60°C (importante)
3. 📄 **Coloca** papel entre boquilla y cama
4. 🔩 **Ajusta** tornillo de esquina inferior izquierda:
   - Papel debe **rozar ligeramente**
   - Debe poder moverse con resistencia
5. 🔄 **Repite** en las otras 3 esquinas
6. 🎯 **Verifica** el centro
7. ♻️ **Repite** TODO el proceso 2-3 veces (las esquinas se afectan entre sí)

**✅ Está bien cuando:** El papel roza IGUAL en todos los puntos

---

### 2️⃣ Temperatura del Hotend y Cama

**🌡️ Para PLA (tu primer material):**

- **Boquilla (Hotend):** 200°C
- **Cama:** 60°C

**🔍 Cómo verificar que funciona:**

1. 🔥 **Precalienta** desde el menú
2. ⏱️ Espera 5 minutos
3. 👀 **Observa:** Las temperaturas deben estabilizarse (±2°C)

**⚠️ Problema si:**

- Fluctúa mucho (±10°C) → Hotend o termistor defectuoso
- No llega a temperatura → Problema eléctrico

---

### 3️⃣ Primera Capa Perfecta

**🎯 La primera capa es el 80% del éxito de tu impresión**

---

**✅ Señales de una BUENA primera capa:**

🟢 **Filamento se adhiere perfectamente** a la cama

🟢 **Líneas están juntas** pero no se montan unas sobre otras

🟢 **Superficie lisa y uniforme** sin espacios

🟢 **No se despega** en las esquinas

---

**❌ Señales de PROBLEMAS (y soluciones):**

**Problema #1: Filamento NO se adhiere**

🔴 **Causa:** Boquilla muy alta

✅ **Solución:** Ajusta Z-offset (baja boquilla 0.1mm)

---

**Problema #2: Líneas aplastadas o transparentes**

🔴 **Causa:** Boquilla muy baja (muy cerca de la cama)

✅ **Solución:** Ajusta Z-offset (sube boquilla 0.1mm)

---

**Problema #3: Esquinas levantadas (warping)**

🔴 **Causa:** Cama fría o corriente de aire

✅ **Solución:** Aumenta temperatura cama a 65°C o usa pegamento

---

## 🏆 Tu Primera Impresión Exitosa (Paso a Paso)

### 📝 Preparación (10 minutos)

**1️⃣ Elige un modelo SIMPLE**

✅ **Características ideales:**

- ⏱️ Tiempo: **Menos de 2 horas**
- 🏗️ **Sin voladizos** complicados
- 📏 **Tamaño pequeño** (menos de 5cm)

**💡 Ejemplos perfectos:**

- **Calibration Cube** (20 minutos)
- **Benchy** (barco clásico, 2 horas)
- **Cable clip** (30 minutos)

---

**2️⃣ Prepara tu Setup**

☑️ **Filamento PLA cargado** correctamente

☑️ **Cama limpia** → Limpia con alcohol isopropílico

☑️ **Tarjeta SD** lista y formateada

☑️ **Espacio libre** alrededor (sin corrientes de aire)

---

**3️⃣ Configura en el Slicer**

**🎯 Usa EXACTAMENTE estos valores:**

```
Material: PLA
Temperatura Boquilla: 200°C
Temperatura Cama: 60°C
Calidad: 0.2mm (Estándar)
Relleno: 20%
Soportes: No
Velocidad: 50mm/s
```

👉 **Genera G-code** y guarda en SD

---

### 🎬 Inicio de la Impresión (CRÍTICO)

**4️⃣ Inicia y OBSERVA**

🔥 **Los primeros 5 minutos son CRÍTICOS:**

1. ▶️ **Inicia** la impresión
2. 👀 **Observa** la primera capa COMPLETA
3. ✅ **Verifica** que el filamento se adhiere bien
4. ⚠️ **Si algo va mal:** Pausa INMEDIATAMENTE y ajusta

**💡 Tip:** Si la primera capa sale perfecta, la impresión tiene 90% de éxito

---

### ⏱️ Durante la Impresión

**5️⃣ ¡Espera con Paciencia!**

✅ **Haz:**

- Deja trabajar la impresora sin tocarla
- Revisa cada 30 minutos (opcional)

❌ **NO hagas:**

- Abrir puertas/ventanas (corrientes de aire)
- Mover la impresora
- Tocar la pieza mientras imprime

---

### 🎉 Finalización

**6️⃣ Retira la Pieza Correctamente**

**🔥 IMPORTANTE:**

1. ⏸️ **Espera** que la cama se enfríe (5-10 minutos)
   - La pieza se despegará más fácil
2. 🔪 **Usa espátula** con cuidado
3. ❌ **NO fuerces** mientras esté caliente (puedes romper la pieza)

**💡 Tip:** Con PLA, al enfriarse la pieza se despega casi sola

---

## ✨ Modelos Recomendados por Nivel

### 🟢 Nivel 1: Super Fácil (Primera semana)

**Tiempo: 15 min - 1 hora**

✅ **Calibration Cube XYZ** (20 min)

👉 Perfecto para verificar tu impresora

✅ **Cable Clips** (30 min)

👉 Útiles y simples

✅ **Simple Keychain** (45 min)

👉 Decorativo y fácil

---

### 🟡 Nivel 2: Fácil (Segunda semana)

**Tiempo: 2-4 horas**

✅ **Baby Yoda / Grogu** (2.5 horas)

👉 Clásico de impresión 3D

✅ **Succulent Planter** (3 horas)

👉 Decorativo y funcional

✅ **Desk Organizer** (4 horas)

👉 Útil para tu escritorio

---

### 🟠 Nivel 3: Intermedio (Cuando domines lo básico)

**Tiempo: 4-8 horas**

✅ **Articulated Dragon** (5 horas)

👉 Se imprime articulado, sin ensamblaje

✅ **Phone Stand** (3 horas)

👉 Funcional y con detalles

✅ **Gear Fidget Toy** (6 horas)

👉 Engranajes funcionales

---

## 🔍 Checklist Pre-Impresión (Úsalo SIEMPRE)

**✅ Antes de darle "Print", verifica:**

### 🔧 Hardware

☐ **Cama nivelada** (hace menos de 5 impresiones)

☐ **Filamento cargado** correctamente (sin nudos)

☐ **Boquilla limpia** (sin restos de filamento)

☐ **Cama limpia** (sin grasa ni polvo)

### 💾 Software

☐ **Archivo .gcode en la SD** (no .STL)

☐ **Temperaturas configuradas** (PLA: 200/60)

☐ **Tiempo estimado revisado** (¿tienes ese tiempo?)

### 🏠 Ambiente

☐ **Espacio libre** alrededor (sin obstáculos)

☐ **Sin corrientes de aire** (cierra ventanas)

☐ **Superficie nivelada** (la impresora no se mueve)

---

## 💡 Consejos de Oro para Tu Primera Impresión

**🔥 Consejo #1: La primera capa lo es TODO**

👉 Si falla, pausa y reintenta. No dejes que continúe.

**🔥 Consejo #2: Empieza PEQUEÑO**

👉 No intentes un busto de 12 horas en tu primera semana

**🔥 Consejo #3: Usa PLA exclusivamente al inicio**

👉 Es el material más fácil y tolerante a errores

**🔥 Consejo #4: Toma fotos de tus configuraciones exitosas**

👉 Para replicarlas después

**🔥 Consejo #5: Únete a comunidades**

👉 Todos empezamos con fallos, pedir ayuda es normal

---

## 🎉 ¡Felicidades por tu Primera Impresión!

**Si llegaste hasta aquí y completaste tu primera impresión:**

🏆 **¡Bienvenido al mundo de la impresión 3D!**

**📈 Próximos pasos:**

1. ✅ Imprime 5-10 modelos simples más
2. ✅ Experimenta con diferentes rellenos (15%, 25%, 50%)
3. ✅ Prueba modelos con soportes
4. ✅ Cuando domines PLA, pasa a PETG

**💪 Recuerda:** Cada fallo es una lección. Todos empezamos igual.