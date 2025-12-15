# mini_turtle_task

mini_turtle_task
Este proyecto es una implementación simple de un “turtle drawer” en Python que dibuja formas básicas en la consola usando texto ASCII. Es un ejercicio de modularidad funcional.

Descripción
El proyecto simula movimientos de una tortuga (turtle) para dibujar líneas horizontales y verticales, formando patrones como escalones. Las funciones principales son:

derecha(n): Dibuja una línea horizontal de n unidades hacia la derecha.
abajo(n): Dibuja una línea vertical de n unidades hacia abajo, incrementando el nivel de escalón.
reiniciar(): Reinicia el contador de escalones para comenzar un nuevo dibujo.
Requisitos
Python 3.x instalado en tu sistema.
Instalación
Clona o descarga este repositorio en tu máquina local.
Navega al directorio del proyecto: cd mini_turtle_task.
Uso
Ejecutar el ejemplo principal
Abre una terminal o línea de comandos.
Navega al directorio raíz del proyecto (donde se encuentra main.py).
Ejecuta el script principal con Python:

python main.py
Esto ejecutará el ejemplo que dibuja 3 escalones en la consola.

Usar el módulo en tu propio código
Importa las funciones en tu script Python:

from mini_turtle_task import derecha, abajo, reiniciar
Llama a las funciones para dibujar:

derecha(5)  # Dibuja una línea horizontal de 5 unidades
abajo(5)    # Dibuja una línea vertical de 5 unidades
reiniciar() # Reinicia para un nuevo dibujo
Ejecuta tu script con python tu_script.py.

Ejemplo de salida
Al ejecutar main.py, verás algo como:

---->
     |
     |
     |
     |
     V
     ---->
          |
          |
          |
          |
          V
          ---->
               |
               |
               |
               |
               V
Estructura del proyecto
main.py: Script principal que demuestra el uso del módulo.
mini_turtle_task/: Paquete del módulo.
__init__.py: Inicializa el paquete y exporta las funciones.
drawer_logic.py: Contiene la lógica de dibujo.
