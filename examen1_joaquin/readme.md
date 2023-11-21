# Informe de Examen
[License](https://github.com/SR2A/Joaquin_Allauca_Vargas_Exam1.git)

## Presentación
![Logo del Repositorio](https://www.cicerocomunicacion.es/wp-content/uploads/2019/04/presentacion-corporativa.png)
*Descripción de la imagen de presentación*

## Licencia
[Archivo de Licencia](enlace_al_archivo_de_licencia)
*Este repositorio está bajo la Licencia XYZ. Consulte el archivo de licencia para obtener más detalles.*

## Preguntas del Examen
### 1.Mayores debilidades y fortalezas de GitHub basado en las indagaciones que hicisteis en el ejercicio 4
### Fortalezas de GitHub:

1. **Colaboración Eficiente:**
   - GitHub facilita la colaboración entre desarrolladores, permitiendo contribuciones simultáneas y gestión de conflictos de manera efectiva.

2. **Control de Versiones:**
   - Utiliza Git como sistema de control de versiones, lo que permite un seguimiento preciso de cambios en el código y la reversión a versiones anteriores.

3. **Amplia Integración:**
   - Ofrece integración con una amplia gama de herramientas y servicios, facilitando la automatización de flujos de trabajo y la implementación continua.

4. **Gestión de Proyectos:**
   - GitHub proporciona funciones de gestión de proyectos y tableros Kanban que ayudan en la organización y seguimiento de tareas.

5. **Despliegue Automático:**
   - La integración con servicios de implementación continua permite el despliegue automático de aplicaciones directamente desde el repositorio.

6. **Seguridad:**
   - Ofrece herramientas como Code Scanning, Dependabot, y análisis de secretos para mejorar la seguridad del código y las dependencias.

### Debilidades de GitHub:

1. **Privacidad Limitada en Repositorios Públicos:**
   - Aunque GitHub permite repositorios privados, las funciones avanzadas de seguridad a menudo requieren suscripciones de pago.

2. **Aprendizaje Inicial:**
   - Para usuarios nuevos, especialmente aquellos menos familiarizados con Git, puede haber una curva de aprendizaje al principio.

3. **Dependencia de Conexión a Internet:**
   - GitHub opera en línea, por lo que se requiere una conexión a Internet para acceder a repositorios y realizar operaciones básicas.

4. **Costo en Funciones Avanzadas:**
   - Algunas funciones de seguridad avanzadas, como Code Scanning, están disponibles solo con GitHub Advanced Security, que tiene un costo asociado.

5. **Gestión de Archivos Binarios:**
   - Git (y, por ende, GitHub) no maneja tan eficientemente los archivos binarios grandes como los archivos de texto, lo que puede afectar el rendimiento.

6. **Dependencia de la Comunidad:**

###2.Propón salvaguardas para evitar la filtración de datos de los exámenes entre grupos e incluso dentro del mismo grupo cuando los exámenes se dividen en dos grupos
### Salvaguardas para Evitar Filtración de Datos de Exámenes

1. **Separación de Acceso:**
   - **Descripción:** Asignar accesos específicos a los exámenes basados en roles y responsabilidades.
   - **Implementación:**
     ```markdown
     - Crear roles distintos para administradores, profesores y estudiantes.
     - Limitar el acceso a la información del examen según el rol.
     ```

2. **Encriptación de Contenidos:**
   - **Descripción:** Aplicar encriptación a los documentos de examen para evitar lecturas no autorizadas.
   - **Implementación:**
     ```markdown
     - Utilizar herramientas de encriptación para proteger los archivos de examen.
     - Compartir claves de desencriptación solo con personal autorizado.
     ```

3. **Control de Versiones:**
   - **Descripción:** Rastrear y gestionar versiones de exámenes para evitar cambios no autorizados.
   - **Implementación:**
     ```markdown
     - Utilizar sistemas de control de versiones como Git para rastrear cambios.
     - Restringir la capacidad de modificación a personas autorizadas.
     ```

4. **Acceso Basado en Token:**
   - **Descripción:** Utilizar tokens de acceso para garantizar que solo personas autorizadas puedan descargar o ver los exámenes.
   - **Implementación:**
     ```markdown
     - Generar tokens de acceso únicos para cada usuario autorizado.
     - Vincular la descarga de exámenes a la validación de tokens.
     ```

5. **Auditoría y Registros:**
   - **Descripción:** Registrar actividades relacionadas con los exámenes para realizar auditorías en caso de sospechas de filtración.
   - **Implementación:**
     ```markdown
     - Registrar todas las interacciones con los documentos de examen.
     - Revisar periódicamente los registros para detectar patrones sospechosos.
     ```

6. **Restricciones de Copia y Pegado:**
   - **Descripción:** Evitar la posibilidad de copiar y pegar contenido del examen.
   - **Implementación:**
     ```markdown
     - Utilizar formatos de visualización que no permitan la copia de texto.
     - Desactivar la funcionalidad de copiar y pegar en documentos protegidos.
     ```

7. **Comunicación Segura:**
   - **Descripción:** Garantizar que la comunicación relacionada con los exámenes sea segura y privada.
   - **Implementación:**
     ```markdown
     - Utilizar canales de comunicación seguros, como correos electrónicos cifrados.
     - Evitar compartir información sensible en plataformas no seguras.
     ```

Estas salvaguardas buscan proteger la integridad y confidencialidad de los exámenes, asegurando que solo personas autorizadas tengan acceso a la información.

   - La calidad de la experiencia en GitHub puede depender de la comunidad que rodea un proyecto, y algunos proyectos pueden carecer de contribuciones activas o soporte.
###3.Explicar brevemente el funcionamiento de la máquina Enigma
### Funcionamiento de la Máquina Enigma

La Máquina Enigma fue un dispositivo de cifrado utilizado por las fuerzas alemanas durante la Segunda Guerra Mundial para cifrar y descifrar mensajes. Su funcionamiento se puede resumir en los siguientes pasos:

1. **Rotores:**
   - La máquina Enigma utilizaba rotores, discos con contactos eléctricos que representaban letras del alfabeto. Cada rotor tenía una disposición única de conexiones.

2. **Conexiones Eléctricas:**
   - Cada letra del teclado estaba conectada a través de una serie de rotores, estableciendo un camino eléctrico complejo que cambiaba con cada pulsación de tecla.

3. **Posición Inicial de Rotores:**
   - La posición inicial de los rotores, conocida como configuración inicial, afectaba la disposición de las conexiones eléctricas y, por lo tanto, el cifrado resultante.

4. **Reflector:**
   - Después de pasar a través de los rotores, la corriente eléctrica llegaba a un reflector que invertía la señal, enviándola de vuelta a través de los rotores para obtener la letra cifrada final.

5. **Configuración Diaria:**
   - La configuración de los rotores se cambiaba diariamente según un código de configuración previamente establecido, lo que hacía que la máquina fuera difícil de descifrar incluso si se conocía la disposición de los rotores.

6. **Anillos de Rotor:**
   - Los anillos en los rotores permitían cambiar la posición inicial de las conexiones eléctricas, aumentando la complejidad del cifrado.

7. **Mensaje Cifrado:**
   - Al ingresar un mensaje en el teclado, la máquina Enigma cifraba cada letra de forma única, generando un mensaje cifrado que podía ser transmitido de manera
