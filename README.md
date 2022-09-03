# Laboratorio 1
## Robótica - Universidad Nacional De Colombia - Sede Bogotá
### Sebastián Cubides - Julián Velandia

- Diseño de la herramienta.

Para la herramienta del brazo, se realizó un acople que sujetaba un marcador y permitía que se contrajera por medio de un resorte, El ensamble se realizó con tubos de PVC.

![image 1](https://raw.githubusercontent.com/SebastianCubides/ROBOTICA-2022-2/main/LAB1/images/herramiente1.jpeg)

![image 2](https://raw.githubusercontent.com/SebastianCubides/ROBOTICA-2022-2/main/LAB1/images/herramienta2.jpeg)

![image 3](https://raw.githubusercontent.com/SebastianCubides/ROBOTICA-2022-2/main/LAB1/images/herramienta3.jpeg)

![image 4](https://raw.githubusercontent.com/SebastianCubides/ROBOTICA-2022-2/main/LAB1/images/herramienta4.jpeg)

- Video que contenga la simulación en RobotStudio y con los robots reales.

Los videos de las simulaciones y de las implementaciones son los siguientes

[![Alt text](https://img.youtube.com/vi/6qXpsAbg4Cc/0.jpg)](https://www.youtube.com/watch?v=6qXpsAbg4Cc)

[![Alt text](https://img.youtube.com/vi/j5a-MLhFNlY/0.jpg)](https://www.youtube.com/watch?v=j5a-MLhFNlY)

[![Alt text](https://img.youtube.com/vi/TcdCo_RbKVI/0.jpg)](https://www.youtube.com/watch?v=TcdCo_RbKVI)

- Descripción de la solución planteada.
    * Primero se diseñó el tablero usado como WorkObject y sobre el cual se planteó escribir. El modelo fue hecho en inventor tomando medidas del objeto original en el laboratorio.
    
    * Lo siguiente fue diseñar y construir la herramienta. Ésta se fabricó usando tubos y acoples de PVC, colocando bajo el marcador un resorte para prevenir daños durante la operación.
    
    * Despues se procedió a configurar los objetos modelados como WorkObject y Tool respectivamente, para así poder colocarlos en la estación de RobotStudio junto con el IRB140 y definir trayectorias, velocidades, posiciones, etc.
    
    * Tras realizado todo la anterior se sincronizó el contenido de la simulación en RobotStudio para generar el codigo RAPID.
    
    * Finalmente se exportó el código a una USB y se realizaron las operaciones correspondientes con el manipulador, la herramienta y el tablero en el laboratorio.

- Descripción de archivos y carpetas.
    - HERRAMIENTAS contiene los archivos del modelado CAD de la herramienta y su creación como librería.
    - PROGRAMA_LAB1_RS Contiene los archivos del código rapid (el código principal quedó con el nombre "YYY")
    - LAB1RS contiene los archivos de la estación de RobotStudio donde se configuró toda la operación y se hicieron las simulaciones.
    - images contiene las fotografías tomadas como evidencia.
    - En LAB1 se encuentran los archivos CAD del tablero.