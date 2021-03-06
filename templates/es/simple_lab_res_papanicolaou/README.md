# Resultado de estudio de papanicolaou

## Resumen

Los estudios de detección del cáncer cervical son una parte importante de la prevención
del cáncer o su detección temprana. Se utilizan dos pruebas para la detección: la prueba
de Papanicolaou (o frotis) y la prueba de VPH. La prueba de Papanicolaou analiza cambios
celulares en el cuello uterino de la mujer que podrían convertirse en cáncer si no se tratan.
La prueba del VPH es para detectar el virus del papiloma humano (VPH). El virus puede causar
cambios celulares que conducen al cáncer de cuello uterino.

También llamado citología cervical, citología vaginal, frotis vaginal o prueba de papanicolaou.

Fuente: https://es.familydoctor.org/interpretacion-de-resultados-de-prueba-de-papanicolaou/
Fuente: https://www.webconsultas.com/pruebas-medicas/citologia-cervical-8079

## Descripción

Esta plantilla busca el registro/reporte de los distintos resultados que puede tener
un estudio de pap en una paciente femenina.

El reporte estará compuesto de un resultado codificado más un comentario en texto
narrativo para opcionalmente agregar detalles que escapen a la codificación.

La plantilla de base es genérica para cualquier resultado de estudios, para lo que es
necesario establecer la estructura para un tipo específico de estudios en tiempo de
ejecución, además de codificando cada tipo de resultado con el código del estudio
correspondiente, intentando usar LOINC para eso.


## Codificación

El procedimiento (determinación) puede codificarse en SNOMED-CT: 168440009 | examen citológico general (procedimiento) |

Los resultados para este tipo de estudio tienen algunos código en SNOMED CT:
http://browser.ihtsdotools.org/?perspective=full&conceptId1=404684003&edition=es-edition&release=v20180430&server=https://prod-browser-exten.ihtsdotools.org/api/snomed&langRefset=450828004

+ Normal (negativo): SNOMED-CT::5559008
+ Poco claro (no concluyente)
+ Anormal (positivo)
  + CEASI o ASCUS (células escamosas atípicas de signigicado indeterminado): SNOMED-CT::39035006
  + CGA (células grandulares atípicas): SNOMED-CT::4476003
  + LIEBG (lesiones intraepiteliales escamosas de grado bajo): SNOMED-CT::112662005
  + LIEAG (lesiones intraepiteliales escamosas de grado alto): SNOMED-CT::22725004
  + CEA (células escamosas atípicas, no se pueden excluir las LIEAG): SNOMED-CT::373878001
  + AIS (adenocarcinoma in situ): SNOMED-CT::51642000
  + Células de cáncer cervical (carcinoma de células escamosas o adenocarcinoma): SNOMED-CT::285432005