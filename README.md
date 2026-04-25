El sistema FAS es una aplicación web para la gestión de un restaurante que permite a los clientes navegar 
por diferentes secciones como el menú, bebidas, reservaciones, boletín, ticket y perfil. Su objetivo principal 
es facilitar la experiencia del usuario al momento de consultar productos, seleccionar mesas y realizar reservaciones de forma digital.

La interfaz principal funciona como punto de entrada del sistema, donde el usuario puede acceder a todas las demás 
secciones. Desde ahí se puede ir al menú de alimentos, donde se muestran los platillos disponibles con la opción de ver 
sus ingredientes de manera dinámica mediante JavaScript. De forma similar, la sección de bebidas muestra las opciones
disponibles como refrescos, jugos y café, también con interacción para ver detalles.

El sistema de reservaciones permite al usuario seleccionar una mesa dentro de un mapa del restaurante, así como elegir una
fecha y hora. Durante este proceso se muestra un resumen en tiempo real con los datos seleccionados. Una vez confirmada la
reservación, la información se guarda en el almacenamiento local del navegador para poder ser utilizada en otras pantallas del sistema.

Después de confirmar la reservación, el sistema muestra una pantalla de éxito donde se presentan los datos completos
del cliente, la mesa seleccionada, la zona, la fecha y la hora. En esta misma pantalla se genera un código QR que representa 
la reservación y puede ser utilizado como comprobante. También existe la opción de generar un ticket con la información de la reservación.

El perfil del cliente permite visualizar y mantener la información personal, así como consultar la última reservación realizada.
Esta sección se actualiza automáticamente con los datos almacenados en el sistema, mostrando la mesa, la fecha y la zona seleccionada.

En general, el flujo del sistema inicia en el panel principal, continúa con la selección de productos o mesas,
pasa por la confirmación de la reservación y finaliza con la generación del ticket o la visualización en el perfil del cliente.
