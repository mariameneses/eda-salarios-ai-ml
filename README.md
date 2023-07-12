# <b><div style='padding:15px;background-color:#0097b2;color:white;border-radius:10px;font-size:110%;text-align: center'>Análisis exploratorio de datos de salarios de AI/ML </div></b>

En este desarrollo se realiza una exploración y visualización de datos salariales de profesionales en los campos de la Inteligencia Artificial (AI) y Aprendizaje Automático (ML). Desarrollo disponible en el siguiente [enlace](https://colab.research.google.com/github/mariameneses/eda-salarios-ai-ml/blob/notebooks/codes/eda_visualizacion_salarios_ai_ml.ipynb).

Los datos provienen de [ai-jobs.net](https://ai-jobs.net/). Ai-jobs recolecta información de salarios, de forma anónima, de profesionales en los campos de AI/ML y Big Data, y la pone a disposición del público para que cualquiera pueda usarla, compartirla y jugar con ella.

## Descripción

<div>
  <h3>Tabla de contenido del desarrollo</h3>
  <ol>
      <li>Importar librerías</li>
      <li>Carga de conjunto de datos</li>
      <li>Entendimiento del conjunto de datos</li>
      <li>Evaluación del conjunto de datos</li>
      <li>Exploración univariada</li>
          <ol>
              <li>Distribución de los salarios en USD</li>
              <li>Exploración de títulos de empleos</li>
              <li>Exploración de los niveles de experiencia</li>
              <li>Exploración de los tipos de contratación</li>
              <li>Exploración de los tamaños de las empresas</li>
              <li>Exploración de los años de pago del salario</li>
              <li>Exploración del tipo de trabajo</li>
              <li>Exploración de las ubicaciones de las empresas</li>
              <li>Exploración de las ubicaciones de residencia de los empleados</li>
          </ol>
      <li>Exploración bivariada</li>
          <ol>
              <li>Relaciones entre características categóricas limitadas</li>
              <li>Relaciones entre características categóricas limitadas y el salario</li>
              <li>Relaciones entre características categóricas y el salario en USD</li>
          </ol>
      <li>Conclusiones</li>
  </ol>
<div>

## Detalles de implementación

La implementación se realiza en la herramienta Google Colaboratory (Colab).

## Algunas gráficas obtenidas

### Exploración univariada

<image
    src="./images/dist-salarios.jpg"
    alt="Distribución de salarios en USD"
    caption="Distribución de salarios en USD">

<image
    src="./images/top-titulos-empleos.jpg"
    alt="Top 10 de titulos de empleos o roles más frecuentes"
    caption="Top 10 de titulos de empleos o roles más frecuentes">

### Exploración bivariada

<image
    src="./images/cajas-bigotes-salarios-años.jpg"
    alt="Diagrama de la relación entre salario en USD por año pagado"
    caption="Diagrama de la relación entre salario en USD por año pagado">

<image
    src="./images/salario-años.jpg"
    alt="Gráfica de salario promedio en USD por año pagado"
    caption="Gráfica de salario promedio en USD por año pagado">

<image
    src="./images/salario-experiencia.jpg"
    alt="Gráfica de salario promedio en USD por nivel de experiencia"
    caption="Gráfica de salario promedio en USD por nivel de experiencia">

<image
    src="./images/salario-ubicacion-empleados.jpg"
    alt="Gráfica de salario promedio en USD para las 5 ubicaciones de empleado más frecuentes"
    caption="Gráfica de salario promedio en USD para las 5 ubicaciones de empleado más frecuentes">

<image
    src="./images/mapa-salario-ubicacion-empleado.jpg"
    alt="Mapa de salario por ubicacion de empleado"
    caption="Mapa de salario por ubicacion de empleado">

<image
    src="./images/mapa-salario-ubicacion-empresa.jpg"
    alt="Mapa de salario por ubicacion de empresa"
    caption="Mapa de salario por ubicacion de empresa">

<image
    src="./images/salario-top-roles.jpg"
    alt="Gráfica de salario promedio en USD para los 10 titulos de empleos o roles más frecuentes"
    caption="Gráfica de salario promedio en USD para los 10 titulos de empleos o roles más frecuentes">

## Conclusiones

A partir de la exploración de los datos, se evidencia que en promedio los salarios aumentan conforme avanzan los años y de igual manera a medida que el empleado obtiene más experiencia. Además, el salario se mantiene similar para los empleados que trabajen de forma completamente remota o completamente presencial.

También se observa gran variedad de roles en el área de Inteligencia Artificial (AI) y Aprendizaje Automático (ML) que en general presentan salarios promedios similares.

Sin embargo, se presenta una dependencia de los salarios y la ubicación del empleado o la empresa, exponiendo mayores valores para los países de Estados Unidos y Canadá.

Hay que tener en cuenta que la base de datos contiene en su mayoría datos de empleados ubicados en Estados Unidos o empleados de empresas ubicadas en este país y se tiene una escaza representación de otros países.