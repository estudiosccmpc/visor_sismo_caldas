# Visor Sismo municipios

Este visor permite explorar los registros empresariales reportados después del sismo en municipios de Caldas.

## Cómo abrirlo

1. Abra la carpeta `git`.
2. Haga doble clic en `index.html`.
3. Use preferiblemente una versión reciente de Chrome, Edge o Firefox.
4. Mantenga conexión a internet para cargar el estilo cartográfico institucional o la capa alternativa de OpenStreetMap. Los datos, la tipografía y las funciones del visor están incorporados en el archivo HTML.

## Organización del visor

- **Panel izquierdo:** reúne los filtros generales.
- **Mapa central:** permanece visible e incorpora selección por rectángulo o círculo, ajuste de puntos, restablecimiento, pantalla ampliada y cambio entre el estilo institucional y OpenStreetMap.
- **Panel derecho:** la navegación de secciones aparece inmediatamente encima del título y actualiza los gráficos.

Las cuatro secciones son: Panorama; Daños y criticidad; Empleo y liquidez; y Recuperación y atención.

## Lectura del mapa

- Los puntos turquesa corresponden a **303 registros** ubicados mediante una dirección o lugar georreferenciado.
- Los puntos naranjas agrupan **165 registros** ubicados en el centroide oficial de su municipio.
- Un centroide municipal es una ubicación referencial: no representa la dirección ni la ubicación exacta del establecimiento.
- El mapa abre con el mismo estilo institucional del visor de referencia. El menú de capas permite cambiar a OpenStreetMap y conserva visibles las atribuciones correspondientes.

## Alcance de la información

- Corte de respuestas: **21 de agosto de 2026**.
- Universo: **468 registros en 21 municipios**.
- Todos los registros tienen una coordenada para visualización: 303 georreferenciados por dirección o lugar y 165 ubicados de manera referencial en centroides municipales.
- 14 fechas de reporte están marcadas como “por revisar” o “sin fecha válida”; por eso el corte se basa en la fecha de respuesta.
- Los puestos de trabajo en riesgo se presentan como rangos. No se suman límites mínimos de intervalos.
- El monto corresponde a los recursos que la persona estimó necesarios para restablecer su operación.
- Los montos se presentan por rangos; no se publica una suma total porque existen valores atípicos y registros que requieren revisión.
- En reapertura, 0 días identifica registros que ya estaban operando o no reportaron espera.
- Los resultados describen las respuestas recibidas; no estiman el total de empresas afectadas en Caldas.

## Privacidad

El visor se construyó con la base pública estructurada y la base georreferenciada. No incluye razón social, nombres de contacto, documentos, teléfonos, correos ni textos abiertos. El archivo restringido de datos sensibles no forma parte del visor.

## Publicación en GitHub Pages

1. Cree un repositorio en GitHub y cargue `index.html` y `README.md` en la raíz.
2. Abra **Pages** en la configuración del repositorio.
3. Seleccione la rama principal y la carpeta raíz como fuente.
4. Guarde y espere a que GitHub muestre la dirección pública.

## Archivos

- `index.html`: visor con datos, Poppins, Leaflet, estilos y funcionalidades integrados. El fondo cartográfico consulta el estilo institucional de Mapbox y OpenStreetMap.
- `README.md`: guía de uso e interpretación.
