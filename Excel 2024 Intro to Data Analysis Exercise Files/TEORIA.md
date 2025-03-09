  
---

## Insertar Tablas para Análisis  
### Hoja: Creating Tables  

Antes de comenzar a trabajar con nuestros datos, debemos asegurarnos de que estén correctamente estructurados. Para ello, seguimos los siguientes pasos:  

### 1. Verificación de los Datos  
Antes de convertir el rango en una tabla, verificamos lo siguiente:  

- **Encabezados**: La primera fila debe contener nombres claros y representativos para cada columna.  
- **Valores o Etiquetas**: Los datos deben estar correctamente etiquetados y organizados.  
- **Celdas en Blanco**: No debe haber celdas vacías dentro del conjunto de datos.  

  Para verificar la presencia de celdas en blanco, usamos la función:  
  ```excel
  =CONTAR.BLANCO(rango_datos)
  ```
  Esta fórmula nos indicará cuántas celdas vacías hay en el rango seleccionado.  

### 2. Formateo de los Datos  
Es importante asegurarse de que los datos tengan el formato adecuado:  
- **Números**: Deben estar configurados como tipo de dato "Número".  
- **Fechas**: Deben estar en formato de fecha para evitar problemas en cálculos o filtros.  
- **Texto**: Debe estar correctamente escrito y sin errores tipográficos.  

### 3. Convertir el Rango en Tabla  
Una vez que hemos verificado y formateado los datos, podemos convertir el rango en una tabla usando el atajo de teclado:  
```  
CTRL + T  
```  
Este atajo abre la ventana de creación de tabla, donde confirmamos que los datos tienen encabezados.  

### 4. Opciones Disponibles en una Tabla  
Al convertir el rango en tabla, podemos:  
- **Ordenar** los datos.  
- **Filtrar** la información según criterios específicos.  
- **Ver filas totales** para cálculos automáticos como sumas o promedios.  

### 5. Ordenar Datos en la Tabla  
Para ordenar los datos dentro de la tabla:  
- Usamos el filtro (icono en los encabezados de la tabla).  
- Para ordenar varias columnas al mismo tiempo, seguimos estos pasos:  

  **Paso 1:** Ir a **Inicio > Edición > Ordenar y Filtrar > Orden Personalizado**.  
  ![Paso 1](./img/1.png)  

  **Paso 2:** Hacer clic en "Orden personalizado".  
  ![Paso 2](./img/2.png)  

  **Paso 3:** Se abrirá una ventana donde podemos agregar niveles para ordenar varias columnas.  
  ![Paso 3](./img/3.png)  

Así podemos estructurar mejor nuestros datos y analizarlos con mayor facilidad.