librerias necesarias para el funcionamiento del programa
os
PyPDF2
re
xlwt
tkinter
PIL (Pillow)
threading
sqlite3
pandas
matplotlib
imaplib
email
Funcionamiento del programa: 

El programa te permite extraer información de facturas en formato PDF y guardarla en un archivo Excel. Además, cuenta con una interfaz gráfica para facilitar su uso.
Funcionalidades:
Extraer datos de facturas PDF: El programa extrae información como el número de factura, la referencia, el total, la dirección de entrega, el folio fiscal y la fecha de factura.
Guardar la información en un archivo Excel: La información extraída se guarda en un archivo Excel con formato, incluyendo el formato de contabilidad para la columna "Total".
Interfaz gráfica: El programa cuenta con una interfaz gráfica que te permite ejecutar el script de extracción, borrar archivos PDF, visualizar los datos en un gráfico, agregar facturas desde una carpeta específica y salir del programa.Flujo del programa:

Al ejecutar el programa, se abre una interfaz gráfica con varios botones.
Puedes hacer clic en el botón "Extraer Datos" para ejecutar el script de extracción de datos.
El script extraer_pdf.py procesa las facturas PDF en la carpeta especificada y extrae la información relevante.
La información extraída se guarda en un archivo Excel con formato.
Puedes usar los otros botones de la interfaz para borrar archivos PDF, visualizar los datos en un gráfico, agregar facturas desde una carpeta específica o salir del programa.
Limitaciones:
El programa no puede extraer datos de tablas complejas o con estructuras variables.
La interfaz gráfica es básica y podría mejorarse visualmente.
El programa no incluye la funcionalidad de base de datos que se había implementado previamente.
