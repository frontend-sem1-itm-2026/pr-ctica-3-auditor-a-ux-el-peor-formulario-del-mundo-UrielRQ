En este archivo debes **listar los problemas encontrados** en el formulario.

Se recomienda clasificar los hallazgos usando las siguientes categorías:

### Categorías sugeridas

**UX (Experiencia de usuario)**  
- claridad del flujo: Debido a la escasez de recursos visuales y a la elección de tamaños de letra aleatorios no se percibe fácilmente qué elementos tienen mayor priodidad.
- botones confusos: Los colores causan confusión por repetir los mismos colores. Además están muy unidos y el orden no aclara su función. Tampoco funcionan. 
- acciones poco claras: Además de que las instrucciones aparecen en letras pequeñitas, dan la posibilidad de dar datos inexactos.

**Accesibilidad**  
- falta de labels: En la parte superior del input no se indica el dato al que corresponde.
- bajo contraste: Casi todo el documento está en tono de grises, restando importancia a secciones primordiales.
- problemas de navegación: La navbar no tiene referencias funcionales. Solo está adorno.

**Validación**  
- campos sin validación: El sitio no indica que campos se colocaron incorrectamemte, solo te arroja tener que llenarlo de nuevo.
- tipos incorrectos: la fecha es tipo "text" en lugar de "date".
- campos que deberían ser `required`: Todos los campos deberían ser 'required'  

**Jerarquía visual / Layout**  
- orden incorrecto: El email y la contraseña deberían ir juntos  
- agrupación deficiente: No es funcional que junte varios campos en uno (como lo es el caso de nacionalidad, religión y estado civil, que son uno solo).
- mala organización de campos

**Responsive**  
- problemas en pantalla móvil: Al no hacer uso de breakpoints np se cuenta diseño responsivo. Los botones incluso se salen de su 'contenedor'.
- layout que se rompe: Se oculta parte importante de la navbar, pues no se acopla al tamaño. 
- elementos demasiado grandes o pequeños: Hay textos demasiados pequeños como lo son las instrucciones y los elementos de la navbar.

**Contenido**  
- textos confusos: Se pierde veracidad en la información por enfatizar que pueden ser datos incorrectos.
- requisitos absurdos: Los checkbox de la parte final indican condiciones incoherentes. También pide datos innecesarios como la religión.
- instrucciones poco claras: El campo de contraseñas da libertad para elegir cualquier tipo de símbolo, lo cual puede ser problemático. También se pide escribir un texto que carece de propósito.

---

# 📊 Formato recomendado

Puedes usar una tabla como esta:

| # | Problema detectado | Categoría | Evidencia | ¿Por qué es un problema? |
|---|---|---|---|---|
| 1 | El campo nombre no tiene label | Accesibilidad | Campo “Nombre” | Los lectores de pantalla no pueden interpretarlo correctamente |
| 2 | Botón cancelar junto al enviar | UX | Botones al final | Puede provocar errores al usuario |
| 3 | Confirmar correo es opcional | Validación | Campo email | Puede causar inconsistencias |

Se recomienda identificar **al menos 10 problemas**.

---

# 📸 Evidencia visual

Además del archivo `AUDITORIA.md`, debes agregar **capturas de pantalla** del formulario.

Incluye al menos:

### 1️⃣ Vista en escritorio
Ventana normal del navegador.

### 2️⃣ Vista en móvil
Ventana reducida o modo responsive del navegador.

Puedes nombrarlas por ejemplo:
captura-escritorio.png
captura-movil.png

---
# 🚫 Regla importante

❌ **No debes modificar el HTML o CSS del formulario.**  

Esta actividad es únicamente de **análisis y auditoría**.
---

# 📦 Entrega

Realiza un **commit en tu repositorio** que incluya:

AUDITORIA.md
captura-escritorio.png
captura-movil.png


Mensaje de commit sugerido:
Auditoría UX del formulario: identificación de problemas de diseño


---

# 💡 Consejo

Piensa como un **usuario real** que intenta completar el formulario.

Si algo te confunde, probablemente **también confundirá a otros usuarios**.
