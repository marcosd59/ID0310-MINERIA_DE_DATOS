## Minería de Datos: Primer Examen Parcial

### Instrucciones

Lee con atención y resuelve lo que se solicita:

#### 1. Exploración de Datos (10 pts)

- **Análisis:** Investiga términos desconocidos y analiza los datos.
- **Pregunta Clave:** ¿Es necesario estandarizar los datos?

#### 2. Preparación de Datos (30 pts)

- **Conversión a Numérico:** Convierte los datos para obtener valores numéricos, eliminando las variables categóricas.
- **Indexación:** Utiliza el ID del cliente como índice en tu dataframe.
- **Columna de Ingresos:** No elimines esta columna. Analiza los valores y decide la mejor forma de manejarlos, justificando tu decisión.
- **Limpieza de Datos:** Identifica y maneja datos atípicos o nulos. Selecciona un enfoque de limpieza (3 o 5 desviaciones estándar) para la segmentación.

#### 3. Segmentación de Datos (20 pts)

- **K-Means:** Aplica la técnica del codo para realizar una segmentación con k means.
- **Determinación de Grupos:** Decide cuántos grupos son ideales.

#### 4. Perfilado de Clientes (10 pts)

- **Análisis de Grupos:** Perfila a los clientes según los grupos identificados.

#### 5. Graficando los Resultados (30 pts)

- **Reducción de Dimensiones:** Si hay muchas dimensiones, reduce los datos a 2 componentes principales (PCA).
- **Gráfica de Dispersión:** Crea una gráfica de dispersión con los 2 componentes principales, representando cada grupo segmentado con un color diferente.

### Dataset: “CreditCard_Customer_Data_Bank_Segmentation.csv”

#### Descripción del Archivo

- **ID_Customer:** Identificador único para cada cliente. (Entero)
- **Customer_Age:** Edad del cliente. (Entero)
- **Gender:** Género del cliente. (Cadena)
- **Dependent_count:** Número de dependientes que tiene el cliente. (Entero)
- **Income_Category:** Categoría de ingresos del cliente. (Cadena)
- **Months_on_book:** Tiempo que el cliente ha estado registrado. (Entero)
- **Total_Relationship_Count:** Número total de relaciones que el cliente tiene con el proveedor de la tarjeta de crédito. (Entero)
- **Months_Inactive_12_mon:** Número de meses que el cliente ha estado inactivo en los últimos doce meses. (Entero)
- **Contacts_Count_12_mon:** Número de contactos que el cliente ha tenido en los últimos doce meses. (Entero)
- **Credit_Limit:** Límite de crédito del cliente. (Entero)
- **Total_Revolving_Bal:** Saldo revolvente total del cliente. (Entero)
- **Avg_Open_To_Buy:** Promedio de ratio de compra abierta del cliente. (Entero)
- **Total_Trans_Amt:** Monto total de la transacción. (Entero)
- **Total_Trans_Ct:** Recuento total de transacciones. (Entero)
- **Avg_Utilization_Ratio:** Ratio de utilización promedio del cliente. (Entero)
