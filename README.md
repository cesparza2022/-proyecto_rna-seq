# Proyecto_RNA-seq
## "MeCP2 represses the rate of transcriptional initiation of highly methylated long genes (RNA-Seq I)"
### *César F. Esparza Alvaradoo*
Universidad Nacional Autónoma de México - Licenciatura en ciencias genómicas

## Introducción
El síndrome de Rett es un trastorno genético raro que afecta principalmente a las niñas. Se estima que afecta a 1 de cada 10,000 a 15,000 niñas. El trastorno se produce por una mutación en el gen MECP2 que se encuentra en el cromosoma X. Esta mutación provoca una alteración en el desarrollo del cerebro y provoca una discapacidad intelectual grave y pérdida de habilidades motoras.

Los síntomas del síndrome de Rett pueden variar desde leves hasta graves. Los síntomas iniciales suelen aparecer en el primer año de vida y pueden incluir retraso en el desarrollo motor, pérdida del interés en los juguetes y una disminución en la comunicación con los demás. A medida que la niña crece, puede desarrollar otros síntomas como convulsiones, problemas respiratorios, escoliosis y problemas gastrointestinales.

La investigación actual sobre el síndrome de Rett se centra en entender la base molecular y celular de la enfermedad para desarrollar tratamientos efectivos. En particular, la expresión diferencial de genes puede proporcionar pistas importantes sobre los mecanismos subyacentes de la enfermedad y ofrecer posibles objetivos terapéuticos.

En estudios previos, se ha demostrado que la eliminación de la proteína MeCP2 provoca una alteración significativa en la expresión génica en el cerebro, lo que sugiere que la disfunción de MeCP2 puede contribuir a la patogénesis del síndrome de Rett. Por lo tanto, la identificación de genes diferencialmente expresados en ratones con síndrome de Rett puede proporcionar información valiosa sobre los procesos patológicos en la enfermedad.

En la investigación propuesta, se analizarán las diferencias en la expresión génica en muestras de cerebro de ratones con síndrome de Rett y ratones normales. Se espera que esta investigación proporcione información importante sobre los mecanismos subyacentes del síndrome de Rett y posibles objetivos terapéuticos para la enfermedad.

## Sobre los datos 
La base de datos consiste de 132 muestras de las que se extrae información para 7 características, que son:
* edad
* fracción celular 
* género 
* genotipo 
* fenotipo 
* cadena 
* procedencia de la muestra

![image](https://user-images.githubusercontent.com/100377746/222931652-cabe8473-8689-45ea-ae23-c22fd291cac2.png)

*figura 1. información sobre las características en la base de datos*

![image](https://user-images.githubusercontent.com/100377746/222933662-5f3936ec-def5-4df8-930f-655175275732.png)

*figura 2. información sobre niveles de expresión*

![image](https://user-images.githubusercontent.com/100377746/222933684-062bee6a-b1d1-4497-8651-1fbf282b94eb.png)

*figura 3. niveles de expresión*


## Control de calidad 
Al hacer una evaluación sobre la concentración de expresidn de los datos en relación con los atributos, se encontró una alta correspondencia con la carcterística de **fenotipo**. Esto se demustra en la siguiente imagen. 
![image](https://user-images.githubusercontent.com/100377746/222933511-b10fe3d6-188a-46cd-802a-0c7a98a6c67f.png)

*figura 4. relación entre calidad de los datos y el fenotipo*

Con esto se puede concluir que los niveles de expresión se enceuntran altamente relacionados con el atributo de **fenotipo**. En este caso, se puede ver que en la cromatina es donde menor expresión hay. 

![image](https://user-images.githubusercontent.com/100377746/222933626-5a239496-0a73-422d-a0d5-dfdbcd39433a.png)

*figura 5. información del fenotipo*

## Limpieza 
Se descartan las muestras que estan por debajo de un umbral de 0.3585, el cual representa el primer cuartil. La distribución resultante es la siguiente.

![image](https://user-images.githubusercontent.com/100377746/222933733-74618602-7c9d-4ff7-af88-14011a0b1124.png)

*figura 6. niveles de expresión despues de la limpieza*






## Resultados





