# Laboratorio 1
## Robótica - Universidad Nacional De Colombia - Sede Bogotá
### Sebastián Cubides - Julián Velandia

- Diseño de la herramienta.

Para la herramienta del brazo, se realizó un acople que sujetaba un marcador y permitía que se contrajera por medio de un resorte, El ensamble se realizó con tubos de PVC.

https://raw.githubusercontent.com/SebastianCubides/ROBOTICA-2022-2/blob/main/images/herramienta2.jpeg


https://raw.githubusercontent.com/SebastianCubides/ROBOTICA-2022-2/main/images/herramienta2.jpeg


https://raw.githubusercontent.com/SebastianCubides/ROBOTICA-2022-2/main/images/herramienta3.jpeg


https://raw.githubusercontent.com/SebastianCubides/ROBOTICA-2022-2/main/images/herramienta4.jpeg


- Video que contenga la simulación en RobotStudio y con los robots reales.

Los videos de las simulaciones y de las implementaciones son los siguientes

[![Alt text](https://img.youtube.com/vi/j5a-MLhFNlY/0.jpg)](https://www.youtube.com/watch?v=j5a-MLhFNlY)

[![Alt text](https://img.youtube.com/vi/j5a-MLhFNlY/0.jpg)](https://www.youtube.com/watch?v=j5a-MLhFNlY)

- Descripción de la solución planteada.
    * Primero se diseñó el tablero usado como WorkObject y sobre el cual se planteó escribir. El modelo fue hecho en inventor tomando medidas del objeto original en el laboratorio.
    
    * Lo siguiente fue diseñar y construir la herramienta. Ésta se fabricó usando tubos y acoples de PVC, colocando bajo el marcador un resorte para prevenir daños durante la operación.
    
    * Despues se procedió a configurar los objetos modelados como WorkObject y Tool respectivamente, para así poder colocarlos en la estación de RobotStudio junto con el IRB140 y definir trayectorias, velocidades, posiciones, etc.
    
    * Tras realizado todo la anterior se sincronizó el contenido de la simulación en RobotStudio para generar el codigo RAPID.
    
    * Finalmente se exportó el código a una USB y se realizaron las operaciones correspondientes con el manipulador, la herramienta y el tablero en el laboratorio.