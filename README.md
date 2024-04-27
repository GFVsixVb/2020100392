Configuración de ROS: Asegúrate de tener ROS instalado en tu sistema. Si aún no lo tienes, puedes seguir las instrucciones de instalación en el sitio web oficial de ROS.
Configuración del espacio de trabajo de catkin: Crea un nuevo espacio de trabajo de catkin si no tienes uno ya configurado. 
Crear un paquete de ROS: En el directorio src de tu espacio de trabajo, crea un nuevo paquete de ROS. Por ejemplo, podrías llamarlo turtle_controller.

Escribe el código del nodo de controlador de tortuga: Abre tu editor de texto favorito y crea un archivo Python dentro del directorio src de tu paquete turtle_controller. Por ejemplo, podrías llamarlo turtle_controller_node.py.
python
Iniciar el entorno de ROS: Antes de ejecutar tu nodo, debes iniciar el entorno de ROS ejecutando roscore en una terminal separada.

luego en otra terminar escribir devel\setup y iniciar la tortuga con el siguiente comando>

rosrun turtlesum turtlesim_node

y en otra terminal volver a iniciar el devel\setup y escribir algun codigo de movimiento como por ejemplo:

rosrun turtle_unida src/mover.py
