Proyecto basado en LLM para identificar, mediante el relato de admisión de un paciente, la parte del cuerpo lesionada.

# Contexto:
Se busca generar nuevos datos de los pacientes, basado en la información recopilada durante su atención médica.

# Datos disponibles:
Contamos con una base de datos de pacientes, los cuales se identifican por un código, y cuentan con el campo "relato_admision", texto libre ingresado por la ejecutiva al ingreso del paciente al recinto de salud. Se consideran ingresos de pacientes relacionados a un incidentes "físico".

Por otra parte, se debe definir un listado de partes del cuerpo específico, ya que este será entregado en el prompt al modelo de lenguaje para acotar las respuestas esperadas. Para ello, generamos el siguiente listado, basado en el CIE-10, capítulo Diagnósticos (añadir referencia):

(agregar lista)


