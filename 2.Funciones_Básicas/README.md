¡Genial! Ahora pasemos a **Funciones Básicas en Excel**, pero con chistes y diversión. 😆  

---

## **2. Funciones Básicas en Excel** 🧮  

Si Excel fuera una escuela, las funciones básicas serían como aprender a sumar con los dedos. 🖐️➕🖐️ Pero tranquilo, aquí no hay examen sorpresa (o sí… 🤔).  

Las funciones básicas se dividen en:  
🔹 **Matemáticas:** SUMA, PROMEDIO, MAX, MIN, CONTAR, CONTARA  
🔹 **Condicionales:** SI, SI.ERROR, SI.CONJUNTO  
🔹 **Texto:** IZQUIERDA, DERECHA, EXTRAE, CONCATENAR, SUSTITUIR, MAYUSC, MINUSC  
🔹 **Fecha y Hora:** HOY, AHORA, AÑO, MES, DÍA, DIASEM, FECHA.DI

¡Vamos con las más usadas!  

---

### **📌 1. Funciones Matemáticas (Porque Excel es una calculadora con esteroides 💪)**
  
🔹 **SUMA:**  
💡 **Suma los valores de un rango de celdas**  
```excel
=SUMA(A1:A5)
```  
Ejemplo: Si en A1 tienes 10, en A2 tienes 20 y en A3 tienes 30, la fórmula `=SUMA(A1:A3)` te dará **60**.  

📢 **Chiste:**  
— Mamá, quiero ser matemático.  
— ¿Por qué, hijo?  
— Porque en Excel me la paso sumando problemas. 😂  

🔹 **PROMEDIO:**  
💡 **Calcula el promedio de un conjunto de números**  
```excel
=PROMEDIO(A1:A5)
```  
Si tienes las notas de un examen en **A1:A5**, esta función te dirá si pasaste… o si mejor huyes a otro país. 😆  

🔹 **MAX y MIN:**  
💡 **Encuentran el valor máximo y mínimo de un rango**  
```excel
=MAX(A1:A5)  ➝ Te dirá el número más grande.  
=MIN(A1:A5)  ➝ Te dirá el número más pequeño.  
```  
Ideal para saber quién sacó la mejor nota en un examen… y quién necesita rezar. 🙏😂  

🔹 **CONTAR y CONTARA:**  
💡 **Cuentan celdas con valores (numéricos o cualquier dato)**  
```excel
=CONTAR(A1:A10)   ➝ Cuenta solo números.  
=CONTARA(A1:A10)  ➝ Cuenta todo (números, texto, emojis 😆).  
```  
Si tienes una lista de alumnos, **CONTAR** te dirá cuántos asistieron… y **CONTARA** contará hasta los fantasmas. 👻  

---

### **📌 2. Funciones Condicionales (Porque Excel también toma decisiones 🤯)**  

🔹 **SI:**  
💡 **Evalúa si una condición es verdadera o falsa.**  
```excel
=SI(A1>50, "Aprobado", "Reprobado")
```  
Si A1 es mayor que 50, dirá **"Aprobado"**, si no, dirá **"Reprobado"**. (Ideal para fingir que eres profesor).  

📢 **Chiste:**  
— Mamá, en Excel me pusieron una condición.  
— ¿Y qué hiciste?  
— Usé `=SI()`, obvio. 😎  

🔹 **SI.ERROR:**  
💡 **Evita que aparezcan errores feos en tus fórmulas.**  
```excel
=SI.ERROR(A1/B1, "Error: No dividas por cero, loco")
```  
Si intentas dividir por cero, en lugar de un feo `#¡DIV/0!`, aparecerá el mensaje más bonito. 💅  

🔹 **SI.CONJUNTO:**  
💡 **Evalúa varias condiciones a la vez (mejor que SI tradicional).**  
```excel
=SI.CONJUNTO(A1>90, "Excelente", A1>70, "Bueno", A1>50, "Regular", A1<=50, "Reprobado")
```  
Ideal para ponerle calificaciones dramáticas a todo. 📊😂  

---

### **📌 3. Funciones de Texto (Porque a veces Excel es mejor escribiendo que nosotros 🤓)**  

🔹 **IZQUIERDA y DERECHA:**  
💡 **Extraen los primeros o últimos caracteres de un texto.**  
```excel
=IZQUIERDA(A1, 3)  ➝ Toma los primeros 3 caracteres.  
=DERECHA(A1, 2)    ➝ Toma los últimos 2 caracteres.  
```  
Si en **A1** tienes `"ChatGPT"`, `=IZQUIERDA(A1, 4)` te dará `"Chat"`, y `=DERECHA(A1, 2)` te dará `"PT"`.  

📢 **Chiste:**  
— ¿Cómo se llama el hermano menor de CONCATENAR?  
— IZQUIERDA. Porque siempre extrae lo primero. 😂  

🔹 **EXTRAE:**  
💡 **Extrae caracteres de un texto, pero desde el medio.**  
```excel
=EXTRAE(A1, 2, 3)  
```  
Si en **A1** tienes `"Excel"`, `=EXTRAE(A1, 2, 3)` te dará `"xce"`.  

🔹 **CONCATENAR y UNIRCADENAS:**  
💡 **Une dos textos en uno solo.**  
```excel
=CONCATENAR(A1, " es genial")
```
Si en **A1** tienes `"Excel"`, te mostrará `"Excel es genial"`.  
**Dato:** En versiones nuevas se usa `=CONCAT()` o `=UNIRCADENAS()`.  

---

### **📌 4. Funciones de Fecha y Hora (Porque Excel sabe qué día es… a diferencia de nosotros 😆)**  

🔹 **HOY y AHORA:**  
💡 **Te muestran la fecha y hora actual.**  
```excel
=HOY()   ➝ Devuelve la fecha actual.  
=AHORA() ➝ Devuelve fecha y hora actual.  
```  
Excel siempre está actualizado… ¡más que nuestro calendario mental! 😂  

🔹 **AÑO, MES, DÍA:**  
💡 **Extraen el año, mes o día de una fecha.**  
```excel
=AÑO(A1)   ➝ Te dará el año de la fecha en A1.  
=MES(A1)   ➝ Te dará el número del mes.  
=DÍA(A1)   ➝ Te dirá el día exacto.  
```  
Ideal para sacar cumpleaños… o calcular cuánto falta para las vacaciones. 🏖️  

🔹 **FECHA.DIF:**  
💡 **Calcula la diferencia entre dos fechas.**  
```excel
=FECHA.DIF(A1, B1, "Y")  
```  
Si **A1** es `"01/01/2000"` y **B1** es `"01/01/2025"`, te dirá **25** años. 😱  

---