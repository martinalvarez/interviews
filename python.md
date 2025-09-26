# Python

**Stack**: React, Node.js, PostgreSQL  
**Duración**: 45 min  
**Entrevistador**: Juan Pérez

https://www.youtube.com/watch?v=u77Az26bFPA

## Concurrencia
La concurrencia es un concepto general en ciencias de la computación y en la vida real:

## ➡️ Definición general:
Concurrencia es la capacidad de manejar varias tareas al mismo tiempo, pero no necesariamente de manera simultánea. Es la idea de organizar el trabajo de manera que se pueda progresar en varias actividades dentro de un mismo período de tiempo.

Ejemplo en la vida cotidiana
Imaginá que estás cocinando:
Ponés agua a hervir (tarda varios minutos).
Mientras el agua hierve, picás verduras.
Después controlás el horno.

👉 No hacés todo a la vez en paralelo (no tenés tres clones tuyos), pero organizás las tareas para que avancen intercaladamente sin que el tiempo de espera se pierda.
Eso es concurrencia.

Diferencia con paralelismo
Concurrencia: resolver varias tareas en el mismo intervalo de tiempo, intercalándolas.
Paralelismo: resolver varias tareas literalmente al mismo tiempo con recursos separados (por ejemplo, varios procesadores).

🔹 Concurrencia es más sobre organización.
🔹 Paralelismo es más sobre ejecución simultánea real.

En informática
Concurrencia: un solo procesador puede cambiar rápido entre tareas (multitarea), de modo que parece que todas avanzan.
Paralelismo: múltiples procesadores/hilos ejecutando cosas a la vez, de verdad.

Ejemplo clásico:
Concurrencia: un solo CPU ejecutando muchas pestañas del navegador a la vez.
Paralelismo: un servidor con 8 núcleos ejecutando 8 procesos pesados al mismo tiempo.

## En español:
La concurrencia es la capacidad de un sistema para manejar múltiples tareas a la vez, intercalando su ejecución en el tiempo para que todas avancen de manera aparentemente simultánea.

## In English:
Concurrency is the ability of a system to handle multiple tasks at once by interleaving their execution over time so they progress seemingly simultaneously.

## Concurrency
- Concurrency in Python allows multiple tasks to be executed simultaneously using different approaches. GIL (Global Interpreter Lock) limits thread execution, making multithreading less efficient for computational tasks, but suitable for I/O. Multiprocessing, using the multiprocessing module, allows multiple cores to be utilized, providing true parallelism. Asynchrony via asyncio is optimal for I/O operations, allowing thousands of connections to be processed simultaneously without blocking. The choice of approach depends on the nature of the task.

## Cosas a preguntar
- Modalidad de pago (transferencia, Payoneer, etc).
- Vacaciones: ¿cómo se manejan?
- Horas de trabajo: ¿cómo distribuyen las 10hs diarias?

## Links
- [Documentación de la empresa](https://empresa.com/docs)
- [Artículo sobre SOLID](https://enlace.com/solid)
