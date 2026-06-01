**REGLAS DE MODALES – CONTENT SYSTEM**

**1\. Principios de escritura para modales**

**🧭 Contexto primero**

El usuario debe entender qué pasó antes de saber qué hacer.

**⚙️ Solución siempre visible**

Cuando hay una acción posible, el modal debe indicarla explícitamente.

**📝 Título activo**

El título debe resumir el estado en voz activa, no en sustantivos sueltos.

**🔘 CTA con verbo**

El botón debe decir claramente qué va a pasar cuando se presione.  
Nunca usar “Aceptar” como único CTA.

**2\. Tipos de modal**

Cada tarjeta define cuándo usarlo, la fórmula de escritura, el tono del Content System y un ejemplo aplicado.

**🔴 Error**

**Cuándo usarlo:**  
El sistema no pudo completar la acción. El usuario necesita saber qué falló y qué puede hacer.

**Fórmula:**

¿Qué no pude hacerse? + ¿Por qué, si aplica? + ¿Qué hacer ahora?

**Tono:**

- Directo
- Claro
- Sin alarmismo
- Sin signos de exclamación

**Ejemplo:**

- “No pudimos validar el código”
- “El código ingresado no es válido. Revísalo e intenta de nuevo.”

**CTA recomendado:**

- Reintentar

**🟡 Warning**

**Cuándo usarlo:**  
Hay una condición que impide continuar o que el usuario debe conocer antes de actuar.

**Fórmula:**

¿Cuál es la condición? + ¿Qué implica para el usuario? + ¿Próximo paso (si aplica)?

**Ejemplo:**

- “Este servicio no tiene valores pendientes”
- “Para registrarlo, debe tener un valor pendiente. Verifica el código o intenta otro servicio.”

**CTA recomendado:**

- Entendido

**🔵 Info**

**Cuándo usarlo:**  
El sistema comparte algo relevante que el usuario debe saber para continuar o decidir.

**Fórmula:**

¿Qué está pasando o qué está disponible? + ¿Qué puede hacer el usuario?

**Ejemplo:**

- “¿Necesitas más tiempo?”
- “Puedes agregar 20 minutos más para completar la solicitud.”

**CTA recomendado:**

- No, gracias
- Sí, agregar tiempo

**🟢 Éxito**

**Cuándo usarlo:**  
La acción se completó correctamente. El usuario necesita confirmación y siguiente paso.

**Fórmula:**

¿Qué se completó? + ¿Qué implica o qué sigue? (opcional)

**Ejemplo:**

- “¡Cambios guardados!”
- “Los cambios quedan guardados para tus futuros pagos.”

**CTA recomendado:**

- Cerrar
- Ver comprobante

**3\. Estructura del modal**

Cada modal debe contener:

**🧩 Icono**

- Diferencia visualmente el tipo de mensaje
- Alineado con el título
- Colores:
    - Rojo = error
    - Amarillo = warning
    - Azul = info
    - Verde = éxito

**🧾 Título**

- Resume el estado
- Voz activa
- Máximo 5 palabras
- Solo el modal de éxito puede incluir signo de exclamación

**📄 Cuerpo**

- Explica qué pasó y qué hacer
- Máximo 2 líneas
- No repetir el título
- Si hay más información, dividir en otro componente

**🔘 CTA**

- Uno o dos botones máximo
- El principal siempre con verbo de acción
- El secundario solo si existe alternativa real

**4\. CTAs por tipo de modal**

**🔴 Error**

- Primario: Reintentar / Volver a intentar / Revisar datos
- Secundario: Contactar soporte
- Evitar: Aceptar, OK, Entendido

**🟡 Warning**

- Primario: Entendido / Verificar
- Secundario: Continuar / Siguiente (solo si aplica)
- Evitar: Continuar sin contexto, Aceptar

**🔵 Info**

- Primario: Acción del contexto (Agregar, Guardar, Continuar)
- Secundario: No, gracias / Cancelar
- Evitar: Aceptar

**🟢 Éxito**

- Primario: Cerrar / Ver comprobante / Ir a inicio
- Secundario: Descargar comprobante (si aplica)
- Evitar: Aceptar, OK

**5\. Reglas generales del sistema**

- El título siempre tiene voz activa
- El cuerpo no repite el título, lo complementa
- No usar tecnicismos sin explicación
- No culpar al usuario
- No usar exclamaciones salvo en éxito
- Los modales no reemplazan toasts
- Si el modal tiene dos botones, el principal va a la derecha