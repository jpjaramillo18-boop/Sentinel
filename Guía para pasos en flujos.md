**Guía para pasos en flujos (CTAs de navegación)**

**🎯 Objetivo**

Estandarizar el uso de CTAs en flujos multi-paso de Banca Empresas para garantizar consistencia, claridad y previsibilidad en la navegación del usuario.

**🧠 PRINCIPIO BASE**

En flujos secuenciales:

- El avance se expresa con **“Continuar”**
- El retroceso se expresa con **“Regresar”**
- El sistema se adapta al estado del flujo:
    - Inicio
    - Intermedio
    - Final

**🔁 1. REGLA DE NAVEGACIÓN POR ESTADO DEL FLUJO**

**🟦 Paso intermedio (flujos multi-step)**

✔ Se usan dos botones:

- Regresar (secundario)
- Continuar (primario)

📌 Ejemplo:  
\[Regresar\] \[Continuar\]

**🟦 Primer paso del flujo**

✔ No existe retroceso dentro del flujo

✔ Se muestra solo:

- Continuar

📌 Excepción opcional:  
Si se permite salida del flujo:

- Inicio (lleva al Home o dashboard)

📌 Ejemplo:  
\[Inicio\] \[Continuar\]

**🟦 Inicio del flujo (pantalla de entrada)**

✔ Acción principal:

- Comenzar (CTA primario)

✔ Acción secundaria opcional:

- Regresar (si existe contexto previo)

📌 Ejemplo:  
\[Regresar\] \[Comenzar\]

**🟦 Último paso del flujo**

✔ “Continuar” se reemplaza por una acción final explícita

**Ejemplos válidos:**

- Finalizar
- Enviar
- Confirmar
- Pagar
- Crear cuenta

📌 Regla:  
El CTA final debe describir la acción real del sistema, no la navegación.

📌 Ejemplo:  
\[Regresar\] \[Enviar\]

**🚪 2. REGLA DE SALIDA DEL FLUJO**

Si el usuario puede abandonar el flujo en etapas tempranas:

- Se puede incluir botón **Inicio**
- Este representa salida al Home o dashboard

📌 Ejemplo:  
\[Inicio\] \[Continuar\]

**⚠️ 3. REGLAS DE CONSISTENCIA**

**❌ No usar**

- Avanzar
- Siguiente (evitar duplicidad semántica con “Continuar”)
- Regresar al paso anterior (redundante)

**✅ Usar siempre**

- Regresar
- Continuar
- Comenzar (inicio de flujo)
- Acción específica (final del flujo)

**🧭 4. JERARQUÍA SEMÁNTICA DEL SISTEMA**

Orden de prioridad de CTAs:

1.  **Acción final**
    - Enviar / Pagar / Confirmar
2.  **Progreso del flujo**
    - Continuar
3.  **Inicio del flujo**
    - Comenzar
4.  **Navegación inversa**
    - Regresar

**🧠 5. REGLA DE ORO**

“Los botones no describen navegación, describen la intención del usuario en el estado actual del flujo.”

**📦 6. USO EN EL CONTENT SYSTEM**

Esta regla se utiliza para:

- Diseño de flujos en Figma
- Auditoría UX Writing
- Generación de microcopy con IA (Sentinel Prime)
- Validación de consistencia en UI
- Diseño de sistemas de navegación

**🚀 OUTPUT FORMAT**

Este documento debe ser tratado como:

- Regla base de navegación en flujos
- Input obligatorio para prompts de IA
- Checklist de QA para UX Writing en productos bancarios

**🧩 INTEGRACIÓN CON SENTINEL PRIME**

Sentinel Prime debe aplicar esta regla para:

- Generar CTAs automáticamente en flujos
- Detectar inconsistencias (ej: uso de “Siguiente”)
- Validar jerarquía de botones
- Recomendar estados correctos según el flujo