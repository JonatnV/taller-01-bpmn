# 📄 Informe Técnico del Taller

## 🔖 Nombre del Taller
_Taller 1 - Modelado de Proceso del Cliente con BPMN_

## 👥 Integrantes del equipo
- Jonatan David Vergara Suárez (github.com/JonatnV)
- Carlos David Bello Ortiz
- Jhojan Camilo Jiménez Amaya

## 🧠 Descripción general del trabajo
El taller tiene de objetivo, entender las actividades del cliente y partir de esto, lograr representar mediante un modelo, como funciona la operación
propuesta para su desglose y futura mejora.

## 🔧 Proceso de desarrollo
Despues de tener la reunión con el cliente y tener comprensión del proceso a trabajar, primero se entendio en pasos sin identificar a quien pertenecia
para entender como estaba compuesto de forma general el proceso, el cliente realiza una solicitud en base a unas necesidades o requisistos,
a partir de esto un miembro de comercialización, busca en el catalogo de productos, aquellos que cumplan los requisitos del cliente, posterior a esto
con las referencias seleccionadas, pasa a la base de datos a consultar el precio y beneficios con los que cuentan segun su proovedor, a partir de esto
luego estos manualmente realizan el calculo del precio teniendo en cuenta descuentos que les ofrece a ellos el , iva y los precios segun el margen de ganancia deseado, luego de esto se continua el proceso, segun se apruebe la cotización para ser preparado y despachado.

Luego de esto se tuvo en cuenta la involucración de sistema de ERP y CRM con los que cuenta la empresa, lo cual su función es principalmente, de registro de clientes, ventas y procesamiento de las cotizaciones.

Con esto se empezo el modelado siguiendo el proceso general descrito, especificando los pasos y que actor los realiza, luego se agrega actores que realizan
pocos pasos pero cruciales como administración que se encarga de realizar el proceso de facturación y aprobar el despacho una vez se tenga el pago


## 🧩 Análisis del modelo propuesto
El modelo esta estructurado, en la sección de recepción del pedido y formulación de los componentes que cumplen la necesidad de este, posteriormente en los
calculos y proceso de cotización y finalmente en el proceso de confirmación de cotización junto al pago para el despacho.

Esto representa las necesidades del cliente, mostrando los pasos manuales que debe realizar en sistemas no conectados, para poder obtener la información
requerida para concer los productos que puedan servir y con los que cuenten para proceder a la cotización de la cual tambien deben manualmente consultar y
realizar el calculo para la venta.

Los supuestos que se tomaron, fueron el uso del CRM durante este proceso y el ERP para registrar las ventas y clientes, ya que durante la explicación que 
se nos proveyo no fueron mencionados durante el proceso, pero en la explicación de sus operaciones se aclaro el uso de una base de datos para clientes, un erp para el inventario y un crm en el cual tienen registro de leads para realizar las cotizaciones, clientes para cotizaciones , cierre de ventas y entregas de bodega.

## 📈 Diagrama final entregado
![modelo-final](https://github.com/user-attachments/assets/5627d34e-a58f-4c82-8989-94f24222b3d3)



## 🔍 Investigación complementaria
### Tema investigado:
Buenas prácticas en BPMN

### Resumen:
La investigación sobre buenas prácticas en BPMN evidencia que un modelado 
efectivo no depende de usar todos los elementos disponibles en la notación, sino de 
aplicar criterios de claridad, simplicidad y coherencia. Según BPMN Best Practices 
[1], es fundamental mantener una estructura clara (flujo de izquierda a derecha), 
utilizar eventos de inicio y fin bien definidos, evitar cruces innecesarios de secuencia 
y emplear swimlanes para delimitar responsabilidades organizacionales. Asimismo, 
se recomienda no sobrecargar el diagrama con elementos avanzados si no aportan 
valor al entendimiento del proceso, privilegiando modelos comprensibles tanto para 
perfiles técnicos como de negocio. 
Por su parte, el artículo BPMN in practice: Real-world examples and case studies [2] 
muestra cómo estas buenas prácticas se aplican en la industria —por ejemplo, en 
procesos de aprobación de préstamos en banca o en optimización de procesos de 
manufactura— donde la claridad del modelo permitió identificar cuellos de botella, 
redundancias y oportunidades de automatización. Estos casos demuestran que un 
BPMN bien estructurado no solo sirve como herramienta de documentación, sino 
como base para la mejora continua y la transformación digital de procesos. 
En relación con el taller, la investigación respalda la importancia de modelar 
procesos siguiendo estándares formales y criterios de calidad. Aplicar estas buenas 
prácticas en el ejercicio del taller permite construir diagramas más profesionales, 
comprensibles y alineados con la realidad organizacional, facilitando tanto el análisis 
del proceso actual (AS-IS) como la propuesta de mejoras (TO-BE). De esta manera, el 
uso correcto de BPMN no solo cumple con un requisito técnico, sino que se convierte 
en una herramienta estratégica para la toma de decisiones y la optimización de 
procesos.

## 📚 Referencias
- [1] “BPMN Best Practices”. https://bpmn.page/article/BPMN_Best_Practices.html
- [2] “BPMN in practice: Real-world examples and case studies”. https://bpmn.page/article/BPMN_in_practice_Realworld_examples_and_case
_studies.html

---

_Este documento hace parte de la entrega del taller X del curso AREM (Arquitectura Empresarial) - Universidad de La Sabana._
