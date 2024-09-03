# moviles-cam-corte-1-9022224362

[ver aqui] (https://trello.com/b/mFnpWQic/moviles-cam-corte-1-9022224362)

Perspectiva del Producto
El prototipo de la aplicación se desarrollará como una solución autónoma que proporcionará herramientas para identificar, categorizar y visualizar fuentes hídricas, bosques y fauna en la región del Alto Magdalena.
# Funcionalidades del Producto
Mapa Interactivo: Mostrar la ubicación de recursos naturales.  Permitir a los usuarios filtrar y buscar por tipo de  Implementar una identidad visual que respete los colores y logotipos de la CAR.
2.3 Usuarios del Producto
Ciudadanos: Personas interesadas en explorar los recursos naturales de la región.
Administradores: Personal autorizado para gestionar la información dentro de la aplicación.
# Restricciones Generales
La aplicación debe respetar los colores institucionales definidos por la CAR.
El desarrollo del prototipo se debe realizar en un entorno compatible con dispositivos móviles y web.
3. Requisitos Específicos
3.1 Requisitos Funcionales
RF-01: Visualización del Mapa Interactivo

 # La aplicación debe permitir a los usuarios visualizar un mapa interactivo con la ubicación de fuentes hídricas, bosques y fauna.
Entrada: Selección de categorías y filtros.
Salida: Mapa con marcadores diferenciados según la categoría seleccionada.
Dependencias: Base de datos con información georreferenciada de los recursos.
RF-02: Filtros y Búsqueda Avanzada

# La aplicación debe permitir a los usuarios aplicar filtros para visualizar recursos específicos.
Entrada: Criterios de búsqueda (tipo de recurso, ubicación, etc.).
Salida: Lista o visualización en el mapa de los recursos que coinciden con los criterios de búsqueda.
Dependencias: Implementación de la lógica de búsqueda y filtros en la base de datos.
RF-03: Gestión de Datos por Administradores

# La aplicación debe permitir a los administradores agregar, editar y eliminar registros de recursos naturales.
Entrada: Formulario con campos necesarios para cada tipo de recurso.
Salida: Actualización en la base de datos y en la visualización del mapa.
Dependencias: Sistema de autenticación y permisos de usuario.
RF-04: Identidad Visual

 # La aplicación debe utilizar los colores y logotipos institucionales de la CAR en todas las interfaces de usuario.
Entrada: Paleta de colores y logotipos proporcionados por la CAR.
Salida: Interfaces de usuario coherentes con la identidad visual de la CAR.
Dependencias: Directrices de identidad visual y diseño gráfico.
3.2 Requisitos No Funcionales
RNF-01: Rendimiento
 
 # La aplicación debe cargar el mapa interactivo en menos de 3 segundos en condiciones de conexión promedio.
Medición: Tiempo de carga medido en segundos.
Prioridad: Alta.
RNF-02: Seguridad

Descripción: La aplicación debe proteger la integridad y confidencialidad de los datos gestionados por los administradores.
Medición: Implementación de protocolos HTTPS y autenticación segura.
Prioridad: Alta.
RNF-03: Usabilidad

Descripción: La interfaz debe ser intuitiva y fácil de usar para usuarios no técnicos.
Medición: Evaluaciones de usabilidad con usuarios representativos.
Prioridad: Media.
RNF-04: Compatibilidad

Descripción: La aplicación debe ser compatible con navegadores web modernos y dispositivos móviles.
Medición: Pruebas de compatibilidad en diferentes dispositivos y navegadores.
Prioridad: Alta.
RNF-05: Escalabilidad
